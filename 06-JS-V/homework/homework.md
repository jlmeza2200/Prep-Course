## Instrucciones

---

1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

- `prototype`
- _Constructors_ (de Clases)

prototype: Todas los objetos en JS obtienen sus propiedades y métodos de proto y gracias a “prototype” logramos modificar el prototype de nuestros objetos. Por ejemplo, los arrays tienen el prototype Array, con sus métodos, que nos permiten usar .push, .splice, .pop, .foreach, entre otros. Todos esos métodos son llamados utilizando el proto del Array.

El constructor nos permitirá en las clases, crear una plantilla que nos servirá para reutilizar código, por ej, con ella podremos crear la clase Alumno con su constructor, en la cual podremos definir sus atributos nombre, apellido, dni, edad, materias. Con esa plantilla, luego podemos crear los alumnos que necesitemos con dicha información.
