## Instrucciones

---

1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

- Funciones Callback: Es una función que se utiliza como parámetro de otra función. Son muy utilizadas en Js, muchos de los métodos usados utiizan callbakcs, por ejemplo foreach, map, reduce, entre otros.

Ejemplo de uso de callback;

function firstLetter(elemento) {
return elemento[0] === "a";
}

const result = array.filter(firstLetter);

En el ejemplo, podemos ver como el método filter que se aplica al array, recibe como callback la función firstLetter.
