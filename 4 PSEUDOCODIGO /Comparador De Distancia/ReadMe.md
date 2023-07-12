// creamos un funcion en donde sumara los numeros que uno le ingrese y tiene que sumar positivo con positivo y negativo con negativo. ya que si es mas negativo dira falso, si no sera verdadero.

Funcion result <- compareDistances()
	Definir result Como Logico
	negativeNumber = 0;
	positiveNumber = 0;
	
	Para count<-1 Hasta 5 Con Paso 1 Hacer
		Escribir "escribe el numero:"
		leer num
		si num > 0 Entonces
			positiveNumber = positiveNumber + num
		sino 
			negativeNumber = negativeNumber + num
		FinSi
		result = positiveNumber > abs(negativeNumber )
	Fin Para
FinFuncion

Algoritmo exampleCompareDistances
	Imprimir compareDistances()
	
FinAlgoritmo
