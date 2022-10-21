MarsPhotos 
==================================
Introducción
------------

MarsPhotos es una aplicación de demostración que muestra imágenes reales de la superficie de Mar. estas imagenes son
fotos de la vida real de Marte capturadas por los rovers de Marte de la NASA. Los datos se almacenan en un servidor web.
como un servicio web REST. Esta aplicación demostró el uso de [Retrofit](https://square.github.io/retrofit/) para realizar solicitudes REST al servicio web, [Moshi](https://github.com/square/moshi) para
manejar la deserialización del JSON devuelto a los objetos de datos de Kotlin y [Coil](https://coil-kt.github.io/coil/) para cargar imágenes por URL.

La aplicación también aprovecha [ViewModel] (https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata), y
[Enlace de datos] (https://developer.android.com/topic/libraries/data-binding/) con enlace
adaptadores

requisitos previos
--------------

Necesitas saber:
- Cómo crear y usar fragmentos.
- Cómo usar los componentes de la arquitectura, incluidos ViewModel y LiveData.
- Cómo usar rutinas para tareas de larga duración.

