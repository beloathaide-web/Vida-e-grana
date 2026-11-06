# Vida & Grana

Jogo educativo de finanças: viva uma vida inteira e aprenda a investir na prática.
Feito por **AB Games**.

## Estrutura

| Caminho | O que é |
|---|---|
| `index.html` | O jogo inteiro (HTML, CSS e JavaScript num arquivo só). |
| `historico/AAAA.csv` | Cotações históricas da B3 por ano (data, ticker, fechamento), usadas no modo de simulação histórica. |
| `privacidade.html` | Política de privacidade (também usada na Play Store). |
| `img/` | Ícone e imagem de capa. |
| `.nojekyll` | Faz o GitHub Pages servir os arquivos como estão. |

## Publicar o site (GitHub Pages)

Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Configurações no `index.html`

Perto do início do script:

- `SB_URL`, `SB_KEY`: servidor Supabase (ranking e Bolsa de verdade). A chave é a
  publicável, feita para ficar no app: o banco só permite leitura e o envio de pontuações.
- `PLAY_URL`: quando o app estiver na Play Store, coloque o link aqui e o botão
  "Baixar o app" passa a funcionar.

## Dados

Cotações históricas: série histórica COTAHIST da B3, sem ajuste por proventos.
Jogo educativo. Nada aqui é recomendação de investimento.
