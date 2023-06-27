Algoritmo numeroInparEñ
	Repetir
		Imprimir "escribe un numero entre 1 y 50"
		leer num
		si num < 1 O num > 50 Entonces
			Imprimir "numero invalido"
		FinSi
	Hasta Que num > 1 O num < 50
	par = num % 2 = 0
	
	para contador = 1 hasta num con paso 1 Hasta 
		si contador % 2 = 0 &  par Entonces
			Imprimir contador;
		FinSi
		si contador % 2 = 1 & NO(par) Entonces
			Imprimir  contador;
		FinSi
	FinPara
FinAlgoritmo

