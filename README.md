# Chavrusa.Oy

Starter site estático para o projeto Chavrusa.Oy.

## Estrutura

- `index.html` — página inicial
- `sobre.html` — proposta e visão
- `estudos.html` — áreas de estudo
- `biblioteca.html` — links e fontes
- `comunidade.html` — entrada para o WhatsApp
- `contato.html` — formulário de contato
- `obrigado.html` — confirmação após o formulário
- `css/style.css` — toda a identidade visual
- `js/script.js` — menu mobile, animações e pequenos comportamentos

## Publicação

O projeto não precisa de build. Pode ser colocado diretamente em um repositório e publicado como site estático, inclusive no Vercel.

## Formulário de e-mail

O formulário usa FormSubmit para evitar a necessidade de criar um backend próprio.

Antes de publicar:

1. Abra `contato.html`.
2. Procure `SEU-EMAIL@HAVRUSA.IO`.
3. Troque pelo endereço real que receberá as mensagens.
4. Troque `https://havrusa.io/obrigado.html` pelo domínio final, se necessário.
5. Faça um primeiro envio para confirmar o endereço no FormSubmit.

A documentação atual do FormSubmit informa que o serviço funciona sem PHP, JavaScript ou backend próprio, e que o primeiro envio dispara uma confirmação por e-mail. Também oferece `_replyto`, `_subject`, `_next`, honeypot e outros campos especiais.

## Links que ainda precisam ser substituídos

- Link real do grupo do WhatsApp em `comunidade.html`
- Instagram em `index.html`/rodapé
- E-mail real em `contato.html`
- Eventuais links de shiurim e Mishnayot em `biblioteca.html`

## Direção visual

A identidade usa:
- creme/papel envelhecido
- laranja
- verde
- azul
- amarelo
- preto
- serifas de aparência editorial
- hebraico como elemento gráfico
- pequenas referências à estética ashkenazi/Yiddish

As animações são intencionalmente discretas.
