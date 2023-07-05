// se crea una funcion, en donde se aplique el iva, y si es mayor a 3000, lleva un descuento, que seria del 10%
Funcion costo <- TotalPrice(precio, iva)
	definir costo Como Real;
	si precio > 3000 Entonces
		costo = (precio + (precio/1000*iva) )/ 1000*90
	sino 
		costo = (precio + (precio/1000*iva) )
	FinSi
FinFuncion

// el iva (21) ya si se quiere cambiar no afecta en nada, es el numero que esta al lado del precio (5000) si fue menor, no aplica el descuanto.

Algoritmo preciototal
	Imprimir TotalPrice(5000,21)
FinAlgoritmo
