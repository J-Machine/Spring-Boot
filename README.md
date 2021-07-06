# Implementar una página web (HTML) con funciones Javascript para realizar llamadas de tipo Ajax a los Servicios Web (RESTFul Spring) creados en el Laboratorio 5 (https://developer.ibm.com/es/tutorials/j-spring-boot-basics-perry/) utilizando el método $.ajax() de jQuery.

## Pre-requisitos:

·        Eclipse.

·        Java – JDK8 o superior. 

·        Descargar la biblioteca jQuery: https://jquery.com/download/

## Tareas de Desarrollo

1.      Crear una página web (HTML, Javascript) con enlaces para poder registrar y visualizar categorías (CRUD de Category) – 2 puntos.

2.      Crear una pagina HTML para visualizar las categorías disponibles en formato tabla (id, name, description) – 3 puntos.

a.      url servicio: /CategoryRestService/FindAll

3.      Crear un formulario HTML para el registro de Category (name, description) – 3 puntos.

a.      url servicio: /CategoryRestService/Add

## Recomendaciones:

·        Utilizar como ejemplo: https://www.w3schools.com/jquery/tryit.asp?filename=tryjquery_ajax_ajax

·        Habilitar la extensión “Developer Tools” o F!2 del browser que será usando para probar las llamadas Ajax.

·        Usar el método console.log(result) para visualizar el retorno de los Servicios Web.

·        Anotar con @CrossOrigin(origins = "*") los Controllers del Laboratorio 4

## Entregable: repositorio GitHub
