Algoritmo listaEjem
	Imprimir "------CONTACTO-------"
	Imprimir "ingresa cuantas personas tendra la agenda: "
	leer contacto
	
	Dimension agenda[contacto]
	// la palabra  Dimension es la que guardara 
	//  y ejecutara la "lista"
	para contador <- 1 hasta contacto Hacer
		Imprimir  "Ingrese el nombre del contacto" , contador , ":"
		leer nombre 
		agenda[contador]= nombre
	FinPara
	
	para iterador<-1 Hasta contacto Hacer
		Imprimir iterador, "." , agenda[iterador]
	FinPara
	
FinAlgoritmo
