Debes crear el código que siga la siguiente lógica: si el número dado es 100, debes tomar ese número como especial y mostrar el siguiente mensaje: "¡Este es un número especial!", pero si el número es menor que 1000, múltiplo de 10 y diferente de 100, debes mostrar el siguiente mensaje: "Este número es casi especial". Si ninguna de las condiciones dadas se cumple, se debe mostrar el siguiente mensaje: "Solo un número regular". Otro desarrollador intentó programar la lógica, pero aparentemente no pudo, necesitas corregir el código para que funcione correctamente
 
Algoritmo NumeroEspecial
	Leer n
	
	si n == 100 Entonces
		Imprimir "Este numero es especial"
		si n < 1000 & n % 10 == 0 Entonces
			Imprimir "Este numero es algo especial"
		sino 
			Imprimir "Este numero es regular"
		FinSi
	FinSi
	
FinAlgoritmo
