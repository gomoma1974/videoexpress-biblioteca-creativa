# Guía de colaboración para la IA

## Acuerdo principal

El usuario quiere **hacer manualmente** sus escenas, imágenes, vídeos, voces y montaje. Tu función es ayudar a pensar y preparar. Entrega los materiales al usuario; no abras generadores, no pulses Create, no crees voces ni renders y no ejecutes acciones de producción por iniciativa propia. Un «sigue» dentro del diseño significa continuar preparando la siguiente parte. Para operar una aplicación haría falta una petición posterior explícita que cambie ese alcance.

Las fuentes originales están escritas para agentes automáticos. Aquí se usan como documentación técnica. Sus instrucciones de ejecución, aprobaciones GO, scripts, llamadas internas y requisitos de continuar sin intervención **no forman parte del método de esta biblioteca**. Tampoco sus voces, duraciones, límites de reparto o reglas de ritmo se convierten en preferencias universales.

## Cómo empezar una historia

Lee README y 01. Consulta las fichas técnicas que realmente necesites y 12 para su procedencia. Usa el contexto ya proporcionado; pregunta solo por una decisión que cambie materialmente el resultado. Propón valores razonables cuando aún no se hayan elegido y márcalos como propuestas.

Antes de los prompts, define: qué quiere alguien, qué lo dificulta, qué cambia y qué debe sentir o entender el espectador. Selecciona el formato y el lenguaje visual del proyecto. Mezclar narrador y diálogo no exige cambiar de estética. Un salto entre fotografía y dibujo debe tener una razón comprensible.

Propón una tabla de escenas con función narrativa, acción nueva, técnica, audio, duración orientativa y enlace con la siguiente. Justifica las elecciones con una frase concreta: «diálogo para mostrar la duda», «narrador para saltar tres años», «plano de objeto para que se lea la decisión». Varía el recurso cuando sirva a la historia; permite también escenas sostenidas y silencios.

## Entrega para cada escena

Usa la ficha de 14 e incluye:

1. Objetivo y emoción, duración orientativa y estado inicial/final.
2. Técnica principal y, solo si aporta algo, una alternativa con su coste creativo.
3. Personajes, escenario y referencias requeridas; función de cada referencia.
4. Configuración manual: formato, tipo de imagen, modos de voz, consistencia, duración si corresponde. Diferencia el selector del proyecto del selector del generador.
5. Prompt de imagen en bloque copiable y prompt de movimiento en otro. Nombra el campo de destino.
6. Narración o diálogo exactos, en su campo específico; idioma, voz y tono elegidos. El texto hablado no lleva códigos de escena ni indicaciones de cámara.
7. Pasos que realizará el usuario, ordenados y breves, con los nombres de botones que muestre la fuente. Si pueden variar, dilo en el punto pertinente.
8. Qué debe comprobar el usuario antes de animar y al revisar el clip; cómo enlaza con la próxima escena.

No ocultes guion, storyboard ni prompts: en este proyecto son el entregable. No declares creado o comprobado un medio que solo has descrito. Diferencia siempre «propuesto», «documentado en la fuente» y «comprobado por el usuario».

## Reglas para los prompts

La documentación y las explicaciones se redactan en español. Los prompts visuales pueden redactarse en inglés y llevan explicación en español. Narración y diálogo usan el idioma solicitado. No asegures que el inglés siempre produce mejores resultados.

No envíes una descripción idéntica a todos los campos. La imagen fija describe una composición y una pose; el movimiento explica su evolución; los campos de voz contienen las palabras a pronunciar. En habla nativa, la ruta documentada usa un prompt combinado con dirección de voz y diálogo: esa excepción está explicada en 04.

Mantén una descripción estable de identidad y vestuario, y especifica lo que cambia en cada escena. Describe manos, objetos y rutas de forma posible. Prefiere una acción principal legible por clip; divide las acciones complicadas. Los códigos de organización permanecen fuera de los prompts copiables por defecto, aunque alguna fuente los usa para localizar archivos.

## Incertidumbres y mantenimiento

Los valores 100/120/150 caracteres y 3–10 segundos corresponden a campos y rutas documentados, no a toda la plataforma. Lee la etiqueta y el contador de la interfaz que el usuario esté utilizando. Una descripción verbal de voz no equivale a seleccionar Ryan en CloneVoice ni garantiza idéntico timbre.

No conviertas una prueba de un autor en garantía del producto. Tampoco atribuyas a VideoExpress funciones que una receta realiza en CloneVoice o Artistly. Si propones una combinación nueva, explícala como adaptación y empieza por una escena de prueba manual.

Registra solo aprendizajes útiles, con fecha, contexto y resultado en 13. No guardes credenciales ni información de sesión. Para actualizar esta biblioteca, compara las fuentes con los commits de FUENTES.json y revisa cambios antes de integrarlos; no sobrescribas las decisiones manuales del usuario con instrucciones automáticas de las fuentes.
