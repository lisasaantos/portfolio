# Portfólio · Elisangela Santos

Site estático (HTML + CSS + JS puro), pronto para GitHub Pages.

## Publicar
1. Crie um repositório público, por exemplo `elisangela-santos`.
2. Envie o conteúdo desta pasta (`index.html` e a pasta `img/`) para a raiz do repositório.
3. Em **Settings → Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
4. O site fica em `https://SEU-USUARIO.github.io/elisangela-santos/`.

## Depois de publicar
- No `<head>` do `index.html`, troque `SEU-USUARIO` nas tags `og:image` e `og:url` pelo seu usuário. É isso que gera a prévia com foto quando o link é colado no WhatsApp.
- Telefone, mensagem do WhatsApp e e-mail ficam no início do `<script>`, no fim do arquivo.

## Trocar ou adicionar fotos
Cada foto tem duas versões em `img/`: `nome-sm.webp` (800px, usada na grade) e `nome.webp` (1600px, usada ao ampliar).
Para incluir uma nova, copie um bloco `<figure class="card">` da seção Portfólio e ajuste `src`, `data-full`, `data-cat` (`carnaval`, `marcas` ou `shows`), o selo e a legenda.
