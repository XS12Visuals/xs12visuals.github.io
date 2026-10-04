# XS12 Visuals — CMS con Pages CMS

Esta versión utiliza Pages CMS, pensado para editar repositorios de GitHub sin tener que programar.

## Primer acceso

1. Abre Pages CMS desde https://pagescms.org/
2. Entra con GitHub.
3. Selecciona el repositorio `XS12Visuals/xs12visuals.github.io`.
4. Pages CMS leerá `.pages.yml` y mostrará los apartados configurados.

## Qué puedes editar

- portada y textos
- español / gallego / inglés
- fotografías
- imágenes
- categorías
- orden
- artículos científicos
- novedades
- biografía
- Instagram y correo

Los cambios se guardan en GitHub. GitHub Pages volverá a publicar la web automáticamente.

IMPORTANTE: esta versión sustituye Sveltia CMS porque el flujo anterior estaba intentando utilizar una autenticación de Netlify que no estaba configurada para este sitio.


## Estructura de páginas

La portada es un resumen. Los apartados completos tienen URLs independientes:

- `/proyecto/`
- `/portfolio/`
- `/ciencia/`
- `/novedades/`
- `/sobre-mi/`
- `/contacto/`

GitHub Pages no permite crear URLs como `proyecto.github.io` dentro del mismo sitio sin crear otros sitios/dominios; por eso se usa esta estructura, que queda como `https://xs12visuals.github.io/proyecto/`, etc.
