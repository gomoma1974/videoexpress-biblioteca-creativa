# 15 · Ejemplo: «El pedido que cambió la tarde»

**Estado:** ejemplo creativo propio, preparado para explicar el uso de la biblioteca; no se han generado ni probado estos medios. Duración orientativa: 35–45 s, ajustable tras escuchar las frases. Formato propuesto: vertical 9:16. Estética: ilustración 2D cálida en todas las escenas.

Clara atiende una pequeña cafetería. Leo intenta pedir por teléfono. Clara descubre que puede organizar los pedidos de otra forma, y ambos recuperan tiempo. La historia puede adaptarse a un anuncio, pero ninguna interfaz o función comercial concreta debe mostrarse como real sin comprobarla.

## Plan de recursos

| Escena | Acción y función | Técnica elegida | Audio propuesto | Duración orientativa |
| --- | --- | --- | --- | --- |
| 1 | Clara mira el teléfono mientras un pedido espera; presentar el problema | Narración integrada para explicar el contexto | «A media tarde, Clara intentaba atenderlo todo a la vez.» | 5–6 s |
| 2 | Clara habla al cliente fuera de plano; dar presencia humana al conflicto | Lipsync HD en plano medio individual | «Un momento, por favor. Ahora te atiendo.» | 4–5 s |
| 3 | Leo observa su móvil y decide; mostrar el punto de vista del cliente | Acción visual sin voz | Ambiente suave; sin texto generado | 4–5 s |
| 4 | Una pantalla sencilla representa el pedido; explicar el cambio | Plano de objeto con narración integrada | «Esta vez, el pedido llegó sin una llamada más.» | 5–6 s |
| 5 | Clara prepara una bolsa; dar tiempo al resultado | Acción visual sobre música discreta | Sin diálogo | 4–5 s |
| 6 | Leo recibe el pedido; resolver | Plano individual de Leo con Lipsync HD | «¡Qué fácil! Ya puedo seguir con mi día.» | 4–5 s |
| 7 | Cierre visual de la cafetería; dejar una idea | Narración integrada y texto editable | «Más tiempo para atender. Más comodidad para pedir.» | 5–6 s |

El narrador conecta momentos, el diálogo aporta cercanía y las acciones permiten comprender el cambio. La cámara no necesita moverse siempre. El montaje debe conservar la misma ropa, luz y distribución del café.

Las duraciones son estimaciones, no reservas exactas del generador. Ajustaremos al comprobar voz y actuación. No elegiríamos automáticamente la misma voz para los dos personajes ni asumiríamos que la voz narradora está disponible en Lipsync HD.

## Referencias necesarias

Clara: mujer adulta de pelo corto oscuro, camisa mostaza y delantal verde azulado, con silueta y cara estables. Leo: adulto joven de pelo rizado, chaqueta azul y camiseta clara. Para cada plano hablante se utiliza la referencia de ese personaje. La referencia del café se emplea cuando hay un hueco disponible; su distribución se describe siempre.

Café: puerta izquierda, ventana posterior izquierda, mostrador a la derecha y cafetera al fondo a la derecha. Evitar que un contraplano refleje arbitrariamente esa geometría. Para un plano individual, las miradas hacia otro personaje se definen fuera de cámara.

## Ficha preparada · Escena 1

**Función:** mostrar una interrupción, sin que Clara pronuncie la voz del narrador. **Ruta:** narración integrada de 03. **Estado final:** Clara atiende el teléfono; la siguiente escena empieza en ese contacto.

Configuración para el usuario: proyecto y generador en Vertical 9:16; Image Type 2D; Use Consistent Character con la referencia de Clara y, si se usa, la del café en el segundo hueco. Narration Video activado, Lipsync HD y Video Only desactivados; Advanced Mode desactivado para esta ruta. Mejora del prompt desactivada cuando esté disponible.

Image Prompt:

```text
Vertical 9:16, warm hand-drawn 2D illustration with clear ink outlines and matte cel colours. Clara is an adult woman with short dark hair, an oval face, a mustard cotton shirt and a teal apron. She stands behind the counter on the right, looking down at a single black desk telephone near the counter's inner edge. Her right hand rests beside the receiver; her left hand is empty at her side. One closed paper bag waits farther along the counter. The café door is on the left, the window on the rear-left wall and the coffee machine at the rear-right. Soft late-afternoon light enters from the window. Medium shot with room for her right arm to lift the receiver, one readable opening pose and no printed lettering.
```

Video and Audio Prompt, solo movimiento:

```text
A continuous medium 2D shot preserves Clara's face, mustard shirt, teal apron and the café layout. She starts with her right hand beside the single receiver and slowly lifts it to her right ear. Her left hand stays empty. She glances once toward the waiting paper bag, then holds the receiver steady with a slightly concerned expression. The camera remains fixed at counter height and ends with her face and the telephone visible. The door, window, coffee machine and bag stay in their established positions.
```

Texto de CloneVoice en el diálogo integrado:

```text
A media tarde, Clara intentaba atenderlo todo a la vez.
```

Pasos: selecciona referencias → genera y revisa la imagen → selecciona el candidato correcto → introduce movimiento → activa Narration Video → abre Create Video → escoge idioma español y la voz narradora → importa/genera la frase → completa Create Narration Video según la interfaz. Revisa el clip y que la frase acaba entera. El usuario elige la voz; Ryan puede ser una propuesta si quiere mantener la referencia del anuncio anterior.

## Ficha preparada · Escena 2

**Función:** escuchar a Clara reaccionar. **Ruta:** Lipsync HD, 04 A. No usamos narrador sobre la misma frase. La posibilidad de conservar el teléfono mientras habla requiere revisar el agarre y la boca.

Configuración: mantiene 9:16, 2D y la referencia de Clara. Activa Lipsync HD y utiliza la ruta de diálogo del actor; no mantengas el modo de narración de la escena anterior por inercia. Si el producto oculta controles de duración al activar Lipsync, configura antes una duración orientativa compatible.

Image Prompt:

```text
Vertical 9:16, warm hand-drawn 2D frame with the established ink outlines and matte colours. Clara is an adult woman with short dark hair, an oval face, a mustard cotton shirt and a teal apron. In an eye-level medium close shot behind the same counter, she holds the single black telephone receiver gently to her right ear with her right hand. Her wrist is straight and her elbow rests near her torso. Her left hand rests empty on the counter. Her face and mouth remain unobstructed; she looks slightly toward screen left with patient concern. The rear-right coffee machine and soft rear-left window light match the established café. One character and one receiver, clear natural contact, no printed text.
```

Video Prompt del diálogo Create Lipsync Audio:

```text
Actor 1 is Clara, the woman wearing the mustard shirt and teal apron. She speaks Spanish with a warm medium-pitched voice and a natural Spanish accent. She says her line with patient concern while keeping the receiver steady at her right ear. Her head makes one small reassuring nod. Her left hand stays resting on the counter and her mouth remains clearly visible. Preserve the established face and illustration style.
```

Actor 1 Script:

```text
Un momento, por favor. Ahora te atiendo.
```

Pasos: revisa y selecciona la imagen → verifica Lipsync HD y referencia → abre la creación del audio labial → introduce la dirección en Video Prompt y solo la frase en Actor 1 Script → genera manualmente → reproduce con sonido y revisa boca, frase y mano. Si el gesto falla, conserva un plano más estable o encuadra sin la mano; no cambies la identidad para corregir el objeto.

La dirección describe una voz; no está validada como selección de Ryan. Si necesitas una voz exactamente igual entre ambos modos, primero habrá que probar qué controles de voz ofrece esa ruta.

## Cómo desarrollaríamos el resto

Prepararíamos cada ficha restante cuando vayamos a trabajarla, incorporando las duraciones y estados reales de lo aprobado. Para la pantalla de la escena 4, generamos una composición limpia y añadimos manualmente las palabras o imágenes reales de la app si se han aportado. En el cierre, el nombre del negocio y la llamada a la acción se añaden como texto editable.

La técnica de montaje musical de la escena 5 adapta 07 a una historia comercial; no requiere generar una canción infantil ni usar Artistly. No se impondrá una música si el usuario prefiere solo ambiente.
