# **Define an algorithm that is able to convert temperatures from Celsius to Fahrenheit and viceversa.**
## Algoritmo para poder convertir temperaturas.
1.	Solicitar un valor de temperatura y guardarlo en variable T.
2.	Evaluar que el valor sea de tipo float, si el resultado es False regresar al paso 1, si el resultado es True podemos proseguir con los siguientes pasos.
3.	Preguntar si la temperatura dada es una temperatura en grados Celsius o Fahrenheit.
4.	Verificar si el resultado de la respuesta es “Celsius”, si el resultado es True realizar las siguientes instrucciones, si el resultado al verificar es un false entonces realizar el paso 5.
 * Realizar la operación (T × 9/5) + 32, y guardarlo en la variable de tipo float “Result”.
 * Imprimir str(Result) + “grados Fahrenheit”.
 * Fin del Algoritmo.
5.	Ya verificado que el resultado de la respuesta sea “Fahrenheit” realizar:
* Realizar la operación (T − 32) × 5/9, y guardarlo en la variable de tipo float “Result”.
* Imprimir str(Result) + “grados Celsius”.
* Fin del Algoritmo.
