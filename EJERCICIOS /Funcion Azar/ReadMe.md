Algoritmo EjemFunciones3
	//realizaremos el juego de cara o escudo, 
	// tendremos que realizar un pseudocodigo en donde podremos seleccionar
	// que es lo que queremos, tambien colocar la hora y fecha.
	
	Imprimir  "elija cara (1) o escudo (0) "
	leer seleccionUsusario
	// la funcion azar empieza en 0
	numeroaleatoro = azar(1)
	
	si seleccionUsusario = 1  Entonces
		imprimir "escogiste cara"
	sino
		Imprimir "escogiste escudo"
	FinSi
	
		si numeroaleatoro = 1  | numeroaleatoro = 0 Entonces
			imprimir "era cara "
			
		SiNo
			Imprimir " era escudo"
			
		FinSi
		
		si seleccionUsusario = numeroaleatoro Entonces
			si seleccionUsusario == 1   Entonces
			Imprimir  "Has Perdidoooo amigo"
		SiNo
			Imprimir " Has Ganadoooo :D"
		FinSi
	FinSi
	
FinAlgoritmo
