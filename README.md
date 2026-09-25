# Plano Criciúma 2047 — Protótipo

Protótipo estático responsivo em HTML, CSS e JavaScript.

## Como abrir

Basta abrir `index.html` no navegador.

## Como publicar gratuitamente

Funciona diretamente em:
- GitHub Pages
- Cloudflare Pages
- Netlify
- Vercel

Não há build nem dependências obrigatórias.

## Estrutura

- `index.html` — conteúdo e estrutura
- `styles.css` — layout e responsividade
- `script.js` — menu mobile e navegação ativa
- `assets/` — imagens e arquivos futuros

## Imagem do estádio

O protótipo atual usa fundo abstrato em CSS para evitar dependência de imagem externa.

Quando houver uma imagem oficial/licenciada, substitua a regra `.hero-bg` em `styles.css` por:

```css
.hero-bg {
  position: absolute;
  inset: 0;
  background: url("./assets/estadio.jpg") center/cover no-repeat;
}
```

## Observação importante

O conteúdo e os indicadores são ilustrativos e devem ser substituídos pelos dados oficiais/validados do projeto antes da publicação pública.
