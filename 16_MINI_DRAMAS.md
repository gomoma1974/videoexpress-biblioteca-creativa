# 16 · Mini dramas para producción manual

Esta ficha adapta [S8 · Realistic Mini Dramas](12_FUENTES_Y_LIMITES.md) a nuestro método: la IA prepara historia, planos, prompts y pasos; **el usuario crea y monta** en VideoExpress. La fuente describe un flujo automático. Sus órdenes de operar el navegador o producir sin mostrar el storyboard no forman parte de esta biblioteca. Los ejemplos y plantillas de esta ficha son redacción propia.

## Cuándo elegirlo

Úsalo si una idea cabe en un conflicto concreto que cambia de sentido antes del final: una decisión difícil, una confusión, una traición, un descubrimiento o un pequeño misterio. Puede funcionar en ficción y en publicidad narrativa. El estilo puede ser fotorealista, 3D o 2D; «mini drama» describe la construcción de la historia, no la apariencia.

No aceleres por sistema una revelación emotiva o una explicación compleja. Conserva el silencio que ayuda a entender una mirada o una decisión. Si el objetivo es explicar un dato, consulta también [06](06_DOCUMENTAL_E_HISTORIA.md); si la voz guía varias escenas, [03](03_NARRACION_INTEGRADA.md) o [06](06_DOCUMENTAL_E_HISTORIA.md).

## Diseñar la historia antes de los prompts

1. **Gancho:** abre cuando el conflicto ya está ocurriendo. El primer plano muestra una acción, una frase o un objeto que obliga a preguntar qué pasa.
2. **Escalada:** cada plano cambia algo verificable: aparece una prueba, se pierde una opción, cambia una alianza o se acerca una consecuencia.
3. **Giro:** un hecho reinterpreta lo visto. S8 lo sitúa cerca del 70 % de la duración como pauta de ritmo, no como segundo obligatorio.
4. **Cierre:** resuelve la pregunta central o termina en una nueva pregunta deliberada. Evita alargar la acción una vez logrado el efecto.

Prepara una tabla con **función, imagen inicial, una acción, voz o silencio, estado final y enlace** por plano. La fuente propone aproximadamente un plano por tres segundos y un tercio de planos sin diálogo. Adapta ese reparto a la comprensión, al idioma y a la duración real de las frases. No generes quince escenas solo porque el objetivo sea 45 segundos.

## Personajes y continuidad

Escribe una ficha breve y estable por personaje: nombre, edad aparente, cara, pelo, piel, ropa, rasgo reconocible y, si habla, carácter de la voz. Crea una imagen maestra en el estilo elegido y úsala como referencia en las escenas correspondientes, siguiendo [02](02_PERSONAJES_Y_CONTINUIDAD.md). Repite los rasgos estables en el prompt de la escena. S8 usa **+ Consistent Character** para guardar la referencia y **Use Consistent Character / Use from Library** al preparar cada plano; comprueba cómo aparecen esos controles en tu cuenta y qué imagen queda seleccionada para animar.

Los personajes pueden cambiar de pose y emoción. Lleva un registro aparte de quién tiene cada objeto, posición en pantalla, dirección de mirada, lado de cámara y estado al terminar. No confíes solo en repetir un retrato para mantener una secuencia de acciones.

## Elegir imagen, acción y voz por plano

| Decisión | Opción de S8 | Cómo aplicarla |
| --- | --- | --- |
| Imagen inicial | Personaje ya cerca del comienzo de la acción | Mostrar una pose que permita el movimiento siguiente; evitar una imagen que ya contiene el resultado |
| Acción | Una acción principal, iniciada enseguida | Especificar qué cambia y dónde termina; una reacción puede ser la acción principal |
| Encuadre | Alternar detalle, primer plano, medio y general | Variar con intención; mantener legibles rostro, manos y objeto en el formato elegido |
| Diálogo | Un hablante por plano; los demás callan | Buena base para turnos breves; escribir nombre, frase exacta, tono y reacción muda del oyente |
| Plano sin diálogo | Acción y ambiente | Dejar que el gesto revele información; decidir música en el montaje si aporta |

S8 usa **habla nativa en Video and Audio Prompt** para sus personajes: desactiva Lipsync HD Video y Narration Video, mantiene Video Only apagado y escribe el diálogo entre comillas en el prompt combinado. Esa ruta es distinta del diálogo en **Actor 1 Script** de Lipsync HD y de la narración creada en CloneVoice; consulta [04](04_DIALOGO_Y_SINCRONIZACION_LABIAL.md). Una descripción repetida de voz ayuda, pero no garantiza el mismo timbre entre clips. Si necesitas una voz específica de CloneVoice, elige otra ruta de audio en vez de asumir que S8 la ofrece.

La fuente limita sus frases a ocho palabras y pide que empiecen de inmediato. En español, la velocidad y claridad pueden variar: escribe una frase que quepa en el clip, pronúnciala a velocidad natural y revisa el audio generado. Un límite de palabras de la receta no es el contador de un campo de VideoExpress.

## Ajustes manuales de la receta S8

S8 observó estos controles en VideoExpress el **23 de octubre de 2026**. Son una configuración concreta para probar, no una obligación ni una garantía de resultados:

| Campo | Realista | 3D | 2D |
| --- | --- | --- | --- |
| Image Type | Photorealistic (Cinematic) | 3D | 2D |
| Use Creative mode | Apagado | Encendido | Encendido |
| Formato de su receta | Vertical 9:16 | Vertical 9:16 | Vertical 9:16 |

Para los tres estilos, S8 desactiva la mejora automática de imagen y vídeo, activa Advanced Mode y Manual Video Length, y deja Video Only apagado cuando el sonido nace en el clip. Solicita **4 segundos** para acción sin diálogo o **5 segundos** para diálogo y después recorta el resultado. Al activar Manual Video Length, la fuente observó que el deslizador volvía a 10: verifica el valor después de activarlo. También indica desmarcar **Share this in the public gallery** para cada plano si no quieres publicarlo allí. Comprueba el estado visible de cada control antes de generar.

El estilo y el formato se eligen para el proyecto concreto. Puedes usar esta estructura narrativa con otra relación de aspecto y otra ruta de voz; en ese caso estaremos **adaptando** S8 y conviene probar primero una escena.

## Plantilla original para un plano con habla nativa

Prepara estos dos campos por separado. Sustituye todos los marcadores y deja fuera de los bloques las instrucciones de interfaz.

**Image Prompt — instante inicial:**

```text
[STYLE AND ASPECT RATIO]. [SHOT SIZE] of [STABLE CHARACTER DESCRIPTION] at [PLACE AND TIME]. [EXACT STARTING POSE], [SCREEN POSITION], looking toward [TARGET]. [ONE IMPORTANT PROP] is [POSITION AND OWNER]. [LIGHT AND FIXED BACKGROUND LANDMARKS]. The composition leaves space for [ONE IMMEDIATE ACTION].
```

**Video and Audio Prompt — movimiento, voz y sonido:**

```text
The selected image begins moving immediately. [CAMERA BEHAVIOUR]. [CHARACTER] [ONE CLEAR ACTION], ending with [VISIBLE CONSEQUENCE]. [IF THERE IS DIALOGUE: NAME, with a consistent [VOICE/ACCENT] and [DELIVERY], says "[EXACT LINE IN THE VIDEO LANGUAGE]". Only [NAME] speaks; [OTHER CHARACTER] reacts without speaking.] Sound: [RELEVANT AMBIENCE OR EFFECT]. Keep character identity, wardrobe, prop count and background positions stable. End when [ACTION OR REACTION] is complete.
```

Si necesitas localizar muchos clips por nombre, S8 empieza el prompt de vídeo con `S01`, `S02`… porque el título en **My AI Videos** toma el inicio del texto. Úsalo solo si compruebas que te ayuda a identificar tus renders y que no interfiere en la generación; nuestra ficha habitual lleva el código fuera del prompt copiable. Para una escena sin voz, elimina toda la cláusula de diálogo. Revisa que el resultado no invente palabras.

## Montaje de ritmo rápido

1. Busca los renders en **Media Library → My Media → My AI Videos** e identifícalos por plano, no por orden de renderizado.
2. Colócalos en orden y comprueba el inicio y final reales de cada uno.
3. Recorta antes de la primera acción o palabra y después de la última acción o palabra. Conserva las sílabas completas y una reacción que aporte sentido.
4. Si el montaje es de clips consecutivos, usa **Auto Align Clips** para cerrar huecos tras los recortes y vuelve a comprobar el orden. Si hay una locución o música sincronizada en otra pista, ajusta los cortes según ese audio y no apliques la alineación de forma ciega.
5. Reproduce la secuencia completa: continuidad de objetos, palabras terminadas, ausencia de fotogramas negros y duración final. Guarda el proyecto y verifica cualquier exportación terminada en **My Videos**.

S8 detalla el corte con **Cut**, borrado por menú contextual y recorte arrastrando bordes. Su equivalencia de 40 píxeles por segundo corresponde a un zoom concreto de la interfaz que observó; mide la regla actual o trabaja escuchando y viendo el material. Sus recortes fijos de emergencia pueden cortar palabras o suprimir una pausa valiosa, así que no sustituyen la revisión manual. Consulta [08](08_MONTAJE_Y_EXPORTACION_MANUALES.md).

## Procedencia y límites

Fuente: [S8, commit 51f18c8](https://github.com/ai-playbooks/realistic-mini-dramas/tree/51f18c8b96622da5c1eeb3882a24dade5d1e529c), principalmente PLAYBOOK.md, las referencias de ritmo e interfaz y los tres ejemplos del directorio `examples/`. Esta ficha resume recursos creativos y controles de su receta. No reproduce sus prompts completos ni afirma que hayamos probado esos ajustes en nuestra cuenta. Los límites de número de personajes, duración, ritmo, ausencia de música y estilo son decisiones de esa producción, no propiedades universales de VideoExpress.
