#Solución reversar string}

Lenguaje seleccionado: JavaScript

Definimos una función de nombre reversor que retornará la cadena invertida

mediante el método split() dividimos la cadena y devolvemos un arreglo con cada caracter que se encuentra en la cadena como elemento

al utilizar el método reverse() invertimos el orden de los elementos que forman el arreglo anteriormente entregado por el método split()

finalmente con el método join() unimos los elementos dentro del arreglo devuelto con reverse() y los devolvemos dentro de una cadena 

tanto en los métodos split() como join() usamos como parametros las comillas("") ya que al dejarlo vacio el split() devolverá en el arreglo la cadena completa como un elemento, por otro lado el join() devolverá como cadena los elemento del arreglo separados por comas

por ultimo definimos la variable cadena donde guardaremos el string que deseamos reversar

y llamamos a la funcion reversar() con el parametro definido anteriormente como cadena dentro de un console.log()
