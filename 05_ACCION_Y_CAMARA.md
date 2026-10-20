# 5 · Acción, imagen inicial y cámara

## Diseña una acción que se pueda leer

La imagen inicial muestra el punto desde el que arranca el movimiento. Para abrir una caja, la caja debe estar cerrada y al alcance; para entregarla, el objeto y el destinatario deben estar en posiciones compatibles. No pidas que el vídeo invente la pieza que falta en la imagen.

El prompt de imagen describe **un instante**, no una lista de acciones. El prompt de movimiento describe el cambio. Si la imagen ya presenta el resultado final, ajusta la pose inicial.

Una acción principal por clip suele ser una base manejable: mirar, acercarse, tomar, entregar o reaccionar. Para movimientos complejos, separa preparación, contacto y resultado en escenas. Deja una ruta de paso y un punto de parada; una puerta cerrada no es una ruta libre.

## Plano continuo

Útil para diálogo, pequeñas acciones y contactos delicados. Describe la composición inicial, la acción, el movimiento secundario del entorno y un único comportamiento de cámara. Termina con el estado que necesita la siguiente escena.

Ejemplo propio, visual y sin instrucciones de audio:

```text
A continuous medium shot preserves the accepted 2D café scene. Clara starts behind the counter with one closed paper bag supported by both hands. She slowly slides the bag toward Leo, who waits on the opposite side with empty hands. Clara releases it only after it rests flat on the counter. The camera stays at counter height on the established side of the scene and finishes with the bag between them. The window, door and coffee machine keep their positions.
```

Si usamos narración integrada, solo este movimiento va al campo visual. La frase de narración se entrega aparte.

## Varios planos dentro de un clip

S2 y S3 documentan prompts con secciones temporales y cortes entre ángulos para procesos o collage. Son una opción para enseñar etapas de un trabajo. No garantizan que el modelo respete cada segundo o corte exactamente.

Diseña dos o tres planos conectados cuando la duración deje leerlos. Cada plano tiene un ángulo y un acontecimiento. Conserva personajes, ropa, objetos y estado material entre cortes. No mezcles «single continuous shot» con «hard cut» en el mismo clip.

Esquema propio para una toma visual de diez segundos:

```text
Total duration: 10 seconds. Preserve the supplied painted workshop, the two workers and the same timber joint.

SHOT 1, 0–3 seconds: Medium side view. One worker steadies the plank while the other aligns a single wooden peg with the visible hole.
SHOT 2, 3–7 seconds: Hard cut to a close view of that same joint. The second worker drives the peg with two measured mallet strokes; the first worker keeps the plank steady.
SHOT 3, 7–10 seconds: Hard cut to a wider view. Both release the completed joint and inspect its alignment. The materials, tool positions and painted texture remain consistent.
```

En la ficha de escena añadiremos por separado si este material lleva ambiente, audio nativo o Video Only con voz/música en otra pista. No lleves este formato con tiempos a la ruta de narración integrada como solución garantizada de duración.

## Cámara según la intención

| Decisión | Cuándo ayuda | Qué cuidar |
| --- | --- | --- |
| Cámara fija | Entrega de objetos, precisión de manos, calma o tensión | La acción debe aportar el cambio |
| Seguimiento lateral suave | Caminar o desplazarse | Mantener dirección y distancia entre sujetos |
| Acercamiento suave | Descubrimiento o detalle importante | Indicar encuadre final; conservar lo que importa visible |
| Plano general | Lugar, distancia, escala y relaciones | Rostros y objetos no pueden quedar ilegibles en móvil |
| Plano de detalle | Objeto, dato, contacto, decisión | Prepararlo en la imagen; evitar manos cruzadas complejas |
| Contraplano | Respuesta de otro personaje | Mantener miradas y lado del eje |

No fuerces una cámara móvil en todas las escenas. El movimiento de cámara tampoco sustituye a una acción que el guion afirma que ocurre.

## Enlaces y fotogramas inicial/final

Esta edición documenta principalmente generación desde una imagen seleccionada. Los siete repositorios no constituyen una guía completa y validada de todos los controles de First Frame / Last Frame. Si queremos esa función específica, consultaremos su documentación y la interfaz antes de dar pasos concretos.

Para continuidad ordinaria, conserva referencias originales y el estado de salida. Inspecciona tú el final del clip cuando un contacto o un enlace sea importante. Recrear la siguiente imagen a partir del plan puede dar libertad; usar un fotograma real puede mejorar un enlace concreto, pero también arrastrar defectos de identidad.

Procedencia: S1 §§2–6, S2 planificación y multi-shot, S3 §§4–6, S4 §§3–4 y S6 §11. Ejemplos y tabla de dirección: síntesis propia.
