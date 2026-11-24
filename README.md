# URBAN DROP — Streetwear Supply Co.

Versión rediseñada del catálogo streetwear.

## Diseño y navegación
- Identidad visual nueva: azul cobalto, naranja y base crema; composición editorial tipo lookbook.
- Estructura distinta a los sitios anteriores: cabecera horizontal, portada de campaña, catálogo en tarjetas grandes, temporada fría y ficha de tienda.
- Un solo `index.html`, adaptable a escritorio y móvil.
- Navegación por pantallas, sin scroll vertical.
- Catálogo integrado directamente en `js/app.js` para que cargue también al abrir el HTML localmente (no depende de `fetch`).
- Filtros, búsqueda, paginación, tema claro/oscuro y navegación móvil.

## Productos
- 13 fotos reales proporcionadas, optimizadas a WebP.
- 4 visuales SVG de referencia para polar afelpado, sherpa, hoodie fleece y jogger térmico.
- Precios y tallas de ejemplo en `json/products.json` y en el arreglo integrado de `js/app.js`. Mantener ambos sincronizados al editar.

## Datos
- TikTok: https://www.tiktok.com/@novedadesymuchomas2
- Teléfono: +591 77704529
- Los precios y tallas son referenciales. Las imágenes marcadas como REFERENCIA no representan inventario confirmado.

## PWA
Manifest y Service Worker incluidos. Publicar en GitHub Pages o probar desde localhost/HTTPS para habilitar instalación y caché offline.
