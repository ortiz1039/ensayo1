REQUISITOS FUNCIONALES

ABRIL 2024
DESARROLLO DE UNA APLICACIÓN DE STREAMING 

BEATFLOW MUSIC   

 BeatFlow es un reproductor de música dinámico diseñado para ofrecer una experiencia auditiva excepcional. Con una interfaz elegante y funciones intuitivas, BeatFlow te permite sumergirte en un mundo de melodías y ritmos. Explora una amplia biblioteca de canciones, crea listas de reproducción personalizadas y descubre nuevas pistas de manera sencilla. Ya sea que estés relajándote en casa o en movimiento, BeatFlow te acompaña con una calidad de sonido impresionante y una navegación sin complicaciones. Deja que BeatFlow te lleve en un viaje musical inigualable."
BeatFlow es mucho más que un simple reproductor de música; es una plataforma completa que ofrece una experiencia auditiva excepcional con una variedad de características diseñadas para satisfacer las necesidades y preferencias del usuario.

Crear una lista de reproducción: Con BeatFlow, puedes crear fácilmente listas de reproducción personalizadas para agrupar tus canciones favoritas según tu estado de ánimo, género musical o cualquier otro criterio que desees.

Visualizar las listas de reproducción: Una vez que has creado tus listas de reproducción, BeatFlow te permite visualizarlas de manera clara y organizada, para que puedas acceder rápidamente a ellas y administrar tu música de manera eficiente.

Agregar una canción a una lista: ¿Encontraste una canción que te encanta y quieres agregarla a una de tus listas de reproducción? Con BeatFlow, simplemente selecciona la canción y añádela a la lista de reproducción deseada en solo unos pocos clics.

Eliminar canción de una lista: Si decides que ya no quieres una canción en tu lista de reproducción, BeatFlow te permite eliminarla fácilmente, manteniendo tus listas organizadas y actualizadas.

Agregar una lista de canciones a la cola de reproducción: ¿Quieres escuchar una lista de reproducción específica en este momento? Simplemente agrega la lista de canciones a la cola de reproducción y BeatFlow se encargará de reproducir todas las canciones en el orden en que aparecen en la lista.

Modo aleatorio de la cola de reproducción: Para añadir emoción y variedad a tu experiencia auditiva, BeatFlow ofrece un modo aleatorio para la cola de reproducción, que mezcla tus canciones de forma aleatoria para una experiencia de escucha más dinámica.

Visualizar canciones de una lista: Cuando desees ver las canciones que componen una lista de reproducción específica, BeatFlow te proporciona una vista detallada de todas las canciones incluidas en esa lista.

Visualizar la cola de reproducción: ¿Quieres saber qué canciones se reproducirán a continuación en la cola? BeatFlow te permite visualizar fácilmente la cola de reproducción para que puedas planificar tu experiencia auditiva.

Reproducir la cola de reproducción: Una vez que hayas creado tu lista de reproducción y configurado la cola de reproducción según tus preferencias, simplemente presiona reproducir y BeatFlow se encargará de reproducir todas las canciones en orden.

Reproducir la siguiente y anterior canción: BeatFlow te permite controlar la reproducción de tu música fácilmente, con opciones para saltar a la siguiente o anterior canción según tus preferencias.

Buscar una canción en el catálogo de canciones: ¿Buscas una canción específica en el vasto catálogo de BeatFlow? Utiliza la función de búsqueda para encontrar rápidamente la canción que deseas escuchar.

Subir y bajar el volumen de la música: BeatFlow te permite controlar el volumen de la música con facilidad, con opciones para subir o bajar el volumen según tus preferencias de escucha.

En resumen, BeatFlow es un reproductor de música completo que ofrece una amplia gama de características y funcionalidades para mejorar tu experiencia auditiva, desde la creación y gestión de listas de reproducción hasta la reproducción de música en modo aleatorio y la búsqueda de canciones específicas en su catálogo. Con una interfaz intuitiva y fácil de usar, BeatFlow te permite disfrutar de tu música favorita de manera conveniente y personalizada.


REQUISITOS FUNCIONALES


NOMBRE	
R1: Crear una lista de reproducción

RESUMEN	Permitir a los usuarios crear una lista de reproducción personalizada en la aplicación.

ENTRADA	Nombre de la lista de reproducción ingresados por el usuario


RESULTADO	creación exitosa de una nueva lista de reproducción con el nombre especificado por el usuario.
	
	
PASOS	METODO	RESPONSABLE
Seleccionar las canciones 	Seleccionar_cancion	canción
Crear lista de reproducción	Crear lista _reproducción	Lista reproducción
Agregar las canciones a lista 	Agregar_canciones a lista reproducción	canción y lista reproducción 
		

NOMBRE	
R2: Visualizar una lista de reproducción 

RESUMEN	Permitir a los usuarios ver el contenido de una lista de reproducción existente en la aplicación 
 
ENTRADA	
-	Nombre de una lista de reproducción por parte de los usuarios

RESULTADO	-	visualización del contenido de la lista de reproducción
-	información adicional sobre la lista de reproducción (nombre)

	
	
PASOS	METODO	RESPONSABLE
obtener los datos de la lista de 	Visualizar_listareproduccion	listaReproduccio
Mostrar la lista de reproducción en la interfaz de usuario 	Visualizar_listareproduccion	listaReproduccio
Permitir la navegación por lista 	Visualizar_listareproduccion	listaReproduccio
Permitir la selección y reproducción de elementos de la lista 	Visualizar_listareproduccion	listaReproduccio













		





NOMBRE	
R3: Agregar canción a una lista
  
                                RESUMEN	Permitir a los usuarios agregar una canción especifica a una lista de reproducción existente en la aplicación 

ENTRADA	-	canción seleccionada por el usuario para agregar a la lista de reproducción
-	Lista de reproducción destino seleccionada por el usuario.

RESULTADO	-	Agregación exitosa de la canción seleccionada la lista de reproducción especificada.

	
	
PASOS	METODO	RESPONSABLE
Identificar una lista de reproducción existente o crear una nueva lista	Identificar_lista	Lista de reproducción
Seleccionar una canción 	Sele_cancion	canción
Agregarla a la lista de reproducción	
Agregar_lista
	Lista de reproducción
		













	

NOMBRE	
R4: Eliminar canción de una lista

RESUMEN 	Permitir a los usuarios eliminar una canción especifica de una lista de reproducción en la aplicación.

ENTRADA	-	canción seleccionada por el usuario para eliminar de la lista de reproducción
-	Lista de reproducción de donde se eliminará la canción seleccionada.
	
	
PASOS	METODO	RESPONSABLE
Seleccionar Canción	Sel_cancion(self)	Canción
Eliminar Canción	Eliminar_cancion(init)	Lista reproducción
Actualizar lista	Act_lista(self)	Lista reproducción
	
	
	
	
  
RESULTADO	-	eliminación exitosa de la canción seleccionada de la lista de reproducción

	-	

NOMBRE	
R5: Agregar una lista de canciones a la cola de reproducción.

RESUMEN 	Permitir a los usuarios agregar a la cola de reproducción una lista de canciones

ENTRADA	-	Lista de canciones que se agregara a la cola.

RESULTADO	-	Agrega la lista de canciones a la cola.
	-	

NOMBRE	
R6: Modo aleatorio de la cola de reproducción

RESUMEN 	Permitir a los usuarios escuchar las canciones de la cola de reproducción de forma aleatoria.

ENTRADA	-	Canciones en la cola de reproducción.

RESULTADO	-	Las canciones en la cola se reproducen aleatoriamente. 
	

NOMBRE	
R7: Visualizar las canciones de una lista de reproducción.

RESUMEN 	Permitir a los usuarios ver todas las canciones de una lista de reproducción.

ENTRADA	-	El usuario selecciona la lista de reproducción que desea ver.


RESULTADO	-	El sistema muestra la lista de reproducción
	

NOMBRE	
R8: Visualizar la cola de reproducción.

RESUMEN 	Permitir a los usuarios ver las canciones que están en la cola de reproducción. 

ENTRADA	

RESULTADO	-	El sistema muestra la cola de reproducción.
	

NOMBRE	
R9: Reproducir la cola de reproducción.

RESUMEN 	Permitir a los usuarios reproducir las canciones que están en la cola de reproducción. 

ENTRADA	

RESULTADO	-	El sistema reproduce las canciones que están en la cola de reproducción.
	-	

NOMBRE	
R10: Reproducir la siguiente/anterior canción.

RESUMEN 	Permitir a los usuarios saltar o devolver la canción que esté sonando. 

ENTRADA	-	El usuario selecciona si salta o devuelve la canción.

RESULTADO	-	El sistema devuelve o salta la canción
	

NOMBRE	
R11: Buscar una canción en el catálogo de canciones

RESUMEN 	Permitir a los usuarios buscar alguna canción sin la necesidad de estar en una lista de reproducción. 

ENTRADA	-	El usuario busca la canción.

RESULTADO	-	El sistema muestra la canción.
-	El usuario selecciona el que hacer con la canción (agregar a la cola, agregar a la fila, …).
	

NOMBRE	
R12: Subir o bajar volumen de la canción.

RESUMEN 	Permitir a los usuarios subir o bajar el volumen de la canción que esté sonando. 

ENTRADA	-	El usuario selecciona el volumen de la canción.


RESULTADO	-	El sistema reproduce la canción en el volumen seleccionado.









REPRESENTACION GRAFICA
  
Modelo del mundo del problema 

