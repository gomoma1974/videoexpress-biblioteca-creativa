# 2 · Personajes, referencias y continuidad

## Qué aporta Consistent Character

Las fuentes usan imágenes de referencia para conservar la identidad entre escenas. Aun con una referencia, conviene repetir la descripción estable del personaje y la ropa. La selección no garantiza continuidad perfecta ni obliga a repetir la pose del retrato.

Prepara una ficha por personaje: nombre, edad aparente, proporciones, rasgos de cara, pelo, prendas y colores, accesorios, personalidad y descripción visual reutilizable. Evita expresiones como «el mismo de antes» como única descripción. Describe diferencias claras entre personajes: silueta y prendas, además de colores.

## Crear manualmente la referencia

1. Abre Create with AI → Create Video From Prompt y fija formato y Image Type.
2. Introduce un prompt de personaje aislado, fondo simple e iluminación uniforme. Si necesitamos revisar ropa y proporciones, usa cuerpo entero; para rostro de presentador, un retrato limpio puede bastar.
3. Desactiva la mejora automática del prompt cuando esté disponible, para conservar las decisiones precisas.
4. Genera y revisa cara, anatomía visible, ropa y silueta. Guarda la opción elegida con Save Image en My AI Images.
5. Activa Use Consistent Character y selecciona esa imagen en Reference Photo. Comprueba la miniatura.
6. Escribe un prompt nuevo para la escena, con la identidad estable y la pose que esa escena necesita. Selecciona explícitamente el resultado que vas a animar.

**Referencia de identidad ≠ imagen inicial del clip.** Use from Library puede seleccionar la imagen que se animará; Reference Photo sirve para condicionar identidad al crear la escena. Confundirlos puede producir un retrato animado cuando querías una acción.

## Elegir qué ocupa la segunda referencia

Reference Photo 2 tiene usos distintos según la fuente: S1 propone un escenario vacío fijo; S4 y S6 lo usan para un segundo personaje recurrente. Decide cuál necesita más apoyo visual. No prometas que dos huecos bastan para dos personajes y un escenario simultáneamente. Si falta una referencia, simplifica el plano y describe el escenario con precisión; una capacidad adicional debe comprobarse en la interfaz actual.

S2 usa una hoja de personaje con varias vistas para el presentador. S4 prefiere una sola figura para evitar que el modelo copie varias. Son alternativas contextuales: empezaremos con una sola figura limpia y usaremos una hoja multivista cuando una prueba la justifique.

## Escenarios que se repiten

Escribe un plano verbal del lugar: puerta a la izquierda, ventana al fondo a la izquierda, mostrador a la derecha y zona de paso central. Mantén posiciones, proporciones, materiales y lado de cámara entre tomas. Una referencia de escenario debe estar libre del protagonista si su función es fijar el espacio.

La cámara puede acercarse y ocultar parte del decorado; eso no justifica mover la puerta de lado. Un cambio real de lugar necesita una transición.

## Continuidad de acción

Para cada escena registra:

| Estado al entrar | Acción nueva | Estado al salir | Qué conserva la siguiente |
| --- | --- | --- | --- |
| Clara tiene un paquete apoyado en el mostrador | Lo desliza hacia Leo | El paquete queda frente a Leo; Clara retira las manos | El paquete permanece allí antes de recogerlo |

Lleva el control de manos ocupadas, contacto, mirada, lado de pantalla, número de objetos y dirección de desplazamiento. No repitas en cada clip el acercamiento y la entrega. Una imagen inicial bonita puede mostrar ya la acción terminada y dejar al movimiento sin nada que hacer.

Usar siempre el último fotograma de cada vídeo puede acumular cambios de cara y ropa. S1 conserva la referencia original y recrea la siguiente imagen según el estado de continuidad. Extraer un fotograma final es una opción a probar para un enlace concreto, no el método predeterminado de esta edición.

## Antes de animar

Comprueba tú la imagen ampliada: identidad, boca y ojos, número de personas, manos conectadas a sus brazos, objeto sostenido con peso plausible y todos los elementos necesarios ya presentes. Si una pose no es posible en la imagen, la animación puede agravar el problema. Simplifica el agarre o divide la interacción.

Procedencia: S1 §§2–5, S2 introducción, S4 §§3–4, S6 §§9–11 y S7 pasos 1–4. Las reglas de dos personajes de S4 reducen fallos en su receta; no establecen un máximo universal de VideoExpress.
