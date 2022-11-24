# **Design an algorithm to calculate the volume of a pyramid, a cube and a sphere.**

## Diseñar un algoritmo para poder calcular el volumen de una pirámide, un cubo y una esfera.

1. Imprimir en pantalla las opciones "1. Piramide, 2. Cubo, 3. Esfera".
2. Recibir un input.
3. Verificar que el dato sea de tipo int y que el número se encuentra en un rango de 1 a 3.
4. Si la respuesta es "1" realizar los siguientes pasos, de lo contrario seguir al paso 5.
  * Pedir el valor de la base, este debe ser de tipo int, guardarlo en variable "b".
  * Pedir el valor del largo, este debe ser de tipo int, guardarlo en variable "a".
  * Pedir el valor de la altura, este debe ser de tipo int, guardarlo en variable "h".
  * Realizar la operación [(1/3) x b x a x h] y guardarlo en la variable de tipo int V.
  * Imprimir el valor de la variable V.
5. Si la respuesta es "2" realizar los siguientes pasos, de lo contrario seguir al paso 6.
  * Pedir el valor de la lado, este debe ser de tipo int, guardarlo en variable "l".
  * Realizar la operación (l x l x l) y guardarlo en la variable de tipo int V.
  * Imprimir el valor de la variable V.
6.  Si la respuesta es "3" realizar los siguientes pasos, de lo contrario seguir al paso 7.
  * Pedir el valor del radio, este debe ser de tipo int, guardarlo en variable "r".
  * Realizar la operación [4/3 x π x (r^3)] y guardarlo en la variable de tipo int V.
  * Imprimir el valor de la variable V.
7. Indicar que la entrada no es correcta, no existe ninguna opción que corresponda a la entrada obtenida.
