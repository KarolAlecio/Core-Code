

Function  resultado <- ReverseDirectionAndSize(string)
	var resultado 
	resultado = "";
 // en resultado se pone, vacio ya que con eso iniciaremos con la  funcion
	para contador<- Longitud(string) Hasta 0 Con Paso -1 Hacer
 // se pone el -1, ya que empezaria de atras para delante
		letter = Subcadena(string,contador, contador);
  // lleva doble, contador ya que con eso se iniciaria de atras para delante.
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
