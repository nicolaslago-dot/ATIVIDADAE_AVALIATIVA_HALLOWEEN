# Halloweenflix — tarefas de revisão e conclusão

Este guia reúne os ajustes necessários para integrar as páginas e concluir a
atividade. Usem os arquivos desta versão do projeto como referência. Antes de
substituir qualquer arquivo, confirmem se há contribuições de colegas que
precisam ser preservadas.

## Ajustes para todas as equipes

- Combinar uma identidade visual: fundo `#1B1024`, cartões `#281B35`, texto
  `#F5F1F7` e destaque `#FF6A00`. Nos botões laranja, usar texto escuro com
  contraste suficiente.
- Padronizar fontes, cabeçalho, rodapé, cartões, botões e espaçamentos.
  Reservar fontes decorativas para títulos; usar fontes legíveis nos parágrafos.
- Conferir contraste, imagens e caminhos de arquivos em todas as páginas.
- Testar os links, a navegação por teclado com Tab e a leitura em telas menores.
- Manter o escopo da atividade: HTML e CSS. O cadastro é demonstrativo e o site
  não envia dados, não cobra e não reproduz filmes.

## Equipe 1 — menu e estilos comuns

**Arquivos:** [css/global.css](./css/global.css), [css/menu.css](./css/menu.css)
e os cabeçalhos e rodapés das páginas principais.

- [ ] Criar em `global.css` os estilos compartilhados: cores, tipografia,
  largura do conteúdo, imagens, cartões, botões, rodapé e foco do teclado.
- [ ] Consolidar em `menu.css` as regras duplicadas do cabeçalho e do menu.
- [ ] Corrigir seletores de interação; conferir, por exemplo, se o efeito de
  foco e de passar o ponteiro é aplicado ao próprio link.
- [ ] Alinhar logo, nome do site e links, destacando a página atual por meio de
  `aria-current="page"`.
- [ ] Conferir se o menu se reorganiza sem cortes em telas estreitas.

## Equipe 2 — especial de Halloween

**Arquivos:** [halloween.html](./halloween.html) e
[css/halloween.css](./css/halloween.css).

- [ ] Personalizar a mensagem e revisar as duas recomendações, mantendo os
  títulos e links de detalhes coerentes com o catálogo.
- [ ] Ajustar o CSS aos elementos existentes no HTML. A página usa `#contagem`
  e cartões `.card`; seletores como `.container` e `.movie-card` não encontram
  esses elementos.
- [ ] Substituir os caminhos inexistentes
  `imagens/filmes/casa-das-sombras.svg` e
  `imagens/filmes/mascara-da-meia-noite.svg` por imagens que existam no projeto.
- [ ] Organizar cartões e imagens para telas menores, sem distorcer nem
  ultrapassar a largura disponível.
- [ ] Manter explícito que a contagem usa números fixos e não se atualiza.

## Equipe 3 — catálogo e categorias

**Arquivos:** [filmes.html](./filmes.html),
[categorias.html](./categorias.html) e [css/catalogo.css](./css/catalogo.css).

- [ ] Revisar os cinco cartões: título, cartaz, texto alternativo, gênero,
  classificação, descrição e link para os detalhes.
- [ ] Conferir os dados dos filmes com a Equipe 4. Atualmente, alguns cartazes
  e textos alternativos não correspondem aos títulos anunciados.
- [ ] Verificar se cada gênero leva ao cartão correto em `filmes.html`.
- [ ] Conferir os 15 links da vitrine e organizar as grades de filmes e alunos
  para diferentes larguras de tela.
- [ ] Testar as imagens da vitrine e manter nomes e textos alternativos
  adequados.

## Equipe 4 — detalhes dos filmes e cadastro

**Arquivos:** [detalhes-filme.html](./detalhes-filme.html),
[cadastro.html](./cadastro.html) e
[css/detalhes-cadastro.css](./css/detalhes-cadastro.css).

- [ ] Alinhar as cinco fichas aos cartões de `filmes.html`: título, cartaz,
  texto alternativo, gênero, classificação, ano, duração e sinopse. Há títulos
  nas fichas que atualmente não correspondem aos títulos exibidos no catálogo.
- [ ] Preservar os identificadores usados pelos links. Se algum identificador
  mudar, atualizar também todos os links que apontam para ele.
- [ ] Organizar imagem e informações lado a lado em telas largas e empilhadas
  em telas estreitas.
- [ ] Conferir a associação entre rótulos e campos e manter claro que o cadastro
  não envia nem armazena informações. O botão de limpar deve restaurar os
  campos.

## Equipe 5 — página inicial

**Arquivos:** [index.html](./index.html) e
[css/dashboard.css](./css/dashboard.css).

- [ ] Corrigir o CSS inválido: há um bloco sem seletor, a propriedade
  `text: center` não é válida e a classe `.banner` não corresponde ao elemento
  `#banner` do HTML.
- [ ] Fazer o destaque de filme apontar para a ficha do mesmo filme anunciado.
  Atualmente, o cartão anuncia *It: A Coisa*, mas o link leva a outra ficha.
- [ ] Revisar o texto de apresentação para citar apenas áreas que existem no
  site, como filmes, catálogo da turma e especial de Halloween.
- [ ] Ajustar banner, imagens, contraste e espaçamento para telas menores.
- [ ] Manter visível que o site é fictício e não reproduz nem aluga filmes.

## Páginas individuais dos alunos

Na conferência desta versão, estas páginas ainda continham apenas o enunciado:

| Equipe | Páginas a completar |
| --- | --- |
| Equipe 1 | Vinicius |
| Equipe 2 | Giovanna S e Micael |
| Equipe 3 | Anna, Augusto e Mayara |
| Equipe 4 | Giovanna B, Helena e Sibele |
| Equipe 5 | Henrique |

Cada aluno deve revisar sua própria página e incluir:

- [ ] Nome, título e tipo da mídia.
- [ ] Descrição, história ou características e comentário pessoal.
- [ ] Imagem relacionada, com texto alternativo adequado.
- [ ] Folha `style.css` própria conectada ao HTML.
- [ ] Link de retorno para `../../categorias.html`.
- [ ] Layout legível em computador e celular.

As páginas já preenchidas também precisam ser conferidas quanto a conteúdo,
imagens, links de retorno, CSS conectado e adaptação para telas menores.

## Como atualizar o projeto pela `main`

No terminal, dentro da pasta do projeto, execute:

```bash
git switch main
git pull --ff-only origin main
```

O comando atualiza a branch local `main` com as alterações publicadas no
repositório remoto. Se houver alterações locais ainda não salvas em um commit,
faça commit delas ou guarde-as antes de atualizar.

## Conferência antes da entrega

- [ ] Revisar os cinco cartões e as cinco fichas de detalhes em conjunto.
- [ ] Abrir todos os links do menu, gêneros, detalhes e páginas individuais.
- [ ] Confirmar que imagens e folhas CSS carregam sem erros.
- [ ] Navegar com Tab e verificar se o foco está sempre visível.
- [ ] Testar em computador e celular; não deve haver conteúdo cortado nem
  rolagem horizontal desnecessária.
- [ ] Reunir as contribuições sem apagar o trabalho já feito e garantir que cada
  integrante consiga explicar sua participação.
