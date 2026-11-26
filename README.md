# Mercería La Reina

Sitio web de Mercería La Reina (República Dominicana): presentación de la empresa, catálogo de productos y carrito de compras.

- Los productos con `v:1` se venden en línea (precio en RD$ y botón "Agregar al carrito").
- Los productos con `v:0` se muestran "Solo por consulta" y abren WhatsApp.
- El pedido se envía por WhatsApp con el detalle del carrito y los datos del cliente.

## Personalizar
En `index.html`, al inicio del `<script>`:
- `CFG`: número de WhatsApp (formato 1809XXXXXXX), teléfono, correo y dirección.
- `P`: lista de productos (nombre, categoría, precio, venta en línea sí/no, descripción).

## Publicar con GitHub Pages
Settings → Pages → Branch: `main` / root. El sitio queda en `https://<usuario>.github.io/mercerialareynawebpage/`.

## Collage de fotos
Las fotos van en la carpeta `fotos/` con los nombres indicados en `fotos/LEEME.md`. Para cambiar textos o nombres, edita la lista `GAL` en `index.html`.
