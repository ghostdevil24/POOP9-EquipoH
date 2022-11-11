
# PATRONES DE DISEÑO

## Definicion
- Plantilla adaptable
- Descripciones de clases y objetos relacionados

## Elementos
- Nombre del patron
- Problema
- Solucion
- Consecuencias

## Antipatrones
- Guia para un pésimo diseño de software

## Ejemplos
- Lava Flow
- The god
- Golder Hammer
- Spaguetti code
- Fantasmas
- Reinventar la rueda

## Tipos
### Diseño estructurales
- Solucionan problemas de composición de clases y objetos
- Patrón Builder
- Patrón Prototype
- Patrón Singleton
#### Decorator
- Extiende la funcionalidad de un objeto de manera dinamica.
#### Adaper
- Transforma una interfaz de una clase en otra.
#### Facade
- Permite interactuar en forma centralizada con un subsistema de clases.
#### Proxy
- Permite proporcionar un sustituto o marcador de posición para otro objeto.
#### Bridge
- Permite dividir una clase grande en dos jerarquías separadas (abstracción e implementación).
#### Virtual Proxy
- Sugiere posponer la creación del objeto hasta que lo necesite.
#### Counting Proxy
- Sugiere encapsular la funcionalidad adicional en un objeto aparte referenciado como counting proxy.
#### Aggregate Enforcer
- Recomienda que cuando un objeto agregado es construido, debe ser creado completamente.
#### Object caché
- Se aplica cuando la construcción de un nuevo objeto es costoso en términos de procesamiento. El objeto en la memoria no se almacena por siempre.
#### Flyweight
- permite mantener más objetos dentro de la cantidad disponible de RAM compartiendo las partes comunes del estado entre varios objetos.

### Diseño de comportamiento
#### Patrón Iterator
#### Patrón Visitor
#### Patrón Command
#### Patrón Mediator
#### Patrón Memento
#### Patrón Observer
#### Patrón Interpreter
#### Patrón State 
#### Patrón Strategy
#### Patrón NULL object
#### Patrón Template Method
#### Patrón Object Authenticator
#### Common Attribute Registry

## Clasificación
### Diseño
#### Son patrones de un nivel de abstracción alto pero a un nivel de granularidad más fino.
- Esquema observador - observador

### Arquitectura
#### Son los esquemas primarios en la organización de un sistema de software
##### Esquema cliente - servidor
- Esta arquitectura consiste básicamente en un cliente que realiza peticiones a otro programa (el servidor) que le da respuesta.

##### Modelo Vista Controlador (MVC)
###### Es un estilo de arquitectura de software que separa los datos de una aplicación, la interfaz de usuario, y la lógica de control en tres componentes distintos.
###### Modelo
- Contiene una representación de los datos que maneja el sistema, su lógica de negocio, y sus mecanismos de persistencia.
###### Vista o Interfaz de usuario
- Compone la información que se envía al cliente y los mecanismos interacción con éste.
###### Controlador
- Actúa como intermediario entre el Modelo y la Vista, gestionando el flujo de información entre ellos.

### Elementales (idioms)
#### Son patrones directamente involucrados en la codificación, por lo tanto, son más simples y especificos al lenguaje.

<!--
        TEMA 6
    Arturo Rodriguez Rodriguez 
        Semestre 2023-1
            Grupo: 1
-->




