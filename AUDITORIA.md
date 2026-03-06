# Auditoría rápida — PixelFest 2026

| # | Problema detectado | Categoría | ¿Por qué es problema? |
|---|---|---|---|
| 1 | La navbar no es completamente responsive | Responsive Design | En pantallas pequeñas el menú no se adapta correctamente porque no utiliza el botón hamburguesa de Bootstrap. |
| 2 | Uso incorrecto del Grid System | Bootstrap / Layout | Algunas secciones no utilizan correctamente container, row y col, lo que provoca que el contenido no esté alineado correctamente. |
| 3 | Imágenes no responsivas | Responsive Design | Las imágenes no tienen la clase img-fluid, por lo que pueden desbordarse o verse demasiado grandes en dispositivos móviles. |
| 4 | Falta de jerarquía visual en los títulos | UX / Jerarquía visual | Los títulos y textos no tienen una estructura clara (h1, h2, h3), lo que dificulta identificar las secciones principales de la página. |
| 5 | Espaciado inconsistente entre secciones | Diseño / Layout | No se utilizan clases de margen o padding de Bootstrap (mt, mb, py), lo que hace que los elementos se vean muy juntos o desordenados. |
| 6 | Enlaces o botones sin funcionalidad | UX / Navegación | Algunos links utilizan href="#" o no apuntan a ninguna sección, lo que genera una mala experiencia de navegación para el usuario. |