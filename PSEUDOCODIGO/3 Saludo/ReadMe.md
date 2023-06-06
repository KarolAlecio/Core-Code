ingresaremos un programa en donde podamos saludar dependiendo la hora que ingreses.

Algoritmo Saludo 
	Imprimir  "======== SALUDO======="
	Definir continuar como cadena
	definir contidadSaludos Como Entero

	
	continuar <- "si"
	contidadSaludos<-0
	Mientras continuar = "si"  Hacer
		Escribir "Hellloo Everyone"
		Imprimir "ingrese la hora actual (0-23): "
		leer hora
		si hora <= 12 Entonces
			imprimir " Good Morning! "
		sino 
			si hora <= 18 Entonces
				Imprimir "Buenas Tardes! "
			SiNo
				si hora <= 24 Entonces
					Imprimir "Buenas Nochesss Mucha! "
				FinSi
			FinSi
			
		FinSi
		contidadSaludos = contidadSaludos +1
		Imprimir "Desea continuar?: Si/No "
		leer continuar
	FinMientras
	imprimir "NOS VEMOS LUEGO :) "
	Imprimir "Cantidad de Saludos: " ConvertirATexto(contidadSaludos) 
	
FinAlgoritmo
