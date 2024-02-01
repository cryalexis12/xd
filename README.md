![](https://itq.edu.ec/wp-content/uploads/2023/02/Recurso-6.png)

                    
Cargo  |Docente  |  
------------- | -------------
Nombre  | Ing. Sebastián Landázuri  |
Asignatura  | Base de Datos no relacionales    |
Carrera  | Desarollo de Software  | 
Nivel: | Tercer Nivel |
Estudiante  | Bryan Velasco, Alejandro Argoti, Alexis Velasco , Lizandro Duran, Gabriel Salazar    |

--------------Proyecto--------------
=============
## Crear una base de datos no relacionales en MongoDB Compass para saber su funcionalidad:
![](https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs/239708679/original/a76d5bfba0311514d6c1f5f607373a1bdd5a865a/anything-and-everything-about-mongodb.png)

### Objetivo

El objetivo principal de este proyecto es diseñar e implementar una base de datos no relacional utilizando MongoDB Compass, estableciendo una conexión eficiente con el cluster de MongoDB Atlas. Se busca comprender y aplicar los conceptos fundamentales de bases de datos no relacionales, aprovechando las capacidades de MongoDB Compass como herramienta gráfica para consultar, optimizar y analizar los datos almacenados. Además, el proyecto tiene como meta explorar y aprovechar las características del servicio de cluster de MongoDB Atlas para garantizar un entorno de base de datos escalable, seguro y de alto rendimiento.

### Marco Teorico

#### Bases de Datos No Relacionales:
Las bases de datos no relacionales, también conocidas como bases de datos NoSQL, representan una categoría de sistemas de gestión de bases de datos que difieren del modelo relacional tradicional. Estas bases de datos están diseñadas para manejar grandes volúmenes de datos distribuidos y ofrecen flexibilidad en la estructura de datos, permitiendo almacenar información en formatos como documentos, pares clave-valor, columnares o basados en grafos.

#### MongoDB Compass 6.0:
MongoDB Compass es una interfaz gráfica de usuario para MongoDB que proporciona herramientas intuitivas y visuales para interactuar con las bases de datos. Permite realizar consultas, indexar datos, optimizar consultas y visualizar la estructura de la base de datos de manera eficiente. Su capacidad para arrastrar y soltar facilita el desarrollo de consultas y análisis de datos.

#### MongoDB Atlas (Cluster) :
MongoDB Atlas es un servicio de base de datos en la nube que proporciona un conjunto integrado de servicios para bases de datos MongoDB. Ofrece opciones de escalabilidad automática, respaldos automáticos, seguridad avanzada y una gestión simplificada. El uso de MongoDB Atlas garantiza una infraestructura confiable y eficiente para la implementación de bases de datos MongoDB en entornos de producción.

#### Conexión entre MongoDB Compass y MongoDB Atlas:
La conexión entre MongoDB Compass y MongoDB Atlas se realiza mediante la configuración de las credenciales de acceso y la cadena de conexión específica proporcionada por MongoDB Atlas. Esta conexión segura permite a los usuarios administrar y visualizar los datos almacenados en el cluster de MongoDB Atlas a través de la interfaz gráfica de MongoDB Compass.

#### Beneficios de la Implementación:
- Escalabilidad: MongoDB Atlas facilita la escalabilidad horizontal y vertical de la base de datos, permitiendo manejar crecimiento futuro.
- Seguridad: Con MongoDB Atlas, se implementan medidas de seguridad avanzadas, como la autenticación, autorización y cifrado de datos, para proteger la integridad de la información.
- Rendimiento: La optimización de consultas y la distribución eficiente de datos en el cluster contribuyen a un rendimiento óptimo de las operaciones de base de datos.


## Conexion al cluster 
Obtén la URL de conexión: Proporcionada por tu proveedor o clúster, incluyendo detalles como nombre de usuario, contraseña y dirección del servidor.

Configura el controlador de MongoDB: Asegúrate de tener el controlador de MongoDB instalado en tu aplicación, disponible en la mayoría de los lenguajes.

Implementa la conexión en tu aplicación: Utiliza la URL de conexión para establecerla, luego podrás realizar operaciones en la base de datos.



# Proyecto N°2
Nuestro proyecto se basa en hacer una base de datos de Streaming, asi creando una base de datos para una plataforma de streaming con módulos de Contenido Multimedia, Usuarios y Perfiles, y Estadísticas y Análisis, son algunos de los ejemplos que podemos tener dentro de esta base de datos, puedes seguir estos pasos:

Diseño de la Base de Datos:

Contenido Multimedia:
Colecciones: Peliculas, Series, EventosEnVivo.
Campos: Titulo, Descripcion, Duracion, Genero, Actores, Director, AñoLanzamiento, etc.
Usuarios y Perfiles:
Colecciones: Usuarios, Perfiles.
Campos: NombreUsuario, CorreoElectronico, Contraseña, Preferencias, HistorialVisualizacion, ListasReproduccion, etc.
Estadísticas y Análisis:
Colecciones: Visualizaciones, Comentarios, Calificaciones, Tendencias.
Campos: FechaVisualizacion, Usuario, PeliculaSerieEventoID, Comentario, Calificacion, etc.
Conexión a la Base de Datos:

Utiliza el controlador de MongoDB en tu lenguaje de programación preferido.
Conecta tu aplicación a la base de datos utilizando la URL de conexión proporcionada por tu proveedor de MongoDB.

### Capturas

### Coleccion Comentarios 
La colección "comentarios" constituye un repositorio que almacena de manera organizada los comentarios emitidos por los usuarios.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Comentarios.png?raw=true)

### Coleccion Categorias
La colección de categorias guarda la informacion de las categorias y se referencia con los peliculas y series para hacer que pertenezcan a una o varias categorias.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Categoria.png?raw=true)


### Coleccion Descargas
La colección "descargas" constituye un repositorio estructurado que almacena información relevante sobre las descargas realizadas por los usuarios, específicamente en relación con películas y episodios de series.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Descargas.png?raw=true)

### Coleccion EpisodiosSeries
La colección "EpisodiosSeries" almacena información detallada sobre episodios de series, incluyendo número, título, duración, fecha de estreno y temporada. Este repositorio es esencial para organizar y presentar de manera estructurada los contenidos.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/EpisodiosSeries.png?raw=true)

### Coleccion Estadisticas
La colección "EstadisticasVisualizaciones" constituye un repositorio clave que almacena datos estadísticos relevantes relacionados con la cuenta de usuario. Incluye información como el número total de visualizaciones y ultima visualizacion, esta misma va referenciado a peliculas.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Estadisticas.png?raw=true)

### Coleccion EstadoReproduccion
La colección de categorias guarda la informacion de las categorias y se referencia con los peliculas y series para hacer que pertenezcan a una o varias categorias.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/EstadoReproduccion.png?raw=true)

### Coleccion EstudiosProducciones
La colección "EstudiosProducciones" es un repositorio esencial que almacena información detallada sobre estudios de producción y sus asociaciones con películas y series específicas.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/EstudiosProdu.png?raw=true)

### Coleccion Eventos
La colección "Eventos" se configura como un repositorio esencial que almacena detalles clave sobre eventos multimedia destacados, vinculándolos con las series y películas participantes.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Eventos.png?raw=true)

### Coleccion EventosVivo
La colección "EventosEnVivo" actúa como un repositorio clave que almacena información detallada sobre la programación transmitida en vivo, incluyendo datos sobre eventos, fechas y las series o películas relacionadas.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/EventosVivo.png?raw=true)

### Coleccion Favorito
La colección "Favoritos" constituye un repositorio esencial que almacena información sobre la multimedia marcada como favorita por los perfiles de usuarios. Incluye datos como títulos de películas y series que van referenciados.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Favorito.png?raw=true)

### Coleccion Historiales
La colección "Historiales" funciona como un repositorio fundamental que registra las películas y series visualizadas por cada perfil de usuario. Contiene información detallada sobre los títulos, permitiendo una gestión efectiva del historial de visualización de cada usuario.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Historiales.png?raw=true)

### Coleccion ListasReproducciones
La colección "ListasReproducciones" es un repositorio central que almacena listas personalizadas de películas y series creadas por perfiles de usuario. Contiene información detallada sobre los títulos incluidos, facilitando la gestión eficiente de listas de reproducción personalizadas.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/ListasRepro.png?raw=true)

### Coleccion Notificaciones
Esta colección posibilita un análisis detallado de las interacciones y respuestas de los usuarios a las notificaciones, contribuyendo así a optimizar estrategias de comunicación.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Notificaciones.png?raw=true)

### Coleccion Ofertas
La colección "Ofertas" funciona como un repositorio clave que almacena información sobre ofertas especiales proporcionadas por nuestra plataforma. Incluye datos detallados sobre las ofertas, como descuentos, promociones y fechas de validez, facilitando la gestión efectiva de oportunidades promocionales. 

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Ofertas.png?raw=true)

### Coleccion Pagos
La colección "Pagos" constituye un repositorio esencial que almacena información sobre las diversas formas de pago proporcionadas por nuestra plataforma. Contiene datos detallados acerca de métodos de pago, impuesto, cobro y asi, facilitando la gestión eficaz de las opciones de pago.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Pagos.png?raw=true)

### Coleccion Peliculas
La colección "Películas" actúa como un repositorio fundamental que almacena información detallada sobre películas, incluyendo sus categorías, y los premios en los que han sido nominadas. Contiene datos esenciales como títulos, categorías temáticas y reconocimientos, facilitando la gestión eficaz de la oferta cinematográfica.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Peliculas.png?raw=true)

### Coleccion PerfilUsuario

La colección "PerfilesUsuarios" se constituye como un repositorio esencial que almacena información sobre los diferentes perfiles que los usuarios pueden crear en nuestra plataforma. Contiene datos detallados, como nombres de perfil, preferencias personalizadas y configuraciones individuales, facilitando la gestión eficaz de las cuentas de usuario.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/PerfilUsuario.png?raw=true)

### Coleccion Populares
Contiene datos clave como el mes, peliculas y series, facilitando la gestión eficaz de los contenidos populares. Esta colección permite un análisis detallado de las tendencias de visualización mensuales, contribuyendo así a destacar y promover el contenido más popular. 

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Populares.png?raw=true)

### Coleccion Premios
La colección "Premios" constituye un repositorio clave que almacena información sobre los premios más relevantes de la industria del entretenimiento. Contiene datos detallados como nombres de premios y la descripcion del premio del ganador.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Premios.png?raw=true)

### Coleccion Restricciones
La colección "RestricionRegional" se configura como un depósito central que almacena información acerca de las películas y series exclusivas para determinadas regiones.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Restricciones.png?raw=true)

### Coleccion Subcripciones
La colección "Subscripciones" funciona como un repositorio central que almacena información sobre las diversas suscripciones ofrecidas por la plataforma. Contiene datos esenciales, como tipos de suscripciones, tarifas.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Subscripciones.png?raw=true)

### Coleccion Trailers
La colección "Trailers" actúa como un repositorio central que almacena información detallada sobre avances de películas y series. Contiene datos esenciales, como títulos, duración, descripcion y tipo de duracion. 

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Trailers.png?raw=true)

### Coleccion Usuarios

La colección "Usuarios" constituye un repositorio fundamental que almacena información detallada sobre las cuentas de usuario, incluyendo datos para iniciar sesión, configuraciones personalizadas, información de pagos y tipos de suscripción. Contiene datos esenciales como nombres de usuario, contraseñas cifradas, preferencias de configuración y detalles de la suscripción, facilitando la gestión integral de las cuentas.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Usuarios.png?raw=true)

### Coleccion Valoraciones
La colección "Valoraciones" se configura como un repositorio esencial que almacena información sobre las distintas valoraciones que los usuarios asignan a series y películas. Contiene datos fundamentales como títulos, puntuaciones, y fechas de valoración, facilitando la gestión eficiente de las preferencias de los usuarios.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/Valoraciones.png?raw=true)

### Coleccion ConfiguracionesCuentas
La colección "ConfiguracionesCuentas" funciona como un repositorio central que almacena información detallada sobre las preferencias y configuraciones de las cuentas de usuario. Contiene datos clave como preferencias de idioma, configuración de notificaciones y ajustes personalizados, facilitando la gestión integral de la experiencia del usuario. 

![](https://raw.githubusercontent.com/Lizandrxo/BaseD/main/Captu/MONGODB/ConfiCuenta.png)

### Coleccion EstadoReproducciones
La colección "EstadosReproducciones" sirve como un repositorio central que almacena información sobre el estado y el tiempo reproducido de películas o series. Contiene datos esenciales como el estado actual de la reproducción (pausado, en curso, finalizado) y la duración exacta del contenido visualizado.

![](https://github.com/Lizandrxo/BaseD/blob/main/Captu/MONGODB/EstadoReproduccion.png?raw=true)

# Comandos 
1. Encuentra todos los perfiles de usuario que han visto más de 10 veces la serie con el título "Stranger Things"

db.PerfilesUsuarios.find({
   "Peliculas.titulo": "Forrest Gump",
   "EstadisticasVisualizaciones": { $gt: 10 }
});

2. Obtén una lista de películas cuya duración sea superior a 2 horas y que estén disponibles en calidad 4K
   
   db.Peliculas.find({
   duracion: { $gt: 120 },
   calidad: "4k"});

   
3. Busca todos los perfiles de usuario que tengan una edad superior a 25 años y han marcado como favoritas al menos 5 películas de género "Ciencia Ficción".

db.PerfilesUsuarios.find({
   Edad: { $gt: 25 },
   "Favoritos.Genero": "Ciencia Ficción",
   "Favoritos": { $size: { $gte: 5 } }
});


4. Encuentra las series ordenadas por la cantidad total de visualizaciones en orden descendente.
   
db.Series.find().sort({ "Visualizaciones": -1 });

5. Obtén una lista de películas que han sido vistas por usuarios con una suscripción premium y que pertenezcan al género "Comedia".
db.Peliculas.find({
  "Suscripciones": "Premium",
  genero: "Comedia"
})

6. Busca todos los perfiles de usuario que han marcado como favorito al menos un episodio de la serie "Black Mirror".

db.PerfilesUsuarios.find({
   favoritos: "65bb18af8041e5ef809bb585" // id Black Mirror
});

7. Encuentra las películas que están disponibles en calidad HD y tienen una clasificación superior a 4.5 estrellas
db.Peliculas.find({
   calidad: "2K",
   clasificacion: "C+18"
   });

8. Obtén una lista de usuarios que han visto al menos 3 películas en los últimos 7 días
db.perfilesUsuarios.find({
  "peliculas_vistas.fecha_hora_visualizacion": { $gte: new Date("2023-07-04T01:21:30.000Z") },
  "peliculas_vistas.num_visualizaciones": { $gte: 3 }
})

9. Busca las series cuyo número de temporadas sea mayor a 5 y que tengan al menos 3 episodios disponibles para ver

db.Series.find({
   temporadas: { $gt: 5 },
   episodiosdisponibles: { $exists: true }
});

10.  Encuentra todos los perfiles de usuario que han dado una calificación de 5 estrellas a alguna película de género "Drama".

db.PerfilesUsuarios.find({
   "Valoraciones.puntuacion": 5,
   "Valoraciones.categoria": "Drama"
});


11. Obtén una lista de películas que no han sido vistas por ningún usuario hasta el momento.
db.Peliculas.aggregate([
   {
      $lookup: {
         from: "Visualizaciones",
         localField: "PeliculaSerieEventoID",
         foreignField: "PeliculaSerieEventoID",
         as: "vistas"
      }
   },
   {
      $match: {
         vistas: { $eq: [] }
      }
   }

]);

12. Busca todos los perfiles de usuario que han marcado como favoritas al menos 2 series de género "Fantasía".

db.perfilesUsuarios.find({
  "series_favoritas.genero": "Fantasía",
  "series_favoritas.num_favoritas": { $gte: 2 }
})

13. Encuentra las películas que fueron lanzadas después del año 2020 y tienen una duración inferior a 2 horas

db.Peliculas.find({
  anio_estreno: { $gt: 2020 },
  duracion: { $lt: 120 }
})

14. Obtén una lista de series ordenadas por la fecha de lanzamiento en orden ascendente

db.Series.find().sort({ fecha_lanzamiento: 1 })


15. Busca todos los perfiles de usuario que han visto al menos una película en los últimos 3 días y han dado una calificación superior a 3 estrellas

db.perfilesUsuarios.find({
  "peliculas_vistas.fecha_hora_visualizacion": { $gte: new Date("2024-01-28T00:00:00.000Z") },
  "peliculas_vistas.calificacion": { $gt: 3 }
})

16. Encuentra las series que contienen la palabra "Mystery" en su descripción

db.Series.find({
  sinopsis: { $regex: /Mystery/i }
})

17. Obtén una lista de películas ordenadas por la cantidad de veces que han sido marcadas como favoritas en orden descendente

db.Peliculas.find().sort({ "usuarios_favoritas.num_favoritas": -1 })

18. Busca todos los perfiles de usuario que han visto alguna película protagonizada por un actor específico.

db.PerfilesUsuarios.find({
  actores: "Bruce Willys"
})


19. Encuentra las series que tienen al menos 3 temporadas y han sido calificadas con un promedio superior a 4 estrellas

db.Series.find({
  num_temporadas: { $gte: 3 },
  calificacion_promedio: { $gt: 4 }
})

20. Obtén una lista de usuarios que tienen más de 5 películas marcadas como favoritas y han dado una calificación promedio superior a 4 estrellas

db.Series.find({
  temporadas: { $gte: 3 },
  calificacion: { $gt: 4 }
})

21. Busca las películas que contienen en su título la palabra "Action" y tienen una duración superior a 2 horas.
    
db.Peliculas.find({
  titulo:  "Action",
  duracion: { $gt: 120 }
})

22. Encuentra todos los perfiles de usuario que tienen una suscripción básica y han visto más de 2 películas en el último mes.


23. Obtén una lista de series que están disponibles en calidad 4K y han sido lanzadas en los últimos 2 años.


24. Busca las películas que tienen al menos 3 géneros asociados y contienen la palabra "Thriller" en alguno de ellos
db.Peliculas.find({
  "generos": { $exists: true, $not: { $size: 0, $size: 1 } },
  "generos.2": { $regex: "Thriller" }
})


25. Encuentra todos los perfiles de usuario que han dado una calificación superior a 4 estrellas a alguna película de género "Aventura".
