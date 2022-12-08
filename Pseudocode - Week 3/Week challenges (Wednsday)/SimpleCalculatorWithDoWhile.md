### For this challenge we are going to use the simple calculator that we made in the challenge 02 but now adding the functionality to perform a calculation again without finishing the program. The program should ask us if we want to use another operation and if the user answers yes then we can perform a new operation. To solve this challenge remember to use Do while (Repetir Hasta Que).

## Code

```
Algoritmo CalculadoraWhile
	YesNo = "Yes"
	Repetir
		Imprimir "Bienvenido a la calculadora Do While"
		Imprimir "Ingrese el primer número: "
		Leer PrimerNumero
		Imprimir "Ingrese el segundo número: "
		Leer SegundoNumero
		Imprimir "Operaciones disponibles"
		Imprimir "+"
		Imprimir "-"
		Imprimir "*"
		Imprimir "/"
		Leer  Option
		Si Option == "+"
			Imprimir "Procesando: "+ConvertirATexto(PrimerNumero)+" + "+ConvertirATexto(SegundoNumero)
			Imprimir "Resultado: "+ConvertirATexto(PrimerNumero+SegundoNumero)
		FinSi
		Si Option == "-"
			Imprimir "Procesando: "+ConvertirATexto(PrimerNumero)+" - "+ConvertirATexto(SegundoNumero)
			Imprimir "Resultado: "+ConvertirATexto(PrimerNumero-SegundoNumero)
		FinSi
		Si Option == "*"
			Imprimir "Procesando: "+ConvertirATexto(PrimerNumero)+" * "+ConvertirATexto(SegundoNumero)
			Imprimir "Resultado: "+ConvertirATexto(PrimerNumero*SegundoNumero)
		FinSi
		Si Option == "/"
			Imprimir "Procesando: "+ConvertirATexto(PrimerNumero)+" / "+ConvertirATexto(SegundoNumero)
			Imprimir "Resultado: "+ConvertirATexto(PrimerNumero/SegundoNumero)
		FinSi
		Imprimir "Desea realizar otra operación?"
		Imprimir "(Yes/No)"
		Leer YesNo
	Hasta Que YesNo == "No" | YesNo=="no"
FinAlgoritmo
```

## Screenshot of Code

![image](https://user-images.githubusercontent.com/98846377/206335560-7b1441a7-d0b9-4bb3-bb1d-1f94e631a8af.png)

## Output

![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/98846377/206336002-6000f004-4133-4dbc-843c-2c7f8a92a220.gif)
