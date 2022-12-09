### For this challenge we are going to print numbers in ascending or descending order. The user must enter a number, then he must enter if he wants to print the numbers in ascending or descending order. If the user chooses ascending, the numbers will be printed from the number 0 to the number entered, otherwise the numbers will be printed descending from the number entered to the number 0.To solve this challenge remember to use the For(Para) loop.

## Code 

``` 
Algoritmo AscendingNDescending
	Imprimir "Bienvenido a números en orden Ascendente y Descendente"
	Imprimir "Ingrese un número:"
	Leer num
	Imprimir "Elija la opciones que desee:"
	Imprimir "1. Orden Ascendente"
	Imprimir "2. Orden Descendente"
	Leer option
	Si option ==1
		Para i<-0 Hasta num Con Paso 1 Hacer
			Imprimir i 
		Fin Para
	FinSi
	Si option ==2
		Para i<-num Hasta 0 Con Paso -1 Hacer
			Imprimir i 
		Fin Para
	FinSi
FinAlgoritmo
```

## Screenshot of Code

![image](https://user-images.githubusercontent.com/98846377/206597263-6939d7c8-d6d7-4211-b3d5-95c12a6f2460.png)

## Output

![ezgif com-gif-maker](https://user-images.githubusercontent.com/98846377/206597931-b705274b-f879-4d3b-85a4-25313fd34d2a.gif)

