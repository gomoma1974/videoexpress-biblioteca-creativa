# 17 · Preparar vídeos con Codex y VideoExpress

Esta ficha adapta a una colaboración creativa manual varias ideas de la skill [videoexpress-scripting](https://github.com/ratava/videoexpress-scripting-skill), versión 2.6.0. Sirve para planificar, escribir y revisar; no autoriza a Codex a manejar tu cuenta ni a generar o publicar medios. Tú controlas VideoExpress y decides qué producir.

## Qué añade a la biblioteca

La aportación principal es un flujo más explícito para pasar de una idea a un paquete de producción: concepto, continuidad, tabla de clips, prompts por clip y revisión iterativa. Encaja con el mapa de decisiones, las fichas de continuidad y las plantillas de trabajo existentes; no sustituye las rutas de narración, diálogo, Artistly o CloneVoice documentadas en [07](07_MUSICA_Y_ESCENAS_SIN_DIALOGO.md).

## Flujo recomendado

1. **Definir el encargo:** objetivo, audiencia, plataforma, formato, duración, tono, llamada a la acción y materiales disponibles.
2. **Elegir la historia:** acordar una idea y su arco antes de escribir prompts. Para un anuncio breve puede ser problema, solución, beneficio y cierre; para ficción, gancho, escalada, giro y remate.
3. **Preparar una biblia breve:** descripción estable de personajes, vestuario, objetos importantes, lugar, época, estilo visual y elementos que deben permanecer iguales. Reutilizar el mismo texto de identidad en los clips relacionados.
4. **Planificar los clips:** una tabla con número, duración objetivo, función narrativa, imagen inicial, acción principal, encuadre/cámara, sonido o voz, continuidad y último estado visual.
5. **Escribir y generar manualmente:** cada prompt debe poder entenderse por sí solo. Comprueba que empieza desde la imagen realmente seleccionada y no depende de que el modelo recuerde un clip anterior.
6. **Revisar el resultado y ajustar:** describe el fallo visible, cambia una causa por intento y aplica la corrección a los clips futuros que compartan ese problema. Anota qué funcionó antes de convertirlo en una regla general.

## Cómo redactar cada prompt

- Empieza por el sujeto y una acción sencilla que se entienda en el clip. Limita la escena a un momento principal.
- Describe qué debe permanecer estable y qué cambia. Mantén explícitos identidad, ropa, objeto, lugar, luz y estilo cuando importen.
- Indica el movimiento de cámara con claridad, incluido su destino. Usa cámara fija si no hace falta moverla; no añadas movimientos solo por espectacularidad.
- Sitúa el comienzo de la acción en el fotograma inicial que vas a usar. El clip debe funcionar aunque el generador no haya visto los anteriores.
- Separa instrucciones visuales, acción, cámara y sonido en bloques o campos claros si la interfaz ofrece esos campos. Los nombres exactos dependen de la versión de la interfaz.
- Para rótulos, nombres de marca y texto exacto, reserva el espacio visual y añade el texto en edición. No confíes en que el generador escriba correctamente un logo o una frase.
- Coloca las exclusiones en un bloque de negativos separado cuando el flujo usado lo permita. Evita enumerar dentro del prompt principal elementos indeseados que puedan distraer al modelo.

## Continuidad y ritmo

Las referencias visuales ayudan a mantener identidad, pero cada clip necesita instrucciones suficientes para su propio plano. Al encadenar clips, planifica el estado final de uno y el estado inicial del siguiente: postura, mirada, posición, objeto y dirección de movimiento. Una imagen final compatible puede ser un puente más fiable que una instrucción del tipo «continúa lo anterior».

Elige dos o cuatro motivos visuales recurrentes si ayudan a reconocer la historia o la marca. Reserva los cambios de plano para información nueva, énfasis o una transición narrativa. Mantén el estilo visual coherente dentro de una misma secuencia y vuelve a anclarlo en los clips donde sea importante.

## Sonido y voz

Decide primero si la escena llevará narración, personaje hablando, habla nativa generada con el prompt, música o solo efectos. No pidas varias rutas de voz a la vez sin una razón clara. Relaciona los efectos con acciones visibles y evita instrucciones vagas como «sonido cinematográfico». Si usas audio preparado por separado, comprueba que los tiempos y las pausas coincidan con los clips.

Artistly y CloneVoice son rutas opcionales cuando están disponibles en tu cuenta y son adecuadas para la tarea. Sus pasos prácticos siguen en la ficha [07](07_MUSICA_Y_ESCENAS_SIN_DIALOGO.md); la skill de origen no demuestra por sí misma que estén habilitados en cada cuenta.

## Revisión por clip

Al ver cada resultado, comprueba:

- identidad, cara, pelo, vestuario y objetos importantes;
- si la acción comienza a tiempo, es legible y termina en un estado aprovechable;
- manos, agarres, movimiento corporal y relación con el espacio;
- encuadre, cámara, luz y consistencia de estilo;
- texto accidental, deformaciones y elementos que distraen;
- sonido, voz, sincronía y pausas cuando correspondan;
- si el fotograma final sirve para el siguiente clip o para el montaje.

Describe el problema concreto («el teléfono cambia de mano al girar») y modifica una variable por prueba. Si persiste, simplifica la acción o cambia la imagen de referencia. Un resultado aislado no basta para declarar una regla universal.

## Funciones mencionadas por la versión de origen

La versión 2.6.0 de la skill también menciona estilos adicionales, Voice Changer, Screen Recorder y filtros de la línea de tiempo, además de Artistly y CloneVoice. Esta biblioteca **no confirma** que todas esas opciones sigan disponibles o tengan los mismos nombres en tu cuenta. Antes de incluirlas en un flujo, comprueba la interfaz y registra una prueba manual en [13](13_APRENDIZAJES_Y_PREFERENCIAS.md).

## Procedencia y límites

Esta guía es una síntesis original en español de métodos creativos y de prompting de la skill [videoexpress-scripting-skill](https://github.com/ratava/videoexpress-scripting-skill), tag **v2.6.0**, consultada el **31 de octubre de 2026**. No reproduce la skill, sus prompts completos, archivos de automatización ni instrucciones para controlar el navegador. La descripción del repositorio declara CC BY-NC 4.0, mientras que los metadatos de licencia de GitHub indican NOASSERTION; por eso esta biblioteca conserva atribución y redacta una síntesis propia, sin redistribuir sus archivos.

Los campos, estilos y controles pueden cambiar según la versión de VideoExpress y la cuenta. Separa lo documentado por la fuente, lo propuesto por esta biblioteca y lo probado manualmente en tu proyecto.
