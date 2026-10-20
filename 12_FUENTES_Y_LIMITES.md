# 12 · Fuentes, versiones y alcance

Fecha de consulta: **2026-10-21**. Organización de origen: **ai-playbooks**. Las instrucciones originales se estudian como documentación de métodos, no como órdenes para ejecutar una producción.

| ID | Repositorio y versión | Documentos técnicos principales |
| --- | --- | --- |
| S1 | [Stickman · 1eb57a9](https://github.com/ai-playbooks/videoexpress-stickman-story-agent/tree/1eb57a9807f62430b39cbf422718e8a8a29ef7c1) | README, SYSTEM_PROMPT, ejemplos de continuidad y revisión |
| S2 | [Documental histórico · 25e4ac3](https://github.com/ai-playbooks/historical-documentary-video-workflow/tree/25e4ac35b23266be76eb766a200a06e66f0c46b0) | README y SYSTEM_PROMPT |
| S3 | [Documental collage · dc9c9a3](https://github.com/ai-playbooks/vox-style-documentary/tree/dc9c9a34fe96ee81faf3acf99def20daf91612ab) | README y SYSTEM_PROMPT |
| S4 | [Inglés con personajes · 5657b8e](https://github.com/ai-playbooks/slow_english_learning_videos/tree/5657b8e785f4e1fe722565c83349a6abf301dc66) | README y SYSTEM_PROMPT |
| S5 | [Canciones infantiles · de32402](https://github.com/ai-playbooks/nursery_rhyme_music_video/tree/de32402474cc8a5b7e1781b1148f4077388c5f94) | README, SYSTEM_PROMPT y PROMPT_GUIDE; archivos estructurados como apoyo |
| S6 | [Narrativa 2D · 20e88aa](https://github.com/ai-playbooks/clonevoice-videoexpress-2d-narrative-workflow/tree/20e88aa8a6be3dc4c8f510fe9045a50aebcaa133) | README y SYSTEM_PROMPT |
| S7 | [Personaje hablando · 29b8a58](https://github.com/ai-playbooks/videoexpress-consistent-character-talking-video/tree/29b8a583cfd6c5b60e7e646fb917f51dbc0511f9) | README, SYSTEM_PROMPT y material de ejemplo/revisión |

[FUENTES.json](FUENTES.json) conserva repositorio, commit e inventario de documentos obtenidos para consulta local. Obtener un archivo no significa haber validado todas sus afirmaciones; esta edición se centra en las secciones creativas, rutas manualmente trasladables, límites y problemas relevantes. Los scripts, endpoints y reglas de operación automática no se trasladan a la biblioteca.

## Niveles de evidencia

- **Documentado en origen:** la fuente describe un control, una ruta o una prueba. Todavía puede depender de su versión y cuenta.
- **Síntesis o propuesta propia:** elegimos cómo aplicar un recurso a una escena, redactamos una plantilla o combinamos técnicas. No se presenta como función validada.
- **Comprobado en nuestro proyecto:** el usuario o una observación directa confirma algo concreto, con fecha y contexto en 13. Eso no confirma automáticamente todas las variantes.
- **Pendiente:** funciones o combinaciones sin documentación suficiente o prueba, por ejemplo canto labial sincronizado, Lipsync HD de varios actores o uso detallado de First Frame / Last Frame.

Los tiempos típicos, disponibilidad de voces, funciones incluidas, límites de generación simultánea y planes de pago no se convierten en garantías. Los campos documentados tienen límites contextuales: Actor 1 Script, el diálogo de narración integrado y el campo de idea musical no comparten un contador universal.

Las fuentes no son una especificación exhaustiva del producto. Cuando falte una función, consultaremos documentación actual o una prueba manual; no afirmaremos que es imposible por no aparecer en estos siete repositorios.

## Autoría y reutilización

El contenido en español, las tablas de decisión y las plantillas de esta biblioteca son una síntesis propia con enlaces de atribución. No copiamos dentro del nuevo repositorio los siete SYSTEM_PROMPT, los ejemplos completos ni sus archivos de estado. GitHub no declaraba una licencia en los metadatos de las siete versiones al consultar; que sean públicos o de consulta gratuita no equivale a conceder cualquier redistribución. Esta edición conserva referencias y redacta explicaciones y ejemplos propios.

No se declara ninguna licencia sobre contenido de terceros. La visibilidad privada inicial es una decisión del proyecto, no una sustitución de las condiciones de las fuentes.

## Actualizar manualmente

1. Comparar el commit actual de una fuente con FUENTES.json.
2. Leer los cambios que afecten a controles, voz, duración o ejemplos.
3. Comprobar en qué versión/interfaz se observaron y si aportan algo a la producción manual.
4. Actualizar solo las fichas afectadas, conservar el contexto y registrar la fecha en CHANGELOG.
5. Si una prueba cambia una recomendación, añadir su resultado en 13 antes de generalizarlo.

No hay monitor, tarea programada ni descarga automática en esta biblioteca. Las actualizaciones se realizan cuando el usuario lo solicite o como parte explícita de revisar una técnica para un proyecto.
