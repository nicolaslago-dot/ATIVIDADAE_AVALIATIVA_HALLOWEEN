# Halloweenflix — atividade de HTML e CSS

## Qual é a proposta?

Vamos desenvolver um site fictício sobre mídias de terror. O trabalho tem duas
partes: melhorar as páginas principais em equipe e criar uma página individual
sobre um filme, uma série, um jogo ou um livro.

**Todo o CSS será escrito pelos alunos.** Os arquivos `.css` entregues contêm
somente comentários com orientações, sem estilos prontos. Ao abrir o site pela
primeira vez, vocês verão o visual padrão do navegador. Isso é esperado.

Os HTMLs principais já têm estrutura e conteúdos de exemplo. Vocês devem
entender essa estrutura, revisar as informações, personalizar o conteúdo e
criar a apresentação visual. Não há uma quantidade de erros escondidos para
encontrar: revisem o que existe e corrijam os problemas que surgirem durante
o desenvolvimento.

Usem somente HTML e CSS. O cadastro não salva nem envia informações, o aluguel
é fictício e a contagem de Halloween tem números fixos. Não é necessário criar
JavaScript, banco de dados, login, pagamento ou reprodução de filmes.

## Por onde começar?

1. Extraiam o ZIP inteiro. Mantenham a organização das pastas para preservar os caminhos.
2. Abram `index.html` no navegador e visitem as páginas do menu.
3. Abram a pasta `Halloweenflix` no editor de código.
4. Encontrem sua equipe na tabela e leiam sua seção em [EQUIPES.md](EQUIPES.md).
5. Leiam o HTML e os comentários do CSS correspondente. Planejem o visual.
6. Façam uma mudança por vez, salvem os arquivos e atualizem o navegador.
7. Realizem também a tarefa individual descrita no guia das equipes.

## Divisão das equipes

Cada equipe tem três integrantes. Todos devem participar do HTML, do CSS,
dos testes e da apresentação. Combinem a divisão das tarefas entre vocês.

| Equipe | Integrantes | Responsabilidade | Arquivos principais |
| --- | --- | --- | --- |
| 1 — Menu e base comum | Vinicius, Lucas e Giovanny | Criar os estilos gerais e do menu; conferir cabeçalho e rodapé. | `css/global.css`, `css/menu.css` e cabeçalhos/rodapés dos HTMLs principais |
| 2 — Especial de Halloween | Micael, Giovanna S e Zaqueu | Personalizar o conteúdo e criar o visual da página temática. | `halloween.html` e `css/halloween.css` |
| 3 — Catálogo e categorias | Anna, Augusto e Mayara | Organizar filmes, gêneros, vitrine dos alunos e visual do mural de favoritos. | `filmes.html`, `categorias.html`, `css/catalogo.css` e `css/favoritos.css` |
| 4 — Detalhes e cadastro | Sibele, Helena e Giovanna B | Revisar as cinco fichas de filmes e a apresentação do formulário demonstrativo. | `detalhes-filme.html`, `cadastro.html` e `css/detalhes-cadastro.css` |
| 5 — Página inicial | Henrique, Thiago e Pedro | Personalizar apresentação, banner e destaques. | `index.html` e `css/dashboard.css` |

`favoritos.html` é compartilhado: cada equipe deve acrescentar ao menos uma
indicação própria. A Equipe 3 reúne essas contribuições e escreve o CSS dessa
página. Os três exemplos iniciais não substituem as cinco indicações das equipes.

## Como organizar o CSS?

- A Equipe 1 escreve `global.css`: cores, fonte, conteúdo principal, imagens,
  rodapé e aparência comum de cards e botões. A turma combina essas escolhas.
- A Equipe 1 também escreve `menu.css`, usado no cabeçalho das páginas principais.
- Cada equipe escreve o CSS específico das suas páginas, complementando a base comum.
- Cada aluno escreve o `style.css` da sua pasta individual e o conecta ao seu HTML.
- Escrevam as regras fora dos comentários: o texto entre `/*` e `*/` serve
  apenas de orientação e não altera a aparência da página.
- Usem arquivos CSS externos. Não coloquem estilos no atributo `style` nem
  em blocos `<style>` dentro do HTML.

Criem um tema de terror com texto legível, cores que contrastem e espaçamentos
confortáveis. Pratiquem Flexbox, Grid, efeitos ao passar o mouse, foco do teclado
e media queries para telas menores. Os comentários indicam o resultado esperado;
vocês devem escolher os seletores, as propriedades e os valores.

## Tarefa individual

Cada aluno deve criar o HTML e o CSS em `entregas-catalogo/SEU-NOME/`, usando
a pasta com seu nome que já existe. O `index.html` inicial contém apenas um
enunciado em comentário; por isso, fica vazio no navegador até que o aluno
escreva o conteúdo. Isso não significa que o link esteja quebrado.

Apresentem uma mídia de terror com título, tipo, descrição, história ou
características principais, imagem relacionada, comentário pessoal e nome do
aluno. Incluam um link de volta ao catálogo da turma. O passo a passo e os
caminhos dos arquivos estão em [EQUIPES.md](EQUIPES.md).

## Onde está cada parte?

| Arquivo ou pasta | Conteúdo |
| --- | --- |
| `index.html` | Apresentação e destaques |
| `filmes.html` | Cinco filmes de exemplo e links para detalhes |
| `categorias.html` | Links por gênero e vitrine das 15 páginas individuais |
| `halloween.html` | Mensagem temática, contagem ilustrativa e recomendações |
| `detalhes-filme.html` | Uma página com cinco seções, uma para cada filme |
| `cadastro.html` | Formulário demonstrativo, sem envio ou armazenamento |
| `favoritos.html` | Mural coletivo de indicações das equipes |
| `css/` | Orientações dos estilos que as equipes devem criar |
| `imagens/` | Logo, banner e cartazes provisórios |
| `entregas-catalogo/` | Uma pasta por aluno, com enunciados de HTML e CSS |

## Cuidados com os arquivos

- Não renomeiem pastas de alunos ou páginas sem combinar e atualizar os links.
- As páginas principais são editadas diretamente nesta pasta. Não há outra pasta
  de equipes nem cópias que se atualizem automaticamente.
- Antes de editar um arquivo compartilhado, combinem quem ficará responsável.
  Reúnam as alterações com ajuda do professor para preservar o trabalho dos colegas.
- Leiam [as orientações de imagens](imagens/LEIA-ME-ANTES.md) antes de substituir
  ou excluir algum arquivo.
- Se alterarem um filme, atualizem também seus detalhes, destaques e recomendações,
  em conjunto com as outras equipes.

## Conceitos para consultar

- `<h1>`, `<h2>` e `<h3>` organizam os títulos; não escolham a tag apenas pelo tamanho.
- `<p>` cria parágrafos; `<a>` cria links; `<img>` exibe imagens. Usem `alt`
  para descrever imagens que transmitem informação.
- `<header>`, `<nav>`, `<main>`, `<section>` e `<footer>` organizam a página.
- `class` permite compartilhar estilos; `id` identifica uma parte única da página.
- Um link com `#` seguido de um identificador leva ao elemento com esse `id`.
- O `for` de um `<label>` deve ser igual ao `id` do campo relacionado.
- Comentários de HTML e CSS aparecem no editor, mas não são conteúdo visível no site.

## O que entregar e apresentar?

- Páginas principais revisadas e personalizadas, com os CSS escritos pelas equipes.
- As 15 páginas individuais, cada uma com HTML, CSS e imagens organizadas.
- O mural com pelo menos uma indicação própria de cada equipe.
- A pasta completa do projeto, incluindo imagens e CSS.
- Uma apresentação breve: cada integrante deve mostrar uma contribuição e
  explicar uma escolha de HTML ou CSS que fez.

Antes de entregar, naveguem pelas páginas, testem links e imagens, usem Tab para
percorrer os controles e confiram a leitura em computador e celular. O trabalho
estará pronto quando o conteúdo estiver completo, o CSS tiver sido criado e
as páginas puderem ser usadas sem elementos cortados ou caminhos quebrados.
