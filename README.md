# Arquitectura-Clean
Arquitectura Clean (Uncle Bob)

##Tarea Investigar más a detalle la arquitectura CLEAN (Uncle Bob)
___

Surge con la problemática que en la mayoría de los desarrollos en los cuales existe un framework, éste se encuentra con más código que lo representa, en lugar del problema que está resolviendo, la idea es centrarse en lo que tiene que hacer la aplicación como tal y es por ello que debemos pensar en el framework como el mecanismo de paso de mensajes hacia nuestro software.  

Lo único que nos dice (Uncle Bob) es que hay que respetar las reglas de dependencia: “El código fuente sólo puede apuntar hacia adentro“.

* _Entities:_ Son aquellos objetos que van a representar los actores importantes de la lógica de negocio de nuestra aplicación.
* _Use Cases:_ Están muy relacionados con las entidades y son los encargados de implementar lógica de negocio de nuestra aplicación, ya que van a orientar todas aquellas interacciones del flujo de datos y entidades dejando al framework fuera de todo esto.
* _Interface Adapters:_ Convierten los datos en el formato más conveniente para los casos de uso y entidades.
* _Frameworks and Drivers:_ Aquí es donde residen los detalles y todo ese conjunto de plataformas externas y herramientas como puede ser la UI, Web, DB, Devices, etc. 

![Sin titulo](https://erikcaffrey.github.io/content/images/2016/1/clean_archi.png)
