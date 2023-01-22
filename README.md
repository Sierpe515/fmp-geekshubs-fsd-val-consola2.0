#### fmp-geekshubs-fsd-val-consola

#Replica Steam Deck

***

#### Índice

1. [Cómo se lanza] (#como-se-lanza)
2. [¿Qué es?] (#que-es)
3. Manejo (#manejo)
4. Cómo se ha hecho (#como-se-ha-hecho)
5. Licencia (#licencia)
6. Sección de problemas conocidos (#seccion-de-bugs-conocidos)
7. Créditos (#creditos)

***
### Cómo se lanza

El lanzamiento de está que replica la videoconsola portátil Steam Deck es muy sencillo. Únicamente abre el archivo index.html en tu navegador o accede a ella a traves del enlace "https://sierpe515.github.io/fmp-geekshubs-fsd-val-consola/".

***

### ¿Qué es?

Se trata de una reproducción -salvando las diferencias- de la videoconsola portátil Steam Deck, realizada a través de HTML y CSS.
También cabe decir que este proyecto se ha desarrollado en un ámbito educativo con fines didácticos para la Academía GeeksHubs.
En dicho proyecto se nos pedía que replicasemos cualquier consola o hardware relacionado con el mundo de los videojuevos, para poner en práctica los conocimientos adquiridos. Especialmente los relacionados con el Layaout, tanto el flow como el grid.
Yo he elegido la Steam Deck en parte por su novedad, en parte por su complejidad.

![Rep Steam Deck](https://user-images.githubusercontent.com/121863208/213922069-437f4fa6-0aaa-4500-9605-a8a5ff915230.jpg)

***

### Manejo

Para usar la Steam Deck replicada sencillamente desliza el cursor sobre los elementos interactivos.
No se puede jugar con ella, pero se han integrado elementos :Hover para que respondan al movimiento del ratón cuando se pasa el ratón sobre estos.

### Cómo se ha hecho

La web se ha desarrollado únicamente utilizando las tecnologías de HTML y CSS.
En HTML se ha dado forma a la estructura básica de contenedores y en CSS se les ha dado estilo.
Se han combinado el flow y el grid para colocar los contenedores (div) en el lugar deseado.
También se han investigado y aplicado diversas propiedades y valores de CSS para tratar de dar un aspecto más realista al objeto, tales como box-shadow, background-image (linear gradient, radial gradient...), border o border-radius.
Uno de los momentos críticos del proyecto fue la inserción de las agarraderas laterales, para las que hubo que describir una serie de curvas, a traves de la propiedad border-radius, que antes de alcanzar el resultado final, llegaron a lucir un aspecto deplorable.
Otro de las fases de mayor dificultad fue la realización de los botones, para cuyo resultado hubo que rotar un div, para que en lugar de trabajar sobre un cuadrado, hacerlo sobre un rombo. Y, posteriormente, volver a rotar a la inversa los elementos de su interior.
De la misma manera se han aplicado elementos :hover para que la consola reaccione a la interacción con el cursor.
Las únicas imagenes utilizadas en la realización de la consola son las pertenecientes a los iconos de los botones, pause, menú y select.

***

### Licencia

La licencia utilizada es una Creative Commons Legal Code.

### Sección de problemas conocidos

El principal escoyo que no se ha podido solucionar en la versión actual de la consola es la interacción del :hover con la cruceta.
Hasta donde alcanzan mis conocimientos, no he conseguido que un :hover alojado en en div interactue con elementos de otros divs. Así pues, al presionar cualquiera de las direcciones de la cruceta, el :hover interactua únicamente con su div, en lugar de hacerlo con todos los que componen la cruceta. Cinco.
También me hubiera custado que al presionar un botón, por ejemplo el de Steam, se encendiese la pantalla. Pero nos enfrentamos de nuevo al mismo problema. Por esta razón únicamente se ha utilizado un .hover para activar la pantalla al pasar el cursor sobre la misma.

***

### Créditos

Este proyecto ha sido realizado únicamente por mí, Fernando Martínez Pardo, estudiante de la edición de Enero de 2023 de GeeksHubs Academy.
