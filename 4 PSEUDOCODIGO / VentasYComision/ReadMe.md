**Realizaremos un programa en donde se puede ingresar la cantidad de ventas realizadas, y de igual forma en donde se le paga con forme a la comision correspondiente.**
Algoritmo COMISION
	
	Imprimir "=======COMISION========"
	
	Imprimir "Ingrese la cantidad de ventas: "
	leer cantidad_de_ventas
	definir totalventas Como Entero
	suma=0
	Para totalventas <-1  Hasta cantidad_de_ventas Con Paso 1 Hacer
		Imprimir "Escribe el valor de la venta: " , totalventas
		leer costo
		suma= suma + costo 
		
	FinPara
	Imprimir "la suma es: " suma
	
	porcentaje= 0
	
	
	si cantidad_de_ventas < 5 Entonces
		Imprimir "La cantidad de comision es: " 
		Imprimir  suma * 0.10
	SiNo
		Imprimir "La cantidad de comision es: " 
		Imprimir  suma * 0.15
		
	FinSi
	
finAlgoritmo

´´´ 
