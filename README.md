# Guia5_POO



## Resumen 
En general, una clase abstracta es aquella que modela un concepto abstracto. Por ejemplo, la clase Animal agrupa todos los atributos y métodos comunes a todos los animales, de tal forma que las clases Gato ̧ Perro y Tiburón ̧ heredaron de ella; en sí misma la clase Animal no representa a ningún animal en concreto, por lo que esta clase sería abstracta. Las clases abstractas suelen marcarse con la palabra clave abstracta. Al marcar una clase como abstracta, no será posible crear objetos de la misma. En general, para poder usar una clase abstracta, se debe crear una clase que herede de ella. Las clases abstractas pueden contener métodos abstractos, los cuales se marcan también con la palabra abstracta. Un método abstracto solo se declara en una clase abstracta, pero no se implementa. Las clases concretas que heredan de la clase abstracta, deben implementar los métodos abstractos




## Introducción, sesión 1 
### Estos ejercicios se deben solucionar en lenguaje Java.

1. Revisar y comprender los requerimientos de la guía de laboratorio. Pedir al profesor las aclaraciones del caso:
2. Para el desarrollo de todo el laboratorio puede emplear la librería Math de java.
3. Cree un nuevo proyecto llamado Figuras. Como ayuda puede descargar el código publicado por el docente en aula del curso.
4. Implemente dentro del proyecto Figuras el siguiente modelo de clase
5. No olvide agregar en todas las clases los constructores correspondientes y los métodos set y get de las propiedades; declare los atributos de la clase abstracta Figura como protected.
6. Note que el Cuadrilátero y el Triángulo tienen de 4 y 3 vértices representados en puntos respectivamente. Declare estos atributos como protected.


![image](https://user-images.githubusercontent.com/124604196/234066801-950a6b5a-2bbd-4939-babf-983737868824.png)
![image](https://user-images.githubusercontent.com/124604196/233872347-0953dfd1-80a0-46c7-94b5-c7c2604f9bdb.png)





## Preguntas orientadoras
¿Cuáles fueron los aprendizajes obtenidos al realizar esta guía?, lista como mínimo 3 aprendizajes y relaciónelos con su futuro quehacer profesional.

a. Aplicar la herencia a un determinado problema que fue el programa que resolvimos, conociendo mejor su definición.  
b. Por medio de la abstracción, organizar las ideas para construir el software que realice alguna acción implementando el paradigma POO.
c. Conocer los tipos de herencia lo cual nos permite que la herencia hace posible conceptualizar nuevas clases basadas en las existentes con el fin de reutilizar el código, lo que da como resultado una jerarquía de clases dentro de la aplicación.
d. Estos aprendizajes nos ayudan en nuestra carrera profesional ya que nos abre la mente para solucionar los problemas propuestos en la actividad fortaleciendo la creatividad y la abstracción. 

¿Dónde presentó mayor dificultad resolviendo la guía? y ¿cómo lo resolvieron? ¿Cuáles fueron las estrategias de solución?

a. Se nos presentó dificultades a la hora del código ya que no fue un proyecto que nosotros iniciamos, fue un proyecto que ya estaba y tocaba ver su funcionamiento y los posibles errores que este tenía, los cuales eran difíciles de visualizar.
b. Modificaciones en el código fueron difíciles de manejar, ya que cuando se realizaba algún cambio aparecen varios errores en el código, lo que hacía que no funcionara de manera correcta.




## Parte 3


1) In software engineering, abstraction refers to the process of simplifying complex systems by isolating their essential features while suppressing details that are not necessary for understanding or manipulating the system. Abstraction is a fundamental concept in software engineering, as it allows developers to create software systems that are more modular, easier to understand, and easier to maintain.

There are several types of abstractions that are commonly used in software engineering, including:

Data Abstraction: Data abstraction is the process of hiding implementation details of data types by providing a simplified interface for manipulating them. This allows programmers to use data structures without worrying about how they are implemented.

Procedural Abstraction: Procedural abstraction is the process of hiding implementation details of functions or procedures by providing a simplified interface for calling them. This allows programmers to use functions without worrying about how they are implemented.

Control Abstraction: Control abstraction is the process of hiding implementation details of control structures (such as loops or conditionals) by providing a simplified interface for using them. This allows programmers to use control structures without worrying about how they are implemented.

Object-oriented Abstraction: Object-oriented abstraction is the process of modeling a system as a set of interacting objects, each with its own state and behavior. This allows programmers to use objects without worrying about how they are implemented.



2) In Java, both abstract classes and interfaces are used to achieve abstraction and provide a way to define common behaviors and attributes for related classes. However, there are some key differences between the two:

Method Implementation: One of the main differences between abstract classes and interfaces is that abstract classes can contain both abstract and non-abstract methods, while interfaces can only contain abstract methods. An abstract method is a method without any implementation, which must be overridden in the concrete subclass.

Multiple Inheritance: Java allows a class to inherit from only one class, but it can implement multiple interfaces. This means that a class can inherit from an abstract class and implement one or more interfaces, but it cannot inherit from multiple abstract classes.

Access Modifiers: Abstract classes can have any access modifier (public, protected, private) for their members, while all members of an interface are implicitly public.

Constructors: An abstract class can have constructors, while interfaces cannot have constructors.

Variables: An abstract class can have instance variables, while interfaces cannot have instance variables.

Purpose: Abstract classes are used to define common behaviors and attributes for related classes, while interfaces are used to define a contract that classes must follow in order to implement certain behaviors.



4) In the context of web services, an interface is a contract that defines the operations or methods that a service provides to its clients. The interface describes the input and output parameters for each operation, as well as any preconditions and postconditions that the service requires.

Similarly, a web service is a software system designed to support interoperable machine-to-machine interaction over a network. Web services are built on top of standard web technologies such as HTTP, XML, and SOAP, and they expose their functionality through interfaces that can be accessed by remote clients.

In the context of web services, the interface is typically defined using a standard language such as WSDL (Web Services Description Language) or REST (Representational State Transfer). These languages provide a standard way to describe the interface of a web service, including the input and output parameters for each operation, the protocol bindings, and the message format.

By defining a standard interface, web services can be accessed by clients written in different programming languages and running on different platforms. This allows for interoperability between different systems and applications, making it possible for them to communicate and exchange data seamlessly.


## Video
https://youtu.be/CoUO5aZ1hTc
