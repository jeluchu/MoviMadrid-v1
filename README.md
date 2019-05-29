# MoviMadrid
CFGS Desarrollo de Aplicaciones Multiplataforma (DAM) - App Android para facilitar a los usuarios la información de Madrid Central, además de mostrar la contaminación y la búsqueda del distintivo ambiental

![Imagen de portada](https://github.com/Jeluchu/MoviMadrid/blob/master/images/init.png)

## Antecedentes

Se realizó una tormenta de ideas en la que expusimos varias ideas para el proyecto, y la que nos convenció más fue el tema de **Madrid Central**. Al inicio, no existía ninguna otra aplicación móvil similar que reuniera características semejantes.

No obstante, en el mes de diciembre aparecieron dos aplicaciones que se asemejaban bastante a nuestra idea. Una de ellas se puede encontrar en la Play Store bajo el nombre de “Madrid Central Información” y la otra desapareció de la propia Play Store tan solo unos meses después.

Todo esto fue pensado para **facilitar la información a todos los usuarios de la Comunidad de Madrid**, ofreciendo diversas características para que los ciudadanos y ciudadanas, puedan disfrutar y planear sus viajes por la ciudad de manera sencilla.

## ¿Qué es MoviMadrid?

MoviMadrid ha nacido como **proyecto final del CFGS Desarrollo de Aplicaciones Multiplataforma**, en el cual queremos facilitar al usuario los datos de contaminación y sus diferentes escenarios activos dentro de la Comunidad de Madrid.

Además de esas características también tendrá la posibilidad de introducir su matrícula para poder averiguar qué tipo de distintivo ambiental tiene su vehículo debido a la implantación de Madrid Central.

El servicio del mapa junto a la navegación se realiza con la idea de que al aproximarse a la zona limitada te salte un aviso para prevenirte en caso de no tener distintivo.

## Funciones y características

Cuando se pensó en realizar MoviMadrid como proyecto, **se planteó desarrollar una aplicación que permitiera a los usuarios mantenerse informados sobre los límites y las posiciones de las cámaras de vigilancia de acceso a Madrid Central, el distintivo ambiental que le corresponde a sus vehículos, el escenario de contaminación activo y la mayor cantidad de radares de tráfico posible**.

Poco a poco **la idea fue sufriendo modificaciones y se pensó en implementar otras funcionalidades** que ampliasen la experiencia del usuario al utilizar MoviMadrid y que además sirvieran para diferenciarla de otras aplicaciones parecidas que pudieran surgir y de las que ya existían.

Por ello se implementó la visualización de imágenes de las cámaras de tráfico, rutas en bicicleta, la localización de los puestos de alquiler de BiciMad y también la localización de los parkings públicos municipales, entre otras.

### Noticias
Pantalla inicial de la aplicación en la que se muestran las noticias de todos los distritos de Madrid (noticias generales, eventos, etc), además se cuentan con las redes sociales del Ayuntamiento de Madrid (Facebook y Twitter).

### Matrículas
El usuario podrá comprobar si su vehículo dispone de distintivo ambiental para saber cuál le corresponde y las restricciones que esto conlleva.

### Contaminación
Observación del escenario activo en el día actual y sus restrincciones, además desde la propia app recomendamos el uso del transporte público y taxi.

### Mapa y navegación
Mapa en el que podrás consultar los límites de Madrid Central, la localización de  
las cámaras de vigilancia de dicha zona, además de rutas, parkings, etc. También gracias a los permisos de ubicación el dispositivo te avisará si te encuentras cerca de alguna de las cámaras enviándote una notificación. Se cuenta con un navegador integrado para generar rutas según el tráfico o el vehículo de transporte que utilices.

### Cámaras de tráfico
Visualización de las cámaras de tráfico de la ciudad de Madrid a tiempo real. De esa manera el usuario podrá ver si hay mucho tráfico o si ha ocurrido un accidente para poder elegir otra ruta alternativa.

### Galería
Información relevante para el usuario en la que podrá ampliar su información acerca de Madrid Central o alguna infografía del Ayuntamiento de Madrid sobre los protocolos, salidas gastronómicas, etc.

### Mi Garage
Tras realizar una búsqueda de tu vehículo en el apartado de matrículas, se guardará automáticamente tu vehículo con su respectivo distintivo en tu nube personal, además podrás entrar en tu garaje para añadir más vehículos sin necesidad  
de realizar una búsqueda, de ese modo podrás guardarlo con un nombre personalizado.

### Ajustes
En el apartado de ajustes podrás encontrar tu perfil, en el que podrás recuperar la contraseña en caso de perderla, cerrar sesión o acceder a tu garaje personal. También estarán los agradecimientos por parte del equipo de desarrollo de la aplicación a aquellas personas que han ayudado o aportado su granito de arena durante el proceso del proyecto.

La información de la aplicación incluyendo el número de versión y las librerías de software libre estarán en el apartado de “Sobre Información”, podrás contactar con el equipo pidiendo ayuda (consultas, incidencias, etc), invitar a un amigo compartiendo directamente el enlace de descarga mediante redes sociales, o opinar la aplicación desde la Play Store.

## Versiones de la aplicación

### MoviMadrid LITE
Es una versión gratuita de la aplicación en la que queremos facilitar toda la información de la contaminación y Madrid Central para todos los ciudadanos y ciudadanas de la Comunidad de Madrid. De ese modo podréis ver cuál es vuestro distintivo medioambiental y ver los límites de Madrid Central además de comprobar las cámaras que hay por la zona.

[![Get it on Google Play](https://play.google.com/intl/en_us/badges/images/badge_new.png)](https://play.google.com/store/apps/details?id=com.jeluchu.movimadridlite)

### MoviMadrid PRO
Esta versión tiene un precio simbólico para apoyar el tiempo de desarrollo y a sus desarrolladores para poder añadir nuevas funciones y características a la app. Esta versión contará con todas las opciones de la versión gratuita además de tener las cámaras de tráfico, ver galería de infografías, rutas ciclistas, parkings, radares y mucho más.

[![Get it on Google Play](https://play.google.com/intl/en_us/badges/images/badge_new.png)](https://play.google.com/store/apps/details?id=com.jeluchu.movimadridlite)

## Tiempos de desarrollo
Durante el primer mes del proyecto comenzamos a organizar las tareas que realizaría cada miembro del equipo y a estimar que partes de la aplicación llevarían más trabajo.

A lo largo del desarrollo fuimos encontrando errores o problemas que se fueron solucionando poco a poco pero que requirieron más esfuerzo, por ejemplo para recoger las matrículas tuvimos que realizar una API montada en un servidor, al igual que con la contaminación hubo que montar una base

de datos para poder comparar la información recogida desde los distintos puntos que recogen la información de la calidad del aire en Madrid.

![Imagen de tiempo desarrollo](https://github.com/Jeluchu/MoviMadrid/blob/master/images/time.png)

# INCIDENCIAS
Si tienes cualquier problema ejecutando la aplicación no dudes en crear una **"Issue"** para que podamos revisar tu incidencia o consulta y corregir los problemas para futuras actualizaciones de la aplicación. Si quieres hablar con nosotros de una forma más personal no dudes en ponerte en contacto por e-mail a: infomovimadrid@gmail.com
