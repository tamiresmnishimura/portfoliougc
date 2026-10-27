# Portfólio UGC

Site de uma página só: todo o código está em `index.html` (CSS e JS embutidos).
O conteúdo editável fica no objeto `CONFIG`, no topo do `<script>`.

## Publicação

- Repositório: https://github.com/tamiresmnishimura/portfoliougc (branch `main`)
- Site no ar (GitHub Pages): https://tamiresmnishimura.github.io/portfoliougc/
- A dona do site pediu que **toda alteração seja publicada direto**: depois de cada mudança, faça commit em português e `git push` para `main`, sem perguntar antes. Depois confira se o GitHub Pages terminou de publicar e se o link abre.
- No Windows desta máquina, git e gh ficam em `C:\Program Files\Git\cmd` e `C:\Program Files\GitHub CLI` (podem não estar no PATH de shells antigos).

## Logos

- As logos ficam em `logos/` como PNG transparente; no site aparecem soltas numa bolinha clara.
- Sempre que trocar uma logo, mude `VERSAO_LOGOS` no `index.html`, senão o navegador continua mostrando a versão antiga (o GitHub Pages manda guardar as imagens em cache).
- Nenhuma logo pode encostar na borda da bolinha: o pixel visível mais distante do centro deve ficar a no máximo 1,04 meia-largura da imagem.

## Regras de texto

- Português do Brasil, com acentuação, focado em vender para marcas.
- Nunca usar o caractere travessão.
