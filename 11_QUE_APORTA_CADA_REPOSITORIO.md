# 11 · Qué aporta cada repositorio

Los identificadores S1–S7 enlazan con [12](12_FUENTES_Y_LIMITES.md) y FUENTES.json. Esta comparación convierte recetas concretas en recursos para dirigir escenas; no reproduce sus instrucciones de ejecución automática.

## S1 · Stickman story agent

**Aporta:** protagonista 2D con imagen maestra independiente, escenario fijo opcional como segunda referencia, narración integrada por clip y continuidad de estado entre escenas. Separa la identidad del personaje de la pose necesaria en la acción. Propone revisar reparto, objetos, mirada y disposición espacial.

**Para nuestro método:** historias explicativas, anuncios y pequeñas aventuras. Útil para preparar estados de entrada/salida y evitar que todos los clips reinicien una acción.

**Particular de la receta:** estilo 2D predeterminado, una voz concreta cuando no se elige otra, y una producción rápida con pocas comprobaciones de vídeo. Aquí elegimos estilo y voz para cada historia y el usuario revisa la calidad que necesite. Su prohibición de ciertas rutas de audio rige esa receta, no todo VideoExpress.

## S2 · Historical documentary

**Aporta:** apertura con presentador realista y habla generada en prompt combinado; documental en acuarela y tinta; locución larga separada; procesos físicos y varios planos por clip. Muy útil para describir ropa, mecanismos, herramientas y arquitectura de la época.

**Para nuestro método:** alternar una persona que contextualiza con planos que muestran y explican. También sirve para un vídeo de fabricación o una historia sobre un lugar.

**Particular de la receta:** introducción de al menos 20 s, presentador y voces elegidos por el autor, duración total y narración conservada sin cambios. No hay que imponerlos a todos nuestros vídeos. No usa Lipsync HD para su presentador: documenta otra ruta de habla.

## S3 · Vox-style documentary

**Aporta:** dirección de arte en collage de papel, jerarquía de elementos, narración continua, planificación de segmentos semánticos y cortes visuales ligados a lo que se oye. Usa imágenes dentro de VideoExpress y audio en CloneVoice.

**Para nuestro método:** datos, comparaciones, explicaciones y documentos. Podemos tomar su disciplina de sincronizar el acontecimiento visual con la frase aunque no usemos collage.

**Particular de la receta:** paleta fija, estilo, voz inglesa, rangos de duración, tiempos por palabra y criterios de aceptación orientados a automatización rápida. No copiamos sus afirmaciones sobre modelos de IA ni sus scripts de interacción como recomendaciones de esta biblioteca. Sus versiones incluyen instrucciones de arrastre y de Add to Timeline diferentes; el método manual verifica cada inserción.

## S4 · Slow English learning videos

**Aporta:** relato 3D con dos personajes que hablan y actúan; anclas de voz, prendas distintas, propiedades de objetos, direcciones de viaje y una acción breve por plano continuo. Su ruta de habla es nativa desde el prompt, sin Lipsync HD ni narrador externo.

**Para nuestro método:** diálogos sencillos, escenas familiares y coordinación entre palabra y movimiento. Se pueden adaptar sus principios de claridad a otros idiomas.

**Particular de la receta:** inglés básico, dos personajes, clips 4–5 s, vocabulario y límites cortos de diálogo, prohibición de primeros planos y entregas poco frecuentes. Son medidas para reducir fallos observados; no límites universales de reparto o cámara. Una voz descrita por prompt puede variar entre generaciones.

## S5 · Nursery rhyme music video

**Aporta:** crear canción en CloneVoice, storyboard en Artistly, animar imágenes en VideoExpress y ajustar los extremos de música e imagen. Su guía controla la boca mientras conserva expresividad en ojos, postura y gestos.

**Para nuestro método:** escenas sobre canción externa, montajes musicales y evitar que un personaje parezca hablar sin motivo. Podemos escribir el storyboard manualmente.

**Particular de la receta:** depende de productos externos, fija opciones específicas de estilo, estructura y validación, y evita la revisión visual durante su automatización. Nosotros revisamos manualmente resultados. La guía de boca cerrada no sirve para un actor que deba pronunciar un diálogo o cantar.

## S6 · CloneVoice + narrativa 2D

**Aporta:** una unidad de narración por clip con audio integrado; investigación y registro de hechos; variedad de mapas, objetos, personajes y documentos; separación entre prompt visual y texto de voz. Documenta campos concretos y límites de la ruta de narración.

**Para nuestro método:** explicaciones por frases y preparación precisa de imágenes que muestran el verbo narrado. Aporta el registro de fuentes para historia y datos.

**Particular de la receta:** guion congelado con reglas de caracteres por minuto para una voz concreta y un número mínimo de filas. Esas cuentas no predicen toda voz o idioma. Incluye rutas de texto con herramientas externas y ejecución automática; aquí preferimos explicar cómo añadir texto editable manualmente y registrar la decisión.

## S7 · Consistent character talking video

**Aporta:** Lipsync HD, frase en Actor 1 Script, dirección de actuación y voz en Video Prompt, identidad repetida y revisión de manos/agarres. Explica cómo separar audio y vídeo para ajustar pausas preservando sincronía.

**Para nuestro método:** un personaje que se dirige a cámara, responde o expresa una emoción. Podemos montar conversaciones con planos alternos.

**Particular de la receta:** siete escenas y una onda emocional intensa, tipo Human y vertical como defaults, líneas inferiores a 100 caracteres en su ruta, un solo actor y duraciones solicitadas de ocho segundos. Ni la cantidad de escenas ni el salto emocional continuo son obligatorios. No demuestra que la voz del actor sea un preset de CloneVoice.

## Contradicciones que conviene resolver por contexto

| Tema | Lo que difiere | Criterio de esta biblioteca |
| --- | --- | --- |
| Audio | Voz integrada, habla nativa o pista larga externa | Elegir por función y ruta; no activar todo a la vez |
| Referencia 2 | Lugar vacío o segundo personaje | Priorizar la necesidad de ese plano y los huecos reales |
| Cámara | Plano continuo en S1/S4/S6, varios planos en S2/S3 | Usar continuidad para interacción y varios ángulos para explicación si procede |
| Expresión vocal | Neutral para estabilidad en S4, intensa en S7 | Probar equilibrio entre continuidad de voz e interpretación |
| Texto | Generado en collage o superpuesto en edición | Para texto exacto, recomendar una capa editable |
| Revisión | Algunas recetas omiten escuchar o ver medios | El usuario revisa imágenes y clips manualmente; la IA no inventa comprobaciones |
| Final | Algunas paran al entrar en cola; otras revisan exportado | Distinguir siempre «solicitado», «terminado» y «abierto/revisado» |

Conclusiones: síntesis propia de las versiones registradas, no una declaración oficial de capacidades de VideoExpress.
