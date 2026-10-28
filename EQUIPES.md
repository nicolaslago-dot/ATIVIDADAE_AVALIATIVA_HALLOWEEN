# Guia das equipes — Halloweenflix

Leiam primeiro o [README.md](README.md). Este guia detalha as tarefas e como
conferir o resultado. **Todos os estilos serão escritos pelos alunos.**
Os CSS contêm somente orientações; não há uma solução visual pronta.

## Combinados da turma

- Mantenham os nomes de arquivos e pastas. Conversem antes de editar arquivos compartilhados.
- Combinem cores, fonte, cards e botões com a Equipe 1, responsável pela base comum.
- Personalizem o conteúdo com suas palavras; não basta deixar os exemplos como estão.
- Escrevam o CSS nos arquivos externos, fora dos comentários, e testem a cada etapa.
- Mantenham os dados de cada filme iguais nas páginas em que ele aparece.
- Não implementem envio, armazenamento, cobrança ou reprodução de mídia.
- Todos devem participar do desenvolvimento, da revisão e da apresentação.

## Equipe 1 — Menu e base comum

**Integrantes:** Vinicius, Lucas e Giovanny.  
**Arquivos:** `css/global.css`, `css/menu.css` e cabeçalhos/rodapés das sete páginas principais.

### O que fazer

1. Combinem com a turma as cores, a fonte e o padrão de cards e botões.
2. Escrevam `global.css` para fundo, texto, largura do conteúdo, imagens que
   caibam na tela, rodapé, cards, botões e foco do teclado.
3. Escrevam `menu.css` para organizar logo, nome e links com Flexbox. Adaptem
   o cabeçalho para manter os links acessíveis em telas estreitas.
4. Confiram os links para Início, Filmes, Mídias favoritas, Catálogo da turma,
   Halloween e Cadastro em todas as páginas principais.
5. Criem no CSS um destaque para a página atual. O atributo `aria-current="page"`
   já identifica no HTML o link que deve receber esse destaque.
6. Confiram logo, links de retorno e créditos do rodapé com as outras equipes.

As páginas individuais precisam de um retorno ao catálogo da turma, sem a
obrigação de repetir o menu completo. A Equipe 1 pode orientar os colegas
sobre a base comum, mas não deve fazer o CSS individual por eles.

### Pronto quando

Há uma base visual consistente, os links funcionam, o menu cabe em telas
menores e o foco aparece ao navegar com Tab.

## Equipe 2 — Especial de Halloween

**Integrantes:** Micael, Giovanna S e Zaqueu.  
**Arquivos:** `halloween.html` e `css/halloween.css`.

### O que fazer

1. Reescrevam a mensagem inicial com uma apresentação temática da equipe.
2. Revisem o banner. Se substituírem imagens, atualizem caminhos e textos alternativos.
3. Personalizem pelo menos duas recomendações de filmes do catálogo. Cada uma
   deve ter imagem, título, gênero, classificação fictícia, descrição e link
   para a seção correta dos detalhes. Combinem mudanças com as Equipes 3 e 4.
4. Mantenham o aviso de que a contagem usa números fixos. Não é necessário
   criar uma contagem que se atualiza sozinha.
5. Escrevam o CSS: destaquem mensagem e contagem, organizem os cards e façam
   as imagens caberem na tela. A decoração não pode prejudicar a leitura.

### Pronto quando

A mensagem foi personalizada, as recomendações correspondem ao catálogo,
os links e imagens funcionam e a página é legível em computador e celular.

## Equipe 3 — Catálogo, categorias e mural

**Integrantes:** Anna, Augusto e Mayara.  
**Arquivos:** `filmes.html`, `categorias.html`, `css/catalogo.css` e
`css/favoritos.css`. A equipe também reúne as contribuições de `favoritos.html`.

### O que fazer

1. Revisem os cinco cards de filmes: imagem, título, gênero, classificação
   fictícia, sinopse curta e link para a seção correta de detalhes.
2. Melhorem as descrições. Combinem com a Equipe 4 para manter a mesma
   história, gênero e classificação nas duas páginas.
3. Confiram as duas áreas de `categorias.html`: links por gênero e vitrine dos
   alunos. Cada gênero deve levar ao card correspondente de `filmes.html`.
4. Confiram os 15 nomes e caminhos individuais. Cada aluno faz sua página;
   a Equipe 3 cuida da vitrine e dos links.
5. Escrevam `catalogo.css` para organizar filmes e alunos em grades adaptáveis
   à largura da tela. Estilizem também a lista de gêneros e seus links.
6. Reúnam uma indicação própria de cada equipe em `favoritos.html` e escrevam
   `favoritos.css`, aproveitando a base comum feita pela Equipe 1.

No início, as páginas individuais ficam vazias porque só têm o enunciado.
Isso é esperado antes do desenvolvimento; na entrega, todas devem ter conteúdo.

### Pronto quando

Os cinco filmes têm informações completas, os gêneros levam aos cards certos,
os 15 links individuais funcionam e o mural contém as cinco contribuições
das equipes. As grades devem funcionar em computador e celular.

## Equipe 4 — Detalhes e cadastro

**Integrantes:** Sibele, Helena e Giovanna B.  
**Arquivos:** `detalhes-filme.html`, `cadastro.html` e `css/detalhes-cadastro.css`.

### O que fazer

1. Revisem as cinco seções de detalhes: imagem, título, ano, duração, gênero,
   classificação fictícia e sinopse. Melhorem os textos com suas palavras.
2. Confiram os dados com a Equipe 3. Todas as seções ficam na mesma página;
   não é preciso criar cinco arquivos de detalhes.
3. Preservem os identificadores das seções para manter os links do catálogo
   e das recomendações funcionando.
4. Revisem os campos de título, imagem, gênero e descrição. Confiram a
   associação entre rótulos e campos e a indicação dos campos obrigatórios.
5. Mantenham o aviso de demonstração. Cadastrar é ilustrativo e não envia nem
   valida os campos: o atributo `required` indica a intenção do modelo, mas
   não aciona validação ao clicar em um botão de tipo `button`. Limpar deve
   apenas restaurar os campos. Não implementem envio ou armazenamento.
6. Escrevam o CSS para imagem e dados lado a lado quando houver espaço e
   empilhados em telas menores. Estilizem rótulos, campos e botões, incluindo
   o foco para quem navega com teclado.

### Pronto quando

Os links abrem as cinco seções corretas, os dados correspondem ao catálogo
e o formulário é legível e claramente demonstrativo.

## Equipe 5 — Página inicial e destaques

**Integrantes:** Henrique, Thiago e Pedro.  
**Arquivos:** `index.html` e `css/dashboard.css`.

### O que fazer

1. Reescrevam a apresentação explicando o projeto e o que o visitante encontrará:
   filmes de exemplo, produções individuais e indicações da turma.
2. Revisem banner e filme em destaque: imagem, título, gênero, classificação,
   descrição e link para a seção correspondente dos detalhes.
3. Mantenham acessos claros a filmes, categorias, páginas individuais e Halloween.
4. Organizem os títulos: um título principal e subtítulos para as seções.
5. Escrevam o CSS para destacar o banner e organizar as seções. Imagens e
   textos devem caber em telas estreitas e combinar com a base comum.
6. Mantenham o aviso de que o site é fictício e não reproduz filmes.

### Pronto quando

O visitante entende a proposta e chega às áreas principais pelos links.
O banner e o restante da página cabem em telas menores.

## Tarefa individual — crie sua página

Esta parte é obrigatória para os 15 alunos, além do trabalho em equipe.
Sua pasta já existe em `entregas-catalogo/`. Use a que corresponde ao seu nome,
sem renomeá-la ou criar uma segunda pasta. `index.html` e `style.css` contêm
apenas enunciados; você deve desenvolver a página.

### Passo a passo

1. Escolha um filme, uma série, um jogo ou um livro de terror ou horror.
2. Abra seu `index.html` no editor e leia o comentário. A página vazia no
   navegador é esperada enquanto existir somente o enunciado em comentário.
3. Em uma linha depois do fechamento do comentário, crie a estrutura HTML.
   No Visual Studio Code, o atalho `!` seguido de Enter pode ajudar. Confira
   idioma, codificação, configuração para celular e título da aba.
4. Inclua seu nome, título e tipo da mídia, descrição com suas palavras,
   história ou características principais e um comentário pessoal sobre a escolha.
5. Crie uma pasta `imagens` dentro da sua pasta e guarde uma imagem relacionada
   à mídia. Inclua-a no HTML com um texto alternativo adequado.
6. Conecte seu `style.css` por meio de um elemento `<link rel="stylesheet">`
   no `<head>`. O CSS está ao lado do HTML; o caminho é `style.css`.
7. Escreva seu próprio CSS: escolha cores e fontes, organize as áreas, crie
   espaçamentos e faça a imagem caber na tela. Não copie o CSS de um colega.
8. Inclua o retorno ao catálogo da turma. Teste seu cartão em `categorias.html`
   e confirme se consegue voltar por esse link.

### Como entender os caminhos

Os caminhos são relativos ao arquivo em que você está trabalhando:

| O que acessar a partir do HTML individual | Caminho |
| --- | --- |
| Seu próprio CSS | `style.css` |
| Uma imagem chamada cartaz.jpg na sua pasta imagens | `imagens/cartaz.jpg` |
| O catálogo da turma | `../../categorias.html` |
| A base comum da turma, caso queira usá-la também | `../../css/global.css` |

Cada `../` volta uma pasta. Mesmo que use a base comum, você deve escrever
o CSS da sua página em `style.css`. `cartaz.jpg` é um exemplo: use o nome e
a extensão reais da imagem escolhida.

### Pronto quando

Seu cartão abre uma página com conteúdo próprio, imagem visível, seu nome,
CSS escrito por você e link de retorno funcionando. A leitura deve ser
confortável em computador e celular.

## Contribuição coletiva — Mídias favoritas

Cada equipe deve acrescentar ao menos uma indicação própria em `favoritos.html`.
Essa contribuição é diferente da página individual de cada aluno.

1. Escolham a mídia e combinem com a Equipe 3 o momento de editar o arquivo.
2. Copiem um bloco completo `<article class="card">` dentro de `.grade-cards`.
3. Atualizem tipo, gênero, título, descrição e identificação da equipe.
4. Se usarem imagem, salvem o arquivo e incluam texto alternativo. Também podem
   manter o pôster ilustrativo do modelo, atualizando o tipo da mídia.
5. A Equipe 3 organiza o mural e escreve `css/favoritos.css`.

Os três cards iniciais são modelos. Na entrega, deve haver pelo menos cinco
indicações próprias, uma de cada equipe, identificadas por equipe ou integrantes.

## Conferência e apresentação

- Percorram menu, gêneros e os cinco detalhes de filmes.
- Abram as 15 páginas individuais e testem o retorno ao catálogo da turma.
- Confiram imagens, textos alternativos e correspondência com o conteúdo.
- Reduzam a janela e testem no celular: textos e controles não devem exigir
  rolagem para os lados.
- Usem Tab para percorrer links, botões e campos, observando o foco.
- Confiram os links dos CSS e se escreveram as regras fora dos comentários.
- Entreguem a pasta completa, incluindo imagens e CSS. Os enunciados sozinhos
  não representam o trabalho concluído.
- Cada integrante deve explicar uma contribuição, uma escolha de HTML ou CSS
  e como testou o resultado.
