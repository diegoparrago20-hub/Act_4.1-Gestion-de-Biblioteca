# Act_4.1-Gestion-de-Biblioteca
Proyecto desarrollado en Java utilizando programación orientada a objetos, herencia, genéricos y polimorfismo para administrar diferentes tipos de publicaciones mediante una biblioteca basada en arreglos.

## Equipo #2
CONTRERAS RODRIGUEZ JANIS ISABEL

LIRA DOMINGUEZ BRYANT

PARRA GONZALEZ DIEGO ALBERTO

# Objetivo
Desarrollar una aplicación que permita administrar diferentes tipos de publicaciones, como libros, revistas y artículos, utilizando una clase genérica que almacena objetos de tipo Trabajo y sus subclases.

# Tecnologías utilizadas
Java
Apache NetBeans
Java Swing
Genéricos y herencia 

# Características
El programa permite realizar las siguientes operaciones:

*Agregar:* registrar libros, revistas y artículos.

*Consultar:* buscar una publicación mediante su posición.

*Mostrar todos:* visualizar las publicaciones almacenadas.

*Eliminar:* quitar una publicación de una posición específica.

*Vaciar biblioteca:* eliminar todos los elementos almacenados.

*Validaciones:* comprobar posiciones válidas y campos obligatorios.

#Estructura del proyecto
*Trabajo:* clase base que contiene los atributos generales de las publicaciones: título, autor y año de publicación.

*Libro:* subclase de Trabajo que agrega el número de páginas.

*Revista:* subclase de Trabajo que agrega el número de edición.

*Articulo:* subclase de Trabajo que agrega el nombre de la conferencia.

*BibliotecaGenericaArreglo:* clase genérica que administra las publicaciones mediante un arreglo.

*Interfaz gráfica:* permite ingresar datos y ejecutar las operaciones de la biblioteca.

# Interfaz gráfica
La aplicación cuenta con una interfaz desarrollada en Java Swing que permite seleccionar el tipo de publicación, ingresar sus datos generales y específicos, y ejecutar las diferentes operaciones de la biblioteca.
