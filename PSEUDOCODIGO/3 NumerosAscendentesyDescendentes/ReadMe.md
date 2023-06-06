**Para este desafío vamos a imprimir números en orden ascendente o descendente. El usuario debe ingresar un número, y luego debe ingresar si desea imprimir los números en orden ascendente o descendente. Si el usuario elige el orden ascendente, los números se imprimirán desde el número hasta el número ingresado; de lo contrario, los números se imprimirán en orden descendente desde el número ingresado hasta el número . Para resolver este desafío, recuerda utilizar el bucle For(Para)**

´´´ psc
Algoritmo numerosAscendentesYDescendentes
	Imprimir "ingrese el numero"
	leer numeroSeleccionado
	Imprimir "Opciones disponibles"
	Imprimir " 1. opcion Ascendente"
	Imprimir " 2. opcion Descendente"
	leer op
	
	Segun op hacer 
	
	"1" :
		Para i<-0 Hasta numeroSeleccionado Con Paso 1 Hacer
			Imprimir ConvertirATexto(i)
		FinPara
	"2" :
		Para i<-numeroSeleccionado Hasta 1 Con Paso -1 Hacer
			Imprimir ConvertirATexto(i)
		FinPara
FinSegun
Imprimir "Numero ingresado incorrecto" 
FinAlgoritmo
´´´
