# +150 Revistas Biológicas

Página de vendas das Revistas Biológicas (coleção para professores do Fundamental II ao Ensino Médio, alinhada à BNCC).

## Estrutura

- `index.html` — página completa (HTML, CSS e JS num único arquivo)
- `images/mockup-revistas.webp` — imagem principal
- `images/capas/` — capas do carrossel
- `images/bonus/` — imagens dos 5 bônus

## Onde editar

- **Revistas do carrossel:** array `CAPAS` no script do `index.html` (`FAIXA_1` e `FAIXA_2` definem a ordem de cada faixa)
- **Bônus:** array `BONUS`
- **Perguntas frequentes:** array `FAQ`
- **Links de checkout:** atributos `href` dos elementos com `data-checkout="premium" | "upsell" | "basico"`
- **Preço do popup:** constante `PRECO_UPSELL`

## Rastreamento

- Utmify (pixel + UTMs) e Meta Pixel no `<head>`
- Evento `InitiateCheckout` disparado ao clicar em qualquer botão de compra

## Publicar

É um site estático: funciona em GitHub Pages, Vercel, Netlify ou qualquer hospedagem.
Para GitHub Pages: *Settings → Pages → Branch: main / root*.
