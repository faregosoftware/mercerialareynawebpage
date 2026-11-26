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

## Cómo editar el contenido (panel Pages CMS)
Todo el contenido vive en dos archivos, que se editan desde un panel con formularios:
- `content/sitio.json`: portada, historia, misión, visión, valores, servicios, galería, "sobre", sucursales y WhatsApp.
- `content/productos.json`: productos (nombre, categoría, precio, venta en línea sí/no, foto o dibujo, visible sí/no).

**Entrar al panel**
1. Abre https://app.pagescms.org e inicia sesión con la cuenta de GitHub **faregosoftware**.
2. Autoriza el acceso y elige el repositorio **mercerialareynawebpage**.
3. Verás dos secciones: **Productos** y **Textos, fotos y sucursales**.
4. Edita, sube fotos y pulsa **Save**. Cada cambio queda guardado en GitHub y la web se actualiza en 1–2 minutos.

**Agregar un producto:** Productos → Lista de productos → Add → llena nombre, categoría, precio, activa "Se vende en línea" (o déjalo apagado para "Solo por consulta"), sube foto si tienes → Save.

**Invitar a otra persona** (por ejemplo, una empleada): en el panel, Settings → Collaborators → invita por correo. No necesita cuenta de GitHub.

La configuración del panel está en `.pages.yml`. Las fotos se guardan en la carpeta `fotos/`.

## Publicar con GitHub Pages
Settings → Pages → Branch: `main` / root. El sitio queda en `https://faregosoftware.github.io/mercerialareynawebpage/`.
