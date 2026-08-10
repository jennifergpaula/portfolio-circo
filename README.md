# Portfolio Circo

Portfólio online para a artista circense Jennifer Gonçalves, com foco em apresentações de trapézio e performances aéreas.

Este projeto entrega uma página estática em HTML e CSS para apresentar vídeos, imagens e informações de contato profissional.

## Estrutura do repositório

- `index.html` - página principal do site com seções de apresentação, vídeos, repertório, galeria de fotos e contato.
- `style.css` - estilos visuais para o layout, tipografia, botões, responsividade e galerias.
- `imagem/` - imagens usadas no site, incluindo:
  - `foto principal.jpg` - imagem de destaque para o hero / sobre
  - `foto 01.webp`, `foto 2.jpg`, `foto 3.jpg`, `foto 4.jpg` - fotos da galeria de performance
  - `KRAMPUS-124.jpg` - imagem usada como placeholder do primeiro vídeo
  - `UAI CIRCO-509.jpg` - imagem usada como placeholder do segundo vídeo
- `.github/workflows/gh-pages.yml` - workflow do GitHub Actions que publica o site via GitHub Pages automaticamente após o push para `main`.

## Como usar

1. Abra `index.html` em um navegador ou sirva o diretório localmente.
2. Para publicar online, faça push para a branch `main` no GitHub; o workflow do GitHub Pages faz o deploy automaticamente.

## Observações

- O contato principal é feito via Instagram: `https://www.instagram.com/jennifergpaula`.
- Os vídeos na seção de destaque são exibidos como imagens de placeholder para evitar erros de embed.
