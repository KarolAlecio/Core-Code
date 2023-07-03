Funcion costo <- TotalPrice(precio, iva)
	definir costo Como Real;
	si precio > 3000 Entonces
		costo = (precio + (precio/1000*iva) )/ 1000*90
	sino 
		costo = (precio + (precio/1000*iva) )
	FinSi
FinFuncion



Algoritmo preciototal
	Imprimir TotalPrice(5000,21)
FinAlgoritmo
