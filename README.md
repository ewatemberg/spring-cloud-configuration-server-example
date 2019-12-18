# Example Spring Cloud Configuration Server
Creación de un archivo de configuración Spring Cloud Config Server centralizado en Github

##Spring Cloud Config
Uno de los problemas comunes a los que nos enfrentamos es asegurarnos que la configuración de todos nuestros microservicios sea correcta y que pueda modificarse de una manera fácil y segura.
Para dar solución a este problema contamos con la ayuda del ecosistema Spring Cloud, el cual nos recomienda la utilización de un patrón denominado configuración distribuida. Este patrón resuelve el problema de la configuración de varios microservicios mediante la creación de un servidor de configuración, accesible por todos los microservicios y en el cual se encuentra la configuración de todos los elementos de nuestro sistema. Y cómo podemos poner en práctica dicho patrón? Pues mediante uno de los componentes integrados de la plataforma Spring Cloud, concretamente Spring Cloud Config.

### Related
* [Servicio de Registro y Descubrimiento basado en Eureka]()
* [Servicio Gateway Zuul]()

######Fuente:
[Miguel Doctor Yuste](https://medium.com/@migueldoctor/spring-cloud-series-spring-cloud-config-server-con-github-paso-a-paso-135d2b4aaf4c)