Algoritmo Nombre_Example
	
	Imprimir "escribe un nombre"
	leer nombre
	Imprimir "escribe un apellido"
	leer apellido
	// se debe de escribor el nombre y apellido con las primeras letras 
	// en Mayusculas, Jasson Gatica
	
	
	nombre1= Subcadena( nombre,0,1 ) 
	nombre2= Subcadena( nombre,2, Longitud(nombre ))
	apellido1= Subcadena( apellido,0,1)
	apellido2= Subcadena( apellido,2, Longitud( apellido ))
	
	nombreCompleto= Mayusculas( nombre1 ) + Minusculas( nombre2 )
	apellidoCompleto=Mayusculas( apellido1) + Minusculas( apellido2 )
	Imprimir nombreCompleto, " " ,apellidoCompleto
	
	
	
FinAlgoritmo
