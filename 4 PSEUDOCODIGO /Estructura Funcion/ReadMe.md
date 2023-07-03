// creamos una funcion en donde dependiendo la edad, se la saludara con señor o joven, y adicional a eso le agrege la funcion d 

funcion  saludo <- decirSaludo(edad)
	definir saludo Como Caracter;
	si edad >= 18 Entonces
		saludo = "Hola Mr."
	SiNo
		saludo = "Hola Joven" 
	FinSi
	
FinFuncion


Algoritmo funciones
	
	Imprimir "Cual es tu nombre: "
	leer nombre
	Imprimir "Cual es tu apellido: "
	leer apellido
	Imprimir "Cuantos años tienes: " 
	leer edad
	
	nom1 = Subcadena(nombre,0,1)
	nom2 = Subcadena(nombre,2, Longitud(nombre))
	ape1= Subcadena(apellido,0,1)
	ape2= Subcadena(apellido,2, Longitud(apellido))
	
	nombreCompleto = Mayusculas(nom1) + Minusculas(nom2)
	apellidoCompleto = Mayusculas(ape1) + Minusculas(ape2)
	Imprimir decirSaludo(edad), nombreCompleto, " " apellidoCompleto
	
FinAlgoritmo
