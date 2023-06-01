Realizaremos la Condicional Segun, para relizar Opciones Multiples.
Algoritmo OpcionMultiple
	Imprimir "Multi Opcional"
	Imprimir "1. SUMA"
	Imprimir "2. DIA DE LA SEMANA"
	Imprimir "3. CALCULAR LONGITUD DE TEXTO"
	Imprimir "Ingrese Opcion: "
	Leer i
	Segun i Hacer
		1:
		 Imprimir "Opcion 1. Suma de dos numeros."
		 Imprimir "ingrese el primer numero"
		 Leer n1
		 Imprimir "ingrese el segundo numero"
		 Leer n2 
		 Imprimir "Suma: " ConvertirATexto(n1 + n2 )
	 2: 
		 Imprimir "Opcion 2. Dia de la semana. "
		 Imprimir "ingrese numero de dia de la semana. (1-7)"
		 leer d 
		 Segun d Hacer
			 1:  
				 Imprimir "Lunes"
			 2: 
				 Imprimir "Martes"
			 3:
				 Imprimir "Miercoles"
			 4:
				 Imprimir "Jueves"
			 5:  
				 Imprimir "Viernes"
			 6: 
				 Imprimir "Sabado"
			 7:
				 Imprimir "Domingo"
			 
		 FinSegun
	 3: 
		 Imprimir "Opcion 3. Longitud de Texto."
		 leer a 
		 Imprimir  Longitud(a)
		 

	Fin Segun
FinAlgoritmo

