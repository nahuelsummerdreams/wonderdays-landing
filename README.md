# WonderDays · Landing

Sitio estático (HTML + imágenes). Sin build, sin dependencias.

- `index.html` — landing en inglés (EE. UU.), la que se usa para vender.
- `es.html` — versión en español de respaldo.
- `assets/` — imágenes (`assets/en/` son las imágenes en inglés).
- `vercel.json` — solo para Vercel (cabecera de no indexar). Hostinger lo ignora.

## Publicación
- Raíz del sitio: la raíz de este repo. Archivo de entrada: `index.html`. Sin comando de build.
- Los botones de compra del Mega Pack apuntan a `https://wonderdays-megapack.impultienda.ar`.
- La página lleva `<meta name="robots" content="noindex">`: no aparece en Google hasta que se quite esa línea de `index.html` y `es.html`.

## Pendiente
- Checkout del Essential Pack (botones avisan "not enabled").
- Mail de contacto y política de devolución.
