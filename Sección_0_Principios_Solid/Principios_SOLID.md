# Principios SOLID

- * S: Single Responsability Principle (SRP)
- * O: Open/Closed Principle (OCP)
- * L: Liskov Subtitution Principle (LSP)
- * I: Interface Segregation Principle (ISP)
- * D: Dependency Inversion Principle (DIP)

`Estos 5 principios a la hora de estudiar codigo:`

- Crear un software eficaz: que cumple con su cometido y que sea robusto y estable
- Escribir un codigo limpio y flexible: ante los cambios que se pueden modificar facilmente segun su necesidad. Que sea reutilizable y mantenible
- Permitir escalabilidad: que acepte ser ampliado con nuevas funcionalidades de manera agil.

`DESARROLAR UN SOFTWARE DE CALIDAD`

### Acomplamiento

Se refiere al grado de interdependencia que tienen dos unidades de software entre si, entendiendo por unidad de software: Clase, subtipos, metodos, modulos, funciones, bibliotecas, etc.

`Si dos unidades son independientes de una de la otra decimos que estan "Desacoplados"`


### Cohesion

Es el grado en que elementos diferentes de un sistema permanecen unidos para alcanzar un mejor resultado que si trabajan por separados.

Es la forma de agrupar diversas unidades de software para crear una unidad mayor.

### Principio de Responsabilidad Unica

`A Class Should have one, and only one, reason to change`

La `S` se refiere a Simple Responsability Principle (SRP) segun este principio "Una Clase deberia tener una y solo una razón para cambiar". Lo que Robert C. Martin identifica como "Responsabilidad"

Es el principio mas importante y fundamental de SOLID muy sencillo de explicar, pero el mas dificil de seguir en la practica

### Principio Abierto/Cerrado

`You should able to extend a classred behavior without modifying it`

El segundo principio de SOLID lo formulo 'Bertrand Meyer' y dice: "Deberia ser capaz de extender el comportamiento de una clase, sin modificarlas"

La clase que usas deberian estar Abiertas para poder extenderse y cerradas para modificarse.

Es importante tener en cuenta el open/closed principle a la hora de desarrollar clases, librerias o frameworks

### Principio de Sustitución de Liskov

`Devived classes must be subtitutable for their base classes`

La `L` de solid alude al apellido de quien lo creo, "Barbara Liskov" y dice que "Las clases derivadas deben poder sustituirse por sus clases base".

Esto significa que los objetivos deben poder ser reemplazados por instancias de sus subtipos sin alterar el correcto funcionamiento del sistema a lo que es lo mismo: si en un programa utilizamos cierta clase, deberiamos poder usar cualquiera de sus subclases. Sin interferir en la funcionalidad.

Segun Robert C. Martin inclumplir el Liskov substitution implica violar tambien el principio de Abierto/Cerrado

### Principio de Segregación de la interfaz

`Make fine grained interfaces that are client specific`

En el cuarto principio de SOLID, el tio bobsugre:

"Haz interfaces que sean especificas para un tipo de cliente", es decir para finalidad concreta.

Es preferible contar con muchas interfaces que definen pocos metodos que tener una interface forzada a implementar muchos metodos a los que no dara uso.


### Principio de Inversión de Dependencias

`Depend on abstractions, not on concretions`

"Depende de abstracciones, no de clases concretas"

1.- Los metodos de alto nivel no deberian depender de un modulo de bajo nivel. Ambos deberian depender de abstracciones.

2.- El objetivo del dependecy inversion principle (DIP). Consiste en reducir las dependencias entre los modulos del codigo, es decir alcanzar un bajo acoplamiento de clases

### Conclusión

Los principios SOLID son eso: principios, es decir, buenas practicas que pueden ayudar a escribir un mejor codigo: mas limpio, mantenible y escalable.

No se trata de reglas, ni leyes, ni verdades absolutas, si no mas bien soluciones de sentido comun a problemas comunes. Son heuristicos, basados en la experiencia "Se ha observado que funcionan en muchos casos, pero no hay pruebas de que siempre funcionen, ni de que siempre se deban seguir"

SOLID nos ayuda a categorizar lo que es buen o mal codigo y es innegable que un codigo limpio tenderá mas a salir airoso del "Control de calidad de codigo"

### Consejo

Cuando estes revisando codigo, lleva la cuenta de cuantas veces por minuto sale de tu boca un WTF?

<img src="Code Quality Measurent.png" alt="Code Quality Measurent" />
