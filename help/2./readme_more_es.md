## Formato de los logros

Todos los archivos JSON de avance están estructurados de acuerdo con el siguiente formato:


display : los datos de pantalla opcionales.

    icon : los datos del icono.

        item : el ID del item.

        nbt : los datos nbt del item.

    frame : Es el tipo de marco opcional para el icono. _challenge_ para un marco con un borde más elegante, ya que se usa para el avance de matar a todos los mobs, el de todas las pociones; _goal_ para un marco con un borde redondeado como se usa para el avance completo del Faro, _task_ para un marco normal (es el predeterminado).

    descripción : la descripción del avance.

    show_toast : puede ser _true_ o _false_ Si mostrar o no la ventana emergente después de completar este avance.

    announce_to_chat : Es _true_ o _false_ Si anunciar o no en el chat cuando se ha completado este avance. Por defecto es verdadero.

 
parent : El directorio de avance de padres opcional de este avance. Si este campo está ausente, este avance es un avance de raíz. Las referencias circulares provocan un fallo de carga.

    criteria : Los criterios requeridos que deben cumplirse.

        trigger : El disparador de este avance; especifica lo que el juego debe verificar para el avance. condiciones : todas las condiciones que deben cumplirse cuando se activa el disparador.

 rewards : un objeto opcional que representa las recompensas proporcionadas cuando se obtiene este avance.

 recipes : una lista de recetas para desbloquear.
 {
 loot  : una lista de tablas de botín para entregar al jugador.
 {
 experience : una cantidad de experiencia .
 
 function : una función para ejecutar. No se permiten etiquetas de función .
