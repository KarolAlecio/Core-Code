// realizamos un programa en donde sabremos cual cantidad es mas grande.
Algoritmo distancia_A_Cero
	Imprimir "escibe un numero"
	leer distancia
	Para contador <-1 Hasta 3 Con Paso 1 Hacer
		Imprimir "escribe un numero"
		leer num
		si abs(num) > abs(distancia) Entonces
			distancia = num
		FinSi
	Fin Para
	Imprimir "la distancia mas grande es: " Trunc(distancia)
FinAlgoritmo
