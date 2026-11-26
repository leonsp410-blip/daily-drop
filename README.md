# DROP 30

Tienda diaria de 30 unidades. Abierta entre las 08:00 y las 20:00 (America/Guayaquil) con hora de apertura aleatoria.

## Como funciona
- **Frontend:** GitHub Pages (`index.html`, `shop.html`).
- **Backend:** Cloudflare Worker `drop-30-api3` con KV `drop30-products`.
- **API:** `/status`, `/product`, `/checkout`, `/admin/products`.
- **Pagos:** QR de Deuna. Mercado Pago pendiente de credenciales reales.

## Actualizar el sitio
Edita los archivos en este repositorio y haz commit en `main`. GitHub Pages publica automaticamente.

## Actualizar el producto
Usa `POST /admin/products` con el token de administrador (`ADMIN_TOKEN`) configurado en el Worker.
