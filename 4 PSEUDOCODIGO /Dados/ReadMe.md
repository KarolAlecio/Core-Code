Algoritmo Dados
	// se creara un codigo en donde, salgran 10 numero al azar
	// y si salen numeros iguales, dira los numeros son iguales.
	definir n1, n2 Como Entero
	Para contador<-1 Hasta 10 Con Paso 1 Hacer
		n1 = azar(6)
		n2 = azar(6)
		si n1 = n2 Entonces
			Imprimir n1, " " , n2, " Los numeros son iguales. "
		SiNo
			Imprimir n1, " " , n2
		FinSi
	Fin Para
FinAlgoritmo
