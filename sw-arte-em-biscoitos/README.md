# SW Arte em Biscoitos — site

Site de uma página (HTML/CSS/JS puros, sem build). Desenvolvido por visualvaro design.

## Antes de publicar
Abra `index.html`, procure por `CONFIGURAÇÃO` (início do último `<script>`) e preencha:

- `WHATSAPP` — já está com 5511977136836; altere só se o número mudar
- `EBOOK_URL` — link de compra do ebook (se vazio, o botão abre uma mensagem no WhatsApp)

## Publicar na Vercel
1. Vercel → Add New → Project → importe o repositório (ou arraste esta pasta).
2. Framework Preset: **Other**. Build Command e Output Directory: deixe vazios (o site é estático, `index.html` na raiz).
3. Deploy. O arquivo `vercel.json` já cuida do cache das imagens.

## Publicar no GitHub Pages
Suba os arquivos na raiz do repositório → Settings → Pages → Branch `main` / `/ (root)`.

Fontes: Anton e Poppins carregam do Google Fonts; a Gochi Hand já está em `assets/`. Imagens ficam em `assets/`.
