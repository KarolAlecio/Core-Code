Algoritmo opecarionRepetir
	Repetir
			Imprimir "ingrese cantidad 1"
			leer n1
			Imprimir "ingrese cantidad 2"
			leer n2
			Imprimir "ingrese operacion"
			leer op
			Si op == '+' | op == '-' | op == '*' | op == '/' Entonces
				Imprimir "Procesando:  " ConvertirATexto(n1)  op  ConvertirATexto(n2)
				segun op Hacer
					"+" : 
						Imprimir "Suma: " n1 + n2 
					"-" :
						Imprimir "Resta: " n1 - n2 
					"*" : 
						Imprimir "Multiplicacion: " n1 * n2 
					"/" :
						Imprimir "Divicion: " n1 / n2 
						
				FinSegun
			SiNo
				Imprimir "Operacion no valida"
			FinSi
			Imprimir "Desea continuar otra operacion: (Si/No)"
			leer continuar 

	Hasta Que  continuar == "no" 
