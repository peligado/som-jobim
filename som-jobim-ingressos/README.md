# Som Jobim - Ingressos

Site estático (HTML/CSS/JS) de venda de ingressos do Show de Alunos Som Jobim.

## Como publicar
1. Suba esta pasta em um repositório no GitHub.
2. No Vercel: Add New > Project > importe o repositório > Deploy (Framework Preset: Other, sem build).

## Onde editar (no final do index.html, dentro de <script>)
- `PRICE`: valor do ingresso
- `WA`: número do WhatsApp (55 + DDD + número)
- `LOTE_VIRA`: data da virada do lote
- Chave Pix: texto dentro de `<span id="key">`
- QR Code: troque `assets/qr-pix.png`
