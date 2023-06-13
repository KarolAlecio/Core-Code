Algoritmo confirmar
	Imprimir "ingrese un numero entre 1 y 50"
	leer num
	
	si num  < 1 o num >50 Entonces
		Imprimir "numeracion invalida"
	FinSi 
	
	Mientras num  < 1 o num >50 Hacer
		par= num % 2 = 0 
	Fin Mientras
	Para contar<-1 Hasta num Con Paso 1 Hacer
		si contar % 2=0 & par Entonces
			Imprimir contar 
		SiNo
			si contar % 2=1 & no impar  Entonces
				Imprimir contar 
			FinSi
		FinSi
	Fin Para
	
	
	
FinAlgoritmo
