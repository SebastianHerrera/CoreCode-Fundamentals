### For this challenge you will create a program with multiple options using Switch (Segun), the options available are the following:

### Sum two numbers
### Print the day of the week given the day number
### Print the length of a given text
### This program must have a start menu where the user must select one of the previously described options. When the user selects each of the options, the program will perform the following:

### Sum. The user enters two numbers and the result of the sum of both is printed
### Print day of the week. The user enters a day of the week using numbers and the name of the day must be printed. For example, if the number 1 is entered, the program prints the text Lunes.
### Calculate text length. The user enters a text and the length of the text should be printed. I was able to use the Pseint Longitud function to get the length.
### When the user enters an incorrect option, a message should be printed saying that the option is not available.

## Code
```PSeInt
Algoritmo MultiOption
	Imprimir "Welcome to the Multi Option Program"
	Imprimir "Opciones: "
	Imprimir "1. Suma de dos números"
	Imprimir "2. Imprimir el día de la semana dando un número"
	Imprimir "3. Imprimir el largo de un texto"
	Leer operation
		Si operation == "1" | operation == "2" | operation == "3" Entonces
			Segun operation Hacer
				"1":
					Imprimir "Ingrese el primer número: "
					Leer PrimerNumero
					Imprimir "Ingrese el segundo número: "
					Leer SegundoNumero
					Imprimir "El resultado es: " + ConvertirATexto(PrimerNumero+SegundoNumero)
				"2":
					Imprimir "Ingrese el número del día que desea conocer: "
					Leer dia
					Si dia == 1 | dia == 2 | dia == 3 | dia ==4 | dia ==5 | dia==6 | dia==7 Entonces
						Segun dia Hacer
							1:
								Imprimir "Lunes"
							2:
								Imprimir "Martes"
							3:
								Imprimir "Miércoles"
							4:
								Imprimir "Jueves"
							5:
								Imprimir "Viernes"
							6:
								Imprimir "Sábado"
							7:
								Imprimir "Domingo"
						FinSegun
					SiNo
						Imprimir "Día no existente"
					FinSi
				"3":
					Imprimir "Ingrese la cadena de texto deseada: "
					Leer text
					Imprimir "El largo de su texto es: "+ConvertirATexto(Longitud(text))
			Fin Segun
		SiNo
			Imprimir "La operación no es valida"
		FinSi
	
FinAlgoritmo
```

## Output

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/98846377/206057318-be99371a-02f3-485f-877b-6978f434c7d4.gif)
