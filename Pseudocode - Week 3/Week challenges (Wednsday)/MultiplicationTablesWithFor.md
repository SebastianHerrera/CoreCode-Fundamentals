### For this challenge you will create a program to calculate the multiplication tables for a given number using the For(Para) loop. The user must enter a number and then the multiplication table for the number must be printed.

## Code

```
Algoritmo MultiplicationTables
	Imprimir "Bienvenido a la calculadora de las tablas de multiplicación"
	Leer num
	Imprimir "Tabla de multiplicar del "+ConvertirATexto(num)
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		Imprimir ConvertirATexto(num) ' *  ' + ConvertirATexto(i) + ' = ' ConvertirATexto(num * i) 
	Fin Para
FinAlgoritmo
```

## Screenshot of Code

![image](https://user-images.githubusercontent.com/98846377/206332802-718956d7-164a-40fb-8b79-aa21a91fef0a.png)

##Output

![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/98846377/206333152-80219d81-ecc4-40c4-966a-9d1c5c3c2c5e.gif)
