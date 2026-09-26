# Entre Momentos — sitio en HTML puro

Sin frameworks, sin JavaScript, sin build. Solo HTML + CSS + imágenes — ábrelo, edítalo con cualquier editor de texto, y súbelo a donde quieras.

## Archivos

- `index.html` — página principal (portada + los 6 aromas)
- `slow-morning.html`, `fresh-air.html`, `myself.html`, `unwind.html`, `ritual.html`, `coffee.html` — página de cada aroma
- `styles.css` — todos los estilos (colores, tipografía, tarjetas)
- `images/` — fotos

## Cómo editar

- **Textos y precios**: ábrelos con cualquier editor y cambia el texto directamente en el HTML.
- **Fotos**: reemplaza el archivo dentro de `images/` con el mismo nombre, o cambia el `src="images/..."` en el HTML por el nombre de tu nueva foto.
- **Notas de fragancia y variantes de producto** (Wax Melt individual / Set x3): aún no tienen foto real — están marcadas como "Foto: ..." dentro de cada página de aroma. Agrega tu imagen en `images/` y reemplaza ese bloque por `<img src="images/tu-foto.jpg" alt="...">`.
- **Número de WhatsApp**: es `573054169214`, aparece en los enlaces `href="https://wa.me/573054169214..."` — reemplázalo si cambia.

## Cómo subirlo

Sirve como sitio estático en cualquier hosting (GitHub Pages, Netlify, Vercel, tu propio servidor). Solo sube la carpeta completa tal cual — no necesita instalación ni build.
