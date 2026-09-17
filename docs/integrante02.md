PASOS A REALIZAR POR EL INTEGRANTE 2
(Trabaja exclusivamente en la rama dev/integrante-2, partiendo de un pull de la
rama main)

Paso 4: Grid de Tarjetas (Sistema de 12 Columnas + Estados)
• Crear una sección para mostrar características, productos o servicios del
tema libre elegido.
• Bootstrap: Usar el sistema de grillas de 12 columnas (container, row, colmd-4) para estructurar 3 tarjetas.
• Tailwind: Estilizar las tarjetas usando rounded-xl para bordes, shadow-lg
para profundidad, y hover:scale-105 con transition-transform para el efecto
interactivo.
• Restricción: No usar consultas de medios (@media) manuales; confiar en
los breakpoints nativos de ambos frameworks.
• Commit: feat: grid de tarjetas con transiciones.

Paso 5: Formulario con Validación UI y Accesibilidad
• Implementar un formulario de contacto, registro o reserva (según el tema
libre).
• Usar los estados de formulario de Bootstrap (form-control, is-invalid, validfeedback) para la validación visual.
• Integrar la clase peer de Tailwind si se requiere validación avanzada solo
con CSS.
• Accesibilidad: Asegurar que el contraste de colores sea ≥4.5:1, que cada
input tenga su label vinculado correctamente mediante for/id, y usar ariadescribedby para los mensajes de error.
• Commit: feat: formulario accesible con validación UI.

Paso 6: Auditoría de Rendimiento y Accesibilidad
• Ejecutar Lighthouse (en Chrome DevTools) y auditar: Performance,
Accessibility, Best Practices y SEO. Corregir los errores críticos.
• Pasar la extensión WAVE para verificar que no queden errores de
accesibilidad.
• Commit: chore: auditoría Lighthouse y WAVE.
• Acción final: Crear un Pull Request a main y notificar al Integrante 1