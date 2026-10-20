# 9 · Problemas frecuentes y correcciones

Identifica primero si el problema está en la imagen, el movimiento, el audio o el montaje. Cambia la parte mínima necesaria y conserva lo que ya sirve. Esperar una cola no exige generar otra copia.

| Síntoma | Qué comprobar primero | Corrección para probar manualmente |
| --- | --- | --- |
| No encuentro el render | Carpeta My Media → My AI Videos; nombre/prompt; estado de proceso | Buscar el clip correcto antes de solicitarlo de nuevo |
| Vista previa negra | Cabezal dentro de la duración, visibilidad de pista y medio cargado | Mover el cabezal en la regla de tiempo, reproducir el clip |
| Se oye una frase dos veces | Audio integrado más otra pista con la misma frase | Dejar una sola versión, sin silenciar voces distintas necesarias |
| Boca cerrada mientras debería hablar | Ruta elegida y campo de texto | Lipsync: frase en Actor 1 Script; habla nativa: frase en prompt combinado |
| Personaje parece hablar sobre narrador | Movimiento bucal no deseado | Reforzar una expresión cerrada y gestos oculares; mantener audio en su campo |
| Voz cambia entre escenas | Voz seleccionada o descripción, idioma, acento y actuación | Conservar catálogo/selección cuando exista; repetir ancla y moderar cambios extremos en habla nativa |
| Narración cortada al final | Duración real del audio frente al clip | Dividir la frase o preparar más tiempo visual; probar el nuevo clip |
| Cambia cara, ropa o edad | Referencia realmente seleccionada y descripción estable | Restaurar referencia y texto; simplificar escena y comparar imagen antes de animar |
| La ropa pasa al otro personaje | Prendas demasiado similares y referencias ambiguas | Dar siluetas diferenciadas, roles claros y usar planos individuales |
| Manos extra o agarre imposible | Imagen original, superposiciones y función de cada mano | Simplificar a un agarre claro, cámara fija y objeto apoyado |
| Aparece otro teléfono o animal | Objeto repetido como si fueran varios, cuenta y ubicación | Describir una sola instancia y referirse después a ese mismo objeto |
| El movimiento atraviesa una puerta | Ruta y estado de la puerta en la imagen | Abrirla en un beat propio o detener al personaje delante |
| Una bicicleta va hacia atrás | Orientación del vehículo, pantalla y acción | Alinear imagen inicial con dirección de avance y seguimiento lateral |
| Repite acercamiento en cada clip | Estado inicial y final de las escenas | Continuar desde el contacto o postura final anterior |
| Escenario se refleja o cambia de lado | Cámara y posiciones de referencias | Mantener eje, repetir distribución y corregir imagen antes del vídeo |
| Textos y cifras mal escritos | Texto generado dentro de imagen | Reservar zona limpia y añadir texto editable después |
| Sale el clip de otra escena | Candidato resaltado en el carrusel | Seleccionar explícitamente la imagen correcta y verificar miniatura de la solicitud |
| No se respeta el formato | Selector del proyecto frente al diálogo de generación | Ajustar ambos antes de generar; no confiar en un recorte posterior |
| El prompt cambia solo | Opciones Automatically enhance | Desactivar cuando sea posible; revisar el texto y resultado si no se puede |

## Cómo pedir ayuda con un resultado

Describe lo esperado, lo observado, el modo elegido, el texto exacto y qué ya probaste. Si puedes compartir una imagen o clip, la IA revisará solo lo que realmente pueda observar. No hace falta repetir toda la historia para corregir una mano o una frase.

## No todos los controles tienen que estar activados

Narration Video y Lipsync HD responden a fines diferentes. Video Only contradice una solicitud de voz generada integrada en las rutas descritas. Advanced Mode y Manual Video Length se usan en unas recetas y se mantienen apagados en otras. Revisa la ficha de la ruta seleccionada, no una configuración universal.

Procedencia: fallos documentados en S1–S7 y experiencia Enodi en 13. La tabla es síntesis propia; una causa posible es una hipótesis hasta comprobarla.
