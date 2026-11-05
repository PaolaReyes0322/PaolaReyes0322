# Documentación del Proyecto 1: Portafolio de identidad digital
**Estudiante:** Paola Isabel Reyes Granados

## Fase 1: Análisis
### 1.1 Perfiles de referencia
Se analizaron cuatro perfiles:
1. Mokkape [https://github.com/Mokkapps/mokkapps]
2. Spiderpig86 [https://github.com/Spiderpig86/Spiderpig86]
3. Raymo111 [https://github.com/Raymo111/Raymo111]
4. alihamzaio [https://github.com/alihamzaio/alihamzaio]

### 1.2 Tabla comparativa de los perfiles
| **Criterio / Perfiles** | **Mokkapps** | **Spiderpig86** | **Raymo111** | **alihamzaio** |
|-------------------------|--------------|-----------------|--------------|----------------|
| **Presentación**| Imagen de cabecera y frase clara: desarrollador senior de Vue.js y Nuxt, freelance. Se entiende de inmediato a qué se dedica. | Saludo con nombre, empleo actual, es decir, ingeniero de software, y ciudad. Tono personal y cercano. | GIF animado de bienvenida con su nombre y listado breve de qué hace y dónde trabaja. Muy llamativo, pero menos directo. | Título con nombre y una frase: desarrollador full stack, años de experiencia, tecnologías y disponibilidad laboral. Muy claro y directo. |
| **Estructura** | Corta: portafolio y dos productos propios, cada uno con su imagen enlazada. Pocas secciones. | Más larga: presentación, datos rápidos, publicaciones recientes, herramientas y estadísticas. | Muy extensa: sobre mí, en qué trabaja, gists, métricas, actividad, contacto y créditos. | Corta y ordenada: presentación, enlaces, qué construye y stack. Jerarquía simple con títulos. |
| **Habilidades** | No hay lista explícita; se deducen del título y de los productos. | Íconos de tecnologías (devicon) con texto alternativo; muestran muchas tecnologías sin explicar nivel. | Se deducen de los proyectos y gists; no hay sección formal. | Lista en texto plano de tecnologías (React, Next.js, Node.js, AWS, etc.). Fácil de leer y copiar, pero sin evidencia. |
| **Proyectos** | Destaca dos productos propios con imagen y enlace al sitio. | Menciona el proyecto actual Cirrus y remite a su GitHub. | Lista de gists y tutoriales enlazados, y enlaces a issues donde necesita ayuda. | Describe tipos de proyectos qué construyo, pero no enlaza a repositorios concretos. |
| **Contacto** | Solo enlace a su sitio web personal. | Insignias a sitio web, Medium, LinkedIn, Dev.to y Spotify. Hay varios canales. | Redes sociales como LinkedIn, Instagram y Twitter mediante íconos. | Portafolio, CV, LinkedIn y correo electrónico visible en el README. |
| **Accesibilidad y móvil** | Imágenes con texto alternativo. Depende de imágenes del propio repositorio. | Depende de muchos servicios externos, tales como insignias, GIF y estadísticas. Si fallan, se pierde contenido. | Usa texto en tipografía Unicode "monoespaciada", que los lectores de pantalla suelen leer mal. Depende de servicios externos. | Muy ligera y legible en móvil. Una sola imagen con texto alternativo. |

### 1.3 Tabla comparativa de los repositorios
| Característica | Mokkapps | Raymo111 |
|----------------|----------|----------|
| Descripción corta | Sí | Sí |
| Topics | Sí, 7. | Sí, 19. |
| Enlace a sitio/demo | No en el "About"; sí en el README (portafolio y productos) | Enlace a su perfil en el "About"; enlaces a gists y proyectos en el README |
| README con propósito claro | Sí, un portafolio, producto propio y boletín | Sí: sobre mí, en qué trabaja, gists, métricas y contacto |
| Licencia | Apache-2.0 | GPL-3.0 |
| `.gitignore` | Sí | No visible |
| Cantidad de commits | 1.692 | 2.405 |
| Issues / Pull Requests | Ninguno abierto | 2 issues abiertos |
| Releases | No visibles | No visibles |
| Estructura de carpetas | Archivos de configuración, imágenes y automatización (`.github/workflows`) | Carpetas `.github` y `socials`; imágenes y script |

### 1.4 Requisitos de mi perfil
#### Requisitos funcionales 
- **RF1.** Una presentación breve que incluye nombre y el tipo de desarrollo que me interesa.
- **RF2.** Información académica y profesional relevante, organizada de forma clara.
- **RF3.** Una sección de tecnologías y herramientas aprendidas en el curso, explicando cómo las apliqué.
- **RF4.** Una sección de proyectos destacados, cada uno con descripción, tecnologías y enlace funcional al repositorio.
- **RF5.** Al menos un canal de contacto profesional.
- **RF6.** El perfil debe estar visible en mi cuenta: repositorio público y con `README.md`.
- **RF7.** Un sitio publicado con GitHub Pages y accesible mediante un enlace.

#### Requisitos no funcionales
- **RNF1. Legibilidad:** títulos claros, listas cortas, párrafos breves y buena jerarquía.
- **RNF2. Accesibilidad:** texto alternativo en todas las imágenes, buen contraste y no depender solo de imágenes para transmitir información.
- **RNF3. Lectura en móvil:** evitar tablas muy anchas y exceso de insignias o imágenes externas.
- **RNF4. Mantenibilidad:** contenido sencillo de actualizar, solo con Markdown.
- **RNF5. Privacidad:** no publicar teléfono, dirección, cédula ni otros datos sensibles.
- **RNF6. Trazabilidad:** commits pequeños con mensajes descriptivos, para que el historial muestre cómo se construyó el perfil.
