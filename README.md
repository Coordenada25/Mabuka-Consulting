# Mabuka Advisory — lista de espera

Página estática (um só ficheiro, `index.html`) para recolher emails de potenciais clientes.
Os emails são enviados para o Buttondown com a etiqueta `waitlist`.

## Configuração
No fim do `index.html`, altera:

- `BUTTONDOWN_USER` — username da conta no Buttondown
- `TAG` — etiqueta aplicada a quem se inscreve

## Publicar
Funciona em qualquer alojamento estático (Cloudflare Pages, Netlify, GitHub Pages).
Não tem build: a pasta raiz é a pasta de publicação.
