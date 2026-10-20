# 4 · Personajes hablando: dos rutas distintas

Las fuentes documentan **Lipsync HD con texto de actor separado** y **habla nativa dirigida en el prompt combinado**. Son alternativas. No copies los controles de una dentro de la otra.

## A · Lipsync HD

Útil para un personaje cuya interpretación facial y frase sean el centro del plano. S7 se centra en una persona; un diálogo de dos personajes puede montarse alternando planos individuales, con referencia propia para cada actor. La combinación de esas tomas es nuestra propuesta de dirección.

### Preparación y pasos manuales

1. Crea una referencia del personaje y guárdala en My AI Images. Activa Use Consistent Character y selecciónala.
2. Prepara la imagen de la escena con rostro legible, boca visible, una postura estable y un gesto compatible con los objetos que sostenga.
3. Si necesitas controlar duración y el modo la oculta, S7 indica configurarla antes de activar Lipsync HD mediante Advanced Mode → Manual Video Length. Sus ocho segundos son una elección de esa receta, no una duración obligatoria ni garantizada.
4. Activa Lipsync HD. Comprueba el formato y el modo de imagen. Selecciona y guarda la imagen que quieres animar.
5. Usa el control de creación para abrir Create Lipsync Audio.
6. En Video Prompt de ese diálogo escribe quién es Actor 1, dirección de movimiento, emoción y descripción estable de voz/acento. Si Video and Audio Prompt queda deshabilitado, no intentes poner allí el diálogo.
7. En **Actor 1 Script** introduce únicamente las palabras que dirá el personaje. S7 documenta un rechazo sobre 100 caracteres y recomienda menos de 100 contando espacios y puntuación; el contador de tu interfaz manda.
8. Genera manualmente y revisa vídeo con sonido: frase correcta, identidad, labios, manos y palabras finales completas.

Ejemplo propio de dirección:

```text
Actor 1 is Clara, the woman wearing the teal cardigan. She looks toward the person just left of camera and speaks with quiet relief. Keep her established Spanish accent and warm medium-pitched voice. Her head moves slightly; both hands remain resting on the counter.
```

Actor 1 Script:

```text
¡Ahora sí! Tu pedido ya está preparado.
```

La dirección no selecciona una voz de catálogo. S7 no demuestra que esta ruta permita elegir Ryan de CloneVoice. Si la interfaz ofrece esa selección, comprobaremos el resultado; hasta entonces no prometeremos el mismo timbre que el narrador.

## B · Habla nativa dentro de Video and Audio Prompt

S2 y S4 documentan personajes que hablan con Lipsync HD y Narration Video desactivados, Video Only desactivado y el texto hablado dentro del prompt combinado. Puede servir para actuar y hablar a la vez en un plano continuo.

1. Prepara una imagen inicial con los sujetos, objetos y ruta de movimiento ya presentes.
2. Conserva referencias, formato y estilo. Desactiva Lipsync HD, Narration Video y Video Only para esta ruta documentada.
3. En Advanced Mode, cuando corresponda, activa Manual Video Length. Las fuentes describen un control de 3–10 s; comprueba el rango de tu versión.
4. Escribe un prompt combinado con una acción principal, cámara, descripción estable de voz, frase exacta entre comillas y quién guarda silencio.
5. Genera una prueba manual. Escucha la voz y revisa los labios antes de escribir muchas escenas con la misma configuración.

En S4 los clips son de 4–5 s y las frases de unas 8–10 palabras como planificación para inglés sencillo. No extrapoles esa velocidad a Ryan, español ni cualquier voz. Es mejor dividir una respuesta larga en dos acciones que acelerar el habla.

## Consistencia de voz y emoción

Un ancla de voz repite edad vocal, tono, timbre, acento y ritmo. Ayuda a orientar al generador pero no garantiza una identidad sonora idéntica.

S4 evita gritos, susurros y cambios extremos para reducir variaciones de timbre. S7 sí dirige emociones vocales intensas. Decide qué priorizar: continuidad sonora estable o interpretación expresiva. No combines «susurra», «grita» y «mantén exactamente el mismo volumen» en la misma dirección.

## Conversación de dos personajes

Planifica quién habla en cada plano, dónde mira y de qué lado del eje está la cámara. Mantén al oyente en silencio cuando aparece. Alterna plano medio del hablante, contraplano y reacción si la historia lo requiere. No afirmamos que se haya validado Lipsync HD con dos actores simultáneos: la fuente S7 no usa Add Actor 2 en su producción de un actor.

Procedencia: S7 pasos 1–6; S4 §§2–4; S2 introducción y ancla de presentador. Consulta las plantillas propias de 10.
