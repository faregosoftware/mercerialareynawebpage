# Mercería La Reina

Sitio web de Mercería La Reina (República Dominicana): presencia en la web, presentación de la empresa y venta de productos por WhatsApp.

## Estructura de la página
1. **Encabezado**: logo y menú en píldoras (Inicio, Nosotros, Servicios, Productos, Galería, Contacto) + carrito.
2. **Portada**: carrusel animado (logo, tienda, cintas, cuentas, equipo, ventas al por mayor).
3. **Historia del negocio**: foto de la tienda y texto.
4. **Lo que nos mueve**: Misión, Visión y Valores.
5. **Servicios**: 4 recuadros con foto que abren el catálogo filtrado + servicios adicionales.
6. **Nuestros productos**: catálogo con filtros, buscador y carrito.
   - `v:1` = se vende en línea (precio y "Agregar al carrito").
   - `v:0` = "Solo por consulta" (abre WhatsApp).
7. **Galería**: fotos de la tienda.
8. **Sobre Mercería La Reina**: presentación corta con el logo.
9. **Nuestras sucursales**: 3 tiendas con horario, "Abierto/Cerrado ahora", Llamar y Cómo llegar.
10. **Pie de página**: Información, Sucursales y Enlaces.

## Personalizar (en `index.html`, al inicio del `<script>`)
- `CFG.wa`: número de WhatsApp para pedidos (formato 1809XXXXXXX).
- `SUC`: sucursales, teléfonos y horarios.
- `P`: productos (nombre, categoría, precio, venta en línea sí/no, descripción).
- `SL`: diapositivas de la portada. `TILES`: recuadros de Servicios. `GAL`: fotos de la galería.

Las fotos van en la carpeta `fotos/`. El logo es `logo-la-reina.png`.

## Publicar con GitHub Pages
Settings → Pages → Branch: `main` / root. El sitio queda en `https://faregosoftware.github.io/mercerialareynawebpage/`.
