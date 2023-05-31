Realizaremos una Calculadora Basica con Condicionales  IF 


Algoritmo CalculadoraSimple
	Escribir "Ingresa Numero"
	Leer n1
	Escribir "Ingresa Numero"
	Leer n2
	Escribir "Ingresa operacion +,-,*,/"
	Leer operacion
	Si operacion = "+"  Entonces
		Imprimir "Suma de Operacines: " , n1  " y "  n2 
		Imprimir "suma: " , n1 + n2, Respuesta
	sino 
		si operacion = "-" Entonces
			Imprimir "Resta de Operacines: " , n1  " y "  n2 
			Imprimir "Resta: " , n1 - n2, Respuesta
		sino 
			si operacion = "*" Entonces
				Imprimir "Multiplicacion  de Operacines: " , n1  " y "  n2 
				Imprimir "Multiplicacion: " n1 * n2, Respuesta
			sino 
				si operacion = "/" Entonces
					Imprimir "Divicion  de Operacines: " , n1  " y "  n2 
					Imprimir "Divicion; " n1 / n2, Respuesta
				sino 
					Imprimir "Operacion Incorrecta"
				FinSi
			FinSi
		FinSi
	
		

	Fin Si
	
	
	
FinAlgoritmo
