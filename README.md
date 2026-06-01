# Ingoo — Plano de Crescimento Copa 2026

Deck online em HTML/CSS (reveal.js) com a identidade visual oficial da Ingoo.

## Stack
- HTML + CSS + reveal.js 5.1 (CDN)
- Fontes Google: Inter + Space Grotesk
- Paleta extraída de `~/projetos/ingoo-site/styles.css`
- Docker + nginx (mesmo padrão de `tutorial-ingooapp`)

## Local
```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Deploy (Coolify)
1. Push pra `github.com/agf3xdev/ingoo-pitch-copa`
2. Nova aplicação Coolify do tipo Dockerfile
3. Subdomínio sugerido: `plano-copa.ingooapp.com.br`

## Navegação
- Setas / espaço / clique nos controles
- `F` fullscreen, `Esc` overview, `S` notas
- URL com hash sincronizado (compartilhar slide específico)

## Estrutura
- `index.html` — 17 slides
- `styles.css` — tema Ingoo
- `brand/` — assets oficiais (logo SVG branca + PNG colorida)
