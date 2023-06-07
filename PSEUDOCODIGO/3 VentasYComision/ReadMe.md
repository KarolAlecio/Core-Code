Algoritmo ComicionPorVentas
	Imprimir "=======COMISION========"

	Imprimir "Ingrese la cantidad de ventas: "
	leer cantidad_de_ventas
	totalventas = 0
	
	Para ventas = 1  Hasta cantidad_de_ventas Con Paso 1 Hacer
		Imprimir "Escribe el valor de la venta " , ventas
		leer costo
	// veridicar por que no me suma
		totalventas = totalventas + costo
	FinPara
	
	porcentage = costo / cantidad_de_ventas
	porcentage = costo % cantidad_de_ventas
	
	
	si cantidad_de_ventas <= 5  Entonces
		Imprimir  " la cantida de comision seria del: " 0.10
	SiNo
		si cantidad_de_ventas >= 6 Entonces
			Imprimir "la cantidad de comision seria del: " 0.15
		FinSi
		
	FinSi
FinAlgoritmo
