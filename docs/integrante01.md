PASOS A REALIZAR POR EL INTEGRANTE 1
(Trabaja exclusivamente en la rama dev/integrante-1)

Paso 1: Setup Inicial, SEO y CDNs
• Crear el archivo index.html con la estructura HTML5 básica.
• Configurar el atributo lang="es" y el meta tag viewport para responsividad.
• Agregar las meta etiquetas SEO: description, keywords, author y robots.
• Integrar los CDN oficiales en el <head>: Bootstrap 5.3.3 (CSS y JS) y
Tailwind CSS (Play CDN para desarrollo). Nota: No usar @import en CSS
local.
• Hacer el primer commit: feat: setup inicial y configuración SEO.
Paso 2: Navbar Responsivo (Componentes + Utilidades)
• Implementar la barra de navegación usando componentes
preensamblados de Bootstrap (navbar-expand-lg, collapse, toggler).
• Incluir un menú desplegable (dropdown) y badges de notificación.
• Toque Tailwind: Mejorar la navbar usando utilidades de Tailwind para
sombras (shadow-lg), espaciado (py-3) y desenfoque de fondo (backdropblur).
• Validar que el botón "hamburguesa" funcione en móviles sin escribir
JavaScript adicional (aprovechando el JS de Bootstrap).
• Commit: feat: navbar responsivo híbrido.
Paso 3: Hero Section (Tipografía Fluida y Composición)
• Maquetar la sección principal (Hero) con un título llamativo, descripción y
botones de acción (Call to Action).
• Bootstrap: Usar clases de tipografía fluida (display-3, lead) y layout (d-flex,
gap-3).
• Tailwind: Aplicar text-balance para mejor lectura, max-w-3xl para limitar el
ancho del texto, y bg-gradient-to-r para el fondo.
• Nota: Documentar en el README si hubo conflictos de especificidad entre
ambos frameworks y cómo se resolvieron.
• Commit: feat: hero section con tipografía adaptativa.
• Acción final: Crear un Pull Request a main y notificar al Integrante 2 para
que revise.