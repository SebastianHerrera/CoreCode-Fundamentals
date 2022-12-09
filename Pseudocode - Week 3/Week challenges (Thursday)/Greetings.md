### For this challenge, you need to create a program that prints a greeting based on an hour entered. The program should do the following:

- Print Buenos dias! if the hour is from 0 to 12
- Print Buenas tardes! if the hour is from 13 to 18
- Print Buenas noches! if the hour is from 19 to 23
- Ask the user if he wants to perform another greeting. If the answer is Si, the program must start again.
- At the end of the program, print out the number of times the program has greeted.

## Code

```
Algoritmo Greetings
	YesNo = "Yes"
	rep = 0
	Repetir
		Imprimir "Bienvenido a Greetings"
		Imprimir "Ingrese la hora que desee (0-23): "
		Leer time
		Si time >= 0 & time <=12
			Imprimir "Buenos días usuario!"
			rep = rep +1
		FinSi
		Si time >= 13 & time <=18
			Imprimir "Buenas tardes usuario!"
			rep = rep +1
		FinSi
		Si time >= 19 & time <=23
			Imprimir "Buenas noches usuario!"
			rep = rep +1
		FinSi
		Imprimir "Desea realizar otra operación?"
		Imprimir "(Yes/No)"
		Leer YesNo
	Hasta Que YesNo == "No" | YesNo=="no"
	Imprimir "Se dieron "+ConvertirATexto(rep)+" greetings." 
FinAlgoritmo
```

## Screenshot of Code

![image](https://user-images.githubusercontent.com/98846377/206599265-51771149-772f-4f4b-9925-2454407af48b.png)

## Output

![ezgif com-gif-maker (5)](https://user-images.githubusercontent.com/98846377/206599432-0fb1bb57-1e0c-4103-88b7-7518a3602217.gif)
