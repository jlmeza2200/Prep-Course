# Homework: Javascript IV

## Instrucciones

---

1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

   - Objetos
   - Propiedades
   - Métodos
   - Bucle `for…in`
   - Notación de puntos vs notación de corchetes

Objetos: En programación, los objetos son la representación de una cosa de la vida real. Por ejemplo una casa, nosotros podemos crear un objeto llamado casa y en agregar propiedades y métodos. Al igual que un array, podemos crear dentro del objeto, arrays, otro objeto, y funciones (métodos). Pero a diferencia de los arrays, los objetos trabajan con el concepto de clave:valor

ej:
const casa = {
integrantes: ["Integrante Uno", "Integrante Dos", "Integrante Tres"],
habitaciones: 4,
colores: "Blanco, verde pastel y celeste",
activar_alarma: function(){
alert("Alarma Activada");
}
}

En el ejemplo anterior, el objeto casa tiene como pares clave:valor; integrantes con su array, habitaciones con el valor 4, colores con el string de colroes, y activar_alarma es un método, es decir una función que en este caso ejecuta un alert.

Hemos definido la variable casa y le asociamos un objeto. A las variables de este estilo, las denominamos propiedades (también se les suele llamar atributos) y son características propias de ese objeto.

Bucle for in: Es un for que nos permitirá recorrer el objeto con sus respectivos pares clave:valor. El bucle for normal no sirve para iterar un objeto. A diferencia del for clásico, en el for in debemos crear una variable dentro del (), y especificar la palabra reservada in y luego el nombre del objeto.

Ej:
for (let clave in casa) {
console.log(clave);
console.log(casa[clave]);
}

Notación de puntos vs notación de corchetes: Podemos llamar a los objetos con sus pares clave:valor a traves del nombre del objeto.clave o también podemos usar [], pero en este caso debemos colocar el nombre de la variable o indicar la clave como string.

Ej:

casa.integrantes;
casa["integrantes"];
casa[clave]; --> en el ejemplo del for in, usamos clave como variable let.
