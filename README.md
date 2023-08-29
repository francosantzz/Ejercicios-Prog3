# Ejercicios-Prog3
Prácticas de Programación con Spring Boot y Bases de Datos

Dentro de este repositorio se encuentran dos prácticas de programación que abordan la implementación de Spring Boot en conjunto con bases de datos. A continuación, te presento una breve descripción de cada práctica, así como los pasos necesarios para ponerlas en marcha.

Práctica 1

Descripción
La Práctica 1 consiste en una aplicación desarrollada con Spring Boot que ilustra cómo crear una entidad llamada "Persona" y almacenarla en una base de datos. Además, se demuestra cómo recuperar la información de esta entidad desde la base de datos y presentar sus detalles.

Pasos para Ejecutarla

Asegúrate de haber configurado una base de datos compatible con Spring Boot, como MySQL o H2. Puedes ajustar esta configuración en el archivo src/main/resources/application.properties.

Ejecuta la clase principal Ej1Application.java, ubicada en el paquete "ej1". Esto pondrá en marcha la aplicación Spring Boot.

La aplicación generará automáticamente una tabla en la base de datos para la entidad "Persona" y guardará una instancia con información como nombre, apellido y edad.

Posteriormente, se recuperará esta instancia de "Persona" y se mostrarán sus detalles en la consola.

Práctica 2

Descripción
La Práctica 2 es similar a la anterior, pero introduce un campo adicional llamado "Domicilio" en la entidad "Persona". Además de guardar y recuperar los detalles básicos de una persona, esta práctica demuestra cómo manejar un campo adicional.

Pasos para Ejecutarla

Asegúrate de haber configurado una base de datos compatible con Spring Boot, como MySQL o H2. Puedes ajustar esta configuración en el archivo src/main/resources/application.properties.

Ejecuta la clase principal Ej2Application.java, ubicada en el paquete "ej2". Esto iniciará la aplicación Spring Boot.

La aplicación creará automáticamente una tabla en la base de datos para la entidad "Persona" y guardará una instancia con información que incluye nombre, apellido, edad y domicilio.

Luego, se recuperará esta instancia de "Persona" y se mostrarán todos sus detalles en la consola.

Observación: Estas prácticas proporcionan ejemplos concretos de cómo utilizar Spring Boot para interactuar con bases de datos. Son ideales para familiarizarse con el desarrollo de aplicaciones backend que involucran la persistencia de datos.
