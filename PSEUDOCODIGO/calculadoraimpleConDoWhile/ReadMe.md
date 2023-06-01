Algoritmo calculadoraimpleConDoWhile
	Imprimir 'Ingrese primer numero'
	Leer n1
	Imprimir 'Ingrese segundo numero'
	Leer n2
	Imprimir 'Ingrese una operación: +,-,*,/'
	Leer op
	
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
	Imprimir "Desea continuar con la otra"
	leer continuar 
	
	Mientras continuar Hacer
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
	Fin Mientras
FinAlgoritmo



