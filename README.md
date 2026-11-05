# Landing page — E-book de Tráfego Pago

Página estática, responsiva e em português, feita para apresentar o e-book e encaminhar o visitante ao checkout da Kiwify.

## Arquivos
- `index.html`: conteúdo da página.
- `style.css`: identidade visual e layout responsivo.
- `script.js`: pequenos ajustes de interface.

## Antes de publicar
1. Confirme o nome/identidade da marca exibida no topo (`TRÁFEGO PRO`).
2. Quando cadastrar o produto na Kiwify, copie o link do checkout.
3. No `index.html`, localize o botão com `id="checkout-button"` e substitua o `href="#contato"` pelo link do checkout.
4. Revise preço, garantia, suporte, formato de entrega e demais condições antes de incluí-los na página. Eles não foram inventados neste modelo.

## Publicar na Vercel
Importe o repositório no Vercel como projeto estático. Não precisa configurar banco de dados nem variáveis do Supabase para esta página.
