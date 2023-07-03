// realizamos un prigrama en donde se hara al azar, quien gana, y quien lo haga su nombre saldra en mayusculas, para asi identificar el ganador.
Algoritmo lanazar_Moneda
	Imprimir "ingresa jugador 1"
	leer play1
	Imprimir "ingresa la cantidad a jugar"
	leer cantidad1
	Imprimir "ingresa jugador 2"
	leer play2
	Imprimir "ingresa la cantidad a jugar"
	leer cantidad2
	
	si cantidad1 <=0 o cantidad2 <=0 Entonces
		si cantidad1 <=0 & cantidad2 <=0 Entonces
			Imprimir "Juego Terminado"
		sino 
			si cantidad1 <=0 Entonces
				Imprimir "Jugador que gana: ", Mayusculas( play2 ), "cantidad ganada: 0"
			SiNo
				Imprimir "Jugador que gana: ", Mayusculas( play1 ), "cantidad ganada: 0" 
			FinSi
		FinSi
	sino 
		si Aleatorio(0,1) = 0 Entonces
			Imprimir "Jugador que gana: ", Mayusculas(play1)," ", "cantidad ganada: " cantidad2
		sino 
			Imprimir "Jugador que gana: ", Mayusculas( play2 ) ," ",  "cantidad ganada: ", cantidad1

		FinSi
	FinSi
