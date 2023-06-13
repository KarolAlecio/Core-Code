Funcion  suma (n1, n2 )
	Imprimir "el resultado de la suma es: "
	Imprimir  n1 + n2
FinFuncion

Funcion resta (n1, n2 )
		Imprimir "el resultado de la resta es: "
		Imprimir  n1 - n2
FinFuncion
Funcion  multiplicacion (n1, n2)
		Imprimir "el resultado de la multiplicacion es: "
		Imprimir  n1 * n2
FinFuncion

Funcion divicion ( n1, n2 )
	Imprimir "el resultado de la divicion es: "
	Imprimir  n1 / n2
FinFuncion


Algoritmo ejemploFunciones
	Escribir "ingresa la operacion: "
	leer operacion
	Imprimir "ingresa numero"
	leer n1
	Imprimir "ingresa numero"
	leer n2
	Segun operacion Hacer
		"suma" : 
			  suma(n1, n2)
		"resta" : 
			resta(n1, n2)
		"multiplicacion" : 
			multiplicacion(n1, n2)
		"divicion" : 
			divicion(n1, n2)
	FinSegun
	
FinAlgoritmo
