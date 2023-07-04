// PREGUNTAR COMO SE HACE

Function  resultado <- ReverseDirectionAndSize(string)
	var resultado 
	resultado = "";
	for contador<- Longitud(string) Hasta 0 Con Paso -1 Hacer
		letter = Subcadena(string,count,count);
		si letter = Mayusculas(letter) Entonces
			letter = Minusculas(letter)
		sino 
			letter = Mayusculas(letter)
		FinSi
		resultado = Concatenar(resultado, letter)
	Fin Para
	
FinFuncion

Algoritmo Revercion
	Imprimir ReverseDirectionAndSize("Hola")
	
FinAlgoritmo
