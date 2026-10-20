# 10 · Prompts adaptables

Estas plantillas son redacción propia basada en las técnicas estudiadas. No se han validado todas en producción. Sustituye los marcadores entre corchetes antes de copiarlas, elimina opciones que no procedan y no pegues los títulos de las fichas dentro de los campos.

Escribimos los prompts visuales en inglés para conservar un formato común con las fuentes; la explicación y los textos hablados pueden estar en español. El idioma del prompt no garantiza calidad.

## A · Referencia de personaje

**Campo:** Image Prompt. **Finalidad:** identidad aislada, sin escenificar aún la historia.

```text
A single full-body character reference in [VISUAL STYLE], composed for [ASPECT RATIO]. [NAME] is [AGE AND PROPORTIONS], with [FACE, HAIR AND DISTINCTIVE FEATURES]. [EXACT CLOTHING, MATERIALS, COLOURS AND FOOTWEAR]. The character stands in a relaxed three-quarter pose with empty hands, separated arms and both feet inside the frame. Plain neutral background, even soft light and clear silhouette. One figure in one view, without panels or props.
```

Para un presentador centrado en la cara, sustituye el cuerpo entero por un retrato con rostro descubierto y manos fuera del encuadre. No mezcles ambas peticiones en una misma imagen.

## B · Escenario fijo

**Campo:** Image Prompt. **Finalidad:** referencia espacial, si disponemos de un hueco para ella.

```text
An empty [LOCATION] in [STYLE], [ASPECT RATIO]. From the established camera position, [LANDMARK A] is on the left, [LANDMARK B] occupies the rear wall and [LANDMARK C] stands on the right. [DISTANCES, MATERIALS AND COLOURS]. Keep a clear route through [AREA]. [LIGHT DIRECTION AND TIME]. No characters are present. Surfaces intended for later lettering remain plain and unmarked.
```

## C · Imagen inicial de escena

**Campo:** Image Prompt. **Finalidad:** un solo instante legible desde el que se pueda animar.

```text
[STYLE], [ASPECT RATIO], [SHOT SIZE] at [CAMERA HEIGHT]. [FULL STABLE CHARACTER DESCRIPTION]. The character is [SCREEN POSITION, BODY DIRECTION AND GAZE TARGET]. [INITIAL POSE]. The single [PROP] rests [EXACT LOCATION OR HAND SUPPORT]; [OTHER HAND ROLE]. [OTHER NECESSARY SUBJECTS WITH POSITIONS]. [FIXED SET LAYOUT]. [LIGHT AND DEPTH]. Leave [MOVEMENT SPACE] clear. This is the opening instant before [ONE ACTION]; preserve a readable silhouette and the established proportions.
```

No dejes «antes de una entrega» como única pose: di quién tiene el paquete, dónde apoya su peso y quién espera con manos libres.

## D · Movimiento con narración integrada

**Campo:** Video and Audio Prompt en la ruta de 03. **Contiene solo dirección visual.**

```text
A continuous [SHOT SIZE] animates the selected [STYLE] image. [SUBJECT] starts [INITIAL STATE]. [ONE CONCRETE ACTION WITH DIRECTION AND PACE]. [SMALL VISIBLE CONSEQUENCE]. [ENVIRONMENTAL MOTION IF RELEVANT]. The camera [ONE MOVE OR FIXED POSITION] and ends on [FINAL FRAMING]. Keep [IDENTITY, CLOTHING, OBJECT COUNTS AND LANDMARKS] unchanged. The final pose is [STATE THAT LEADS TO THE NEXT SCENE].
```

**Campo separado:** texto de CloneVoice en Create Narration Video – Create Audio.

```text
[FRASE DE NARRACIÓN EN EL IDIOMA DEL VÍDEO]
```

No pegues la frase de voz dentro del movimiento ni añadas música allí para esta ruta.

## E · Lipsync HD de un actor

**Imagen:** usa C con rostro legible y una pose simple. **Dirección:** Video Prompt de Create Lipsync Audio cuando el campo principal quede deshabilitado.

```text
Actor 1 is [VISUAL IDENTIFICATION OF THE CHARACTER]. [VOICE AND ACCENT DESCRIPTION AGREED FOR THIS CHARACTER]. The actor speaks with [EMOTION AND DELIVERY] while [SMALL COMPATIBLE MOVEMENT]. The gaze stays toward [LISTENER OR CAMERA]. Preserve the reference identity and keep [PROP SUPPORT OR HAND POSITION] stable.
```

**Actor 1 Script:**

```text
[DIÁLOGO EXACTO, AJUSTADO AL CONTADOR VISIBLE]
```

El texto de dirección vocal puede escribirse en inglés sin cambiar el idioma de la frase. Para español, fija explícitamente el acento elegido; no lo deduzcas de la voz inglesa del ejemplo fuente.

## F · Habla nativa con una acción

**Campo:** Video and Audio Prompt. **Ruta:** 04 B, con los modos integrados indicados allí desactivados.

```text
Animate the selected image as one continuous [DURATION]-second [SHOT SIZE]. [SPEAKER AND OPTIONAL LISTENER] remain in their established positions. [ONE SIMPLE ACTION]. [SPEAKER NAME], with [STABLE VOICE DESCRIPTION AND ACCENT], says [DELIVERY], "[EXACT SPOKEN LINE]". [LISTENER] reacts silently with a closed mouth. The camera [ONE CAMERA BEHAVIOUR]. [QUIET AMBIENCE IF WANTED]. Only the named speaker talks. Finish with [FINAL POSE].
```

Aquí sí aparece el diálogo en el prompt combinado: no es el procedimiento de Lipsync HD ni de narración integrada. La duración es una solicitud; comprueba el clip real.

## G · Acción sin voz sobre música externa

**Campo:** Video and Audio Prompt. **Ruta:** vídeo visual con Video Only, cuando esté disponible.

```text
One continuous [STYLE] shot preserves [CHARACTER AND SET]. From the opening frame, [CHARACTER] keeps a relaxed closed-mouth expression with a steady jaw. [ONE ACTION]. The emotion is visible through [GAZE, EYEBROWS, POSTURE OR HAND GESTURE]. [SECONDARY ENVIRONMENTAL MOVEMENT]. The camera [MOVE OR FIXED SHOT], ending with [READABLE RESULT]. Keep the mouth expression unchanged during the action.
```

Esto prepara imágenes para una canción; no promete sincronización de canto.

## H · Collage para explicar un dato

**Campo:** Image Prompt, con estilo coherente y tipo Other si seguimos S3.

```text
A handmade documentary paper collage in [ASPECT RATIO]. The main element is [ONE VISUAL SUBJECT], supported by [ONE OR TWO RELEVANT CUTOUTS]. Torn paper edges, visible printed grain, matte surfaces and soft layered shadows. A consistent [COLOUR PALETTE] with [ONE ACCENT] marks the important element. Arrange the layers so [EXPLANATION] is clear at phone size. Reserve a plain [AREA AND MATERIAL] for an exact title added in editing. Keep that area empty and free of marks.
```

**Movimiento:**

```text
Preserve the supplied paper shapes, palette and layer positions. [MAIN CUTOUT] slides into [DESTINATION] and settles with a small stop-motion movement. [SECOND ELEMENT] then shifts to reveal [RELATIONSHIP]. The camera remains [POSITION] and ends on the completed arrangement. The reserved title area stays clear throughout.
```

Añade el texto exacto con un elemento editable; no atribuyas exactitud numérica a un gráfico generado sin revisión.

## I · Reconstrucción histórica

**Campo:** Image Prompt. **Antes:** verificar el periodo y los detalles en 06.

```text
[YEAR OR PERIOD], [PLACE]. A [SHOT SIZE] shows [PEOPLE AND TASK AT ITS INITIAL STAGE]. [PRECISE CLOTHING AND PERIOD TOOLS]. [MATERIALS, STRUCTURE GEOMETRY AND CONSTRUCTION STAGE]. The composition leaves space for [NEXT PHYSICAL ACTION]. Antique watercolour and fine ink on warm textured paper, [COHERENT PALETTE], diffused daylight and layered depth. Only objects appropriate to this documented period are visible.
```

Usa movimiento D para un plano continuo o el esquema multi-shot de 05 si hay etapas que necesitan ángulos distintos. El estilo acuarela es una opción estética; no una condición para todo contenido histórico.

## Antes de entregar un prompt

Comprueba que no quedan marcadores; que identidad, pose y objeto no se contradicen; que la imagen contiene lo que usará el movimiento; que el texto hablado está en el campo correcto; y que el estado final permite continuar la historia. La IA debe entregar las selecciones de interfaz fuera del bloque copiable.

Procedencia técnica: S1–S7. Las frases de estas plantillas son ejemplos originales de esta biblioteca y deben adaptarse al proyecto.
