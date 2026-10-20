# 7 · Música, canciones y escenas sin diálogo

## Qué aporta la fuente musical

S5 encadena **CloneVoice para crear la canción**, **Artistly para obtener un storyboard visual** y **VideoExpress para animar y montar**. Es importante conservar esta atribución: no son tres funciones demostradas dentro de VideoExpress.

El storyboard automático de Artistly es una opción de esa receta. Para nuestro método, podemos diseñar manualmente cada escena y usar VideoExpress con las imágenes escogidas. Esta adaptación permite controlar la historia y no obliga a emplear Artistly.

## Preparación manual de una canción

1. Define protagonista, objetivo musical, idioma, género, ánimo y letra o idea.
2. Si utilizas CloneVoice Music, las fuentes describen New → AI-Generated, idea, estilo e idioma, después Generate Lyrics, revisión y Generate Music. El límite de 150 caracteres corresponde a su campo de idea documentado; compruébalo en tu interfaz.
3. Revisa la letra antes de producir: identidad de personajes, vocabulario, ritmo y pronunciaciones. Las opciones o acuerdos del servicio los decide el usuario.
4. Espera a la canción completa y mide su duración real. Divide estrofas, estribillos y transiciones por lo que se oye.
5. Diseña un acontecimiento visual para cada segmento. El estribillo puede repetir un motivo con evolución, en lugar de repetir exactamente el mismo clip.

Si eliges Artistly, S5 distingue Nursery Rhymes —personajes deducidos de la letra— de Music Storyboard —con una indicación de estilo propia—. Cambia el formato predeterminado si no coincide con tu proyecto y revisa que obtienes un storyboard completo. No tratamos una lista de imágenes creada con errores como un resultado aprobado.

## Animar para música sin habla accidental

Cuando la canción suena sobre las imágenes pero los personajes no cantan en pantalla, conviene una expresión de boca cerrada estable y una interpretación mediante mirada, postura y manos. Para no congelar al personaje, conserva movimiento corporal y ambiental.

Plantilla propia:

```text
One continuous shot keeps the accepted illustrated character and room unchanged. From the opening frame, Nora maintains a relaxed closed-mouth expression with a still jaw. She slowly tilts her head toward the glowing window, blinks and raises her eyebrows with curiosity. Her shoulders and scarf move gently as the curtain sways. The camera follows a short lateral path and settles with her face and the window visible. Her expression never changes into speech.
```

Este prompt es para una ruta visual sobre una pista musical externa. No lo uses en una escena donde Nora deba hablar. Si usamos narración integrada visual pura de 03, mantendremos fuera del movimiento las instrucciones de audio y escogeremos solo las indicaciones de expresión pertinentes.

## Voz, canción y ambiente son capas distintas

- **Sin diálogo** significa que nadie dice una frase; aún puede haber ambiente o música.
- **Video Only (No Sound)** sirve en las rutas documentadas para generar imágenes en movimiento sin sonido. Actívalo cuando colocaremos una pista separada.
- **Canción aparte** no equivale a sincronización labial de canto. S5 intenta evitar precisamente ese movimiento bucal. Esta edición no valida un procedimiento de canto labial sincronizado.
- **Ambiente** puede apoyar una acción. No nombres una máquina inexistente como fuente de sonido si no quieres que el modelo la introduzca visualmente.

## Montaje a la música

Coloca la pista completa en el punto elegido. Ajusta las acciones y los cortes a frases y cambios musicales; no distribuyas todas las imágenes a intervalos iguales sin escucharlas. Si falta imagen, planifica cobertura adicional o alarga un segmento que admita tiempo; si sobra, recorta el excedente visual sin cortar por accidente la canción.

La coincidencia del final de imagen y audio se revisa en la línea de tiempo y en reproducción. Una igualdad de píxeles depende del zoom; no es una medida universal de sincronía ni sustituye a escuchar.

Procedencia: S5 SYSTEM_PROMPT, secciones 5–12, y PROMPT_GUIDE. El método de storyboard manual y la plantilla anterior son adaptaciones propias.
