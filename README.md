# Portafolio de Sohany Galán García

**Repositorio público:** https://github.com/SohanyGalan/portafolio-sohany-galan  
**GitHub Pages:** https://sohanygalan.github.io/portafolio-sohany-galan/  
**Vercel:** https://portafolio-sohany-galan.vercel.app/

Portafolio estático responsive de Sohany Galán García (matrícula `24-sisn-8-004`), estudiante de Ingeniería de Sistemas y Computación. Presenta su experiencia en desarrollo web, diseño visual y coordinación de contenido, además de sus intereses en UX/UI, QA y gestión de proyectos. Incluye su foto de portada, cuatro capturas de sitios publicados, muestras visuales de SG Custom Works, Hard Devs y ASSB SolutionsTech, un prototipo web de Kodigo Nub en Figma, una vista del sistema de ventas La Reserva con datos ocultos y tres certificados ampliables. Las imágenes están incorporadas dentro de `index.html`, junto con el fondo Matrix, la alternancia dark/light, nueve proyectos filtrables (3 Web, 3 App y 3 Diseño), tres videos responsivos y nueve tarjetas adicionales comentadas. El formulario abre `mailto:` mientras se configura EmailJS; esto **no equivale a un envío automático confirmado**.

La información profesional procede del CV facilitado por Sohany. Ella confirmó su participación integral en el diseño y desarrollo de Andreina Taveras, Gap Móviles y Catálogo La Reserva; Listado La Reserva, el sistema de ventas y el diseño de Kodigo Nub se añadieron por petición suya. Las nueve tarjetas muestran trabajos concretos; el prototipo de Figma se presenta como diseño, no como sitio publicado.

## Proyectos web publicados

- [Andreina Taveras](https://www.andreinataveras.com/es) — diseño y desarrollo del sitio profesional.
- [Gap Móviles](https://www.gapmoviles.com/) — diseño y desarrollo del sitio comercial.
- [Catálogo La Reserva](https://catalogo.lareservasd.online/) — diseño y desarrollo del catálogo con búsqueda y filtros.
- [Listado La Reserva](https://www.listadolareserva.com/) — listado mayorista de perfumes con búsqueda y precios.

## Aplicación de gestión

- Sistema de ventas La Reserva — panel administrativo para ventas, clientes, inventario y reportes. La vista previa está editada para ocultar montos, cantidades y fechas antes de publicarla.
- El Catálogo La Reserva y Listado La Reserva aparecen en el filtro **App** porque son aplicaciones web interactivas; siguen enlazados como sitios públicos.

## Diseño visual

- SG Custom Works — identidad visual.
- Hard Devs — planificación y contenido para la comunidad.
- ASSB SolutionsTech — piezas para redes de un servicio técnico.
- Kodigo Nub — prototipo de sitio web en Figma (inicio, presentación y servicios).

El prototipo Kodigo Nub aparece en el filtro **Web** para completar los tres casos web, pero se identifica expresamente como prototipo, no como sitio publicado. Las otras tres muestras visuales integran el filtro **Diseño**.

## Certificados y reconocimientos

- Google/Coursera — Foundations of Project Management, 30 de mayo de 2025.
- ITLA — Manejo de Proyectos con Metodología Scrum y Agile, 40 horas, diciembre de 2025.
- Instituto Cultural Dominico Americano — reconocimiento por excelencia académica en English Immersion Program, 28 de noviembre de 2025.

## Tecnologías

- HTML5, CSS3 y JavaScript
- Bootstrap 5 (CDN)
- Canvas API para el fondo Matrix
- EmailJS Browser SDK para el formulario
- Devicon (logotipos de tecnologías) y Font Awesome (iconos de contacto)

## Publicación en GitHub Pages

1. Se creó el repositorio público `SohanyGalan/portafolio-sohany-galan` con README y licencia MIT.
2. Se subió `index.html` mediante **Add file > Upload files** en la interfaz de GitHub y se confirmó en `main`.
3. En **Settings > Pages** se seleccionó **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Se comprobó la URL pública de GitHub Pages indicada arriba (HTTP 200 y contenido correcto).

## Activar el formulario

Sin configuración de EmailJS, el formulario abre la aplicación de correo del visitante con el mensaje preparado; el visitante debe enviarlo allí. Para envío directo desde la página, crea una cuenta/proyecto en [EmailJS](https://www.emailjs.com/), configura un servicio y una plantilla, y reemplaza los tres valores vacíos de `emailConfig` al final de `index.html` con el public key, service ID y template ID. Después prueba un envío real. No incluyas contraseñas ni claves privadas en el código público.

## Comparación: GitHub Pages vs Vercel

| Criterio | GitHub Pages | Vercel |
| --- | --- | --- |
| Mejor para | Sitio estático y repositorio académico | Apps frontend y despliegues automatizados |
| Deploy | Desde una rama/carpeta | Desde Git o CLI |
| Funciones serverless | No | Sí |
| Preview por rama | No nativo | Sí |
| Recomendación | Este portafolio HTML estático | Si después incorpora backend/API |

Se importó el mismo repositorio en Vercel. La URL de producción indicada arriba respondió con HTTP 200 y mostró el contenido del portafolio. Ambas plataformas sirven el mismo `index.html`; GitHub Pages es la entrega principal solicitada y Vercel permite comparar el flujo de importación Git y los despliegues automáticos.

## Métricas estimadas de tiempo

| Nivel | Estimación | Alcance |
| --- | ---: | --- |
| Aprendiz / estudiante | 8–15 h | Comprensión, personalización, despliegue y documentación |
| Junior en empresa | 4–7 h | IA, personalización, despliegue y README/PDF |
| Junior freelancer | 5–8 h | Revisión adicional para cliente |
| Semi-senior en empresa | 2.5–4 h | Prompt, QA, despliegue y documentación |
| Semi-senior freelancer | 3–5 h | Pruebas multidispositivo y entrega |
| Senior en empresa | 1.5–3 h | Dirección, control de calidad y despliegue dual |
| Senior freelancer | 2–3.5 h | SEO, accesibilidad y rendimiento |
| Experto full stack | 1–2 h | Automatización y revisión final |

Estos rangos proceden de la tabla estimativa del documento de la asignatura; no son tiempos medidos en este proyecto.

## Capturas de referencia

Las capturas de escritorio y móvil del portafolio publicado se adjuntan en el PDF de documentación. Los proyectos también tienen vistas previas integradas en sus tarjetas.

## Licencia

MIT. Consulta [LICENSE](LICENSE).
