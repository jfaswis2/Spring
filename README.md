# Java Spring Framework
![Opening logo](images/logo.jpg)

Debo aclarar que esto son solo apuntes de mi aprendizaje, no es ning煤n tipo de tutorial ni de curso, pero siempre son bienvenidos a leer mis notas.
## 馃摂 Spring 1
##  驴Qu茅 es Spring Framework?
Primero que todo, 驴Qu茅 es un framework? Pues un framework es una "Estructura predefinida" para construir algo completamente, desde el inicio hasta el final, y no tan solo la estructura si no tambien el conjunto de funcionalidades que tu vas a necesitar.馃槷

Y ahora si, Spring es un framework de c贸digo abierto para la creaci贸n de apliaciones empresariales, tiene una estructura modular y una gran flexibilidad para implementar diferentes tipos de arquitecturas seg煤n las necesidades de la aplicaci贸n.

![Spring_Runtime](images/springruntime.png)

##  Core Spring

Contenedor central: Realiza el trabajo de creador de Beans, lectura de archivos Config, manejo de propiedades y dependencias, uso del contexto como almacen de los Beans en memoria y con SpEL que nos permite manipular objetos en tiempo de ejecuci贸n.

Infraestructura: En este modulo se maneja todo lo referente a las transacciones, los login, a la seuridad, etc...

Acceso a datos: Nos permite acceder a datos con mucho menos codigo (JDBC) usando helper classes, nos permite acceder a datos utilizando POO y nos permite escribir menos codigo a la hora de hacer llamadas a nuestra base de datos.

Web/MVC: Trae con el 4 modulos(Servlet, Portlet, WebSocket, Web) que nos permitira el acceso web remoto, la programaci贸n distribuida, la integraci贸n de otras tecnolog铆as como JSF o Struts.

Pruebas: Nos va permitir hacer pruebas durante el desarrollo de nuestro programas.

##  Spring Container y Beans
Un contenedor crea objetos, los une, los configura y administra su ciclo de vida completamente. Los Beans son objetos que maneja el contendor de spring (Spring Container).
