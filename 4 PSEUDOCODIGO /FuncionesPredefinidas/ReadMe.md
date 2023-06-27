
Algoritmo abs_Funciones
	// lo que quiere decir es que el valor absoluto es realmente el numero
	// osea el valor absoluto de x es x
	// en caso contrario, si -x el valos seria x, y que no puede aver un numero
	// negativo, todo tiene que ser de verdad.
	Imprimir "el valor Absoluto de 15: " , abs(15)
	Imprimir "el valor Absoluto de -15: " , abs(-15)
	// resultado :
	/// el valor Absoluto de 15: 15
	///el valor Absoluto de -15: 15
FinAlgoritmo

SubAlgoritmo  Funciones_Trunc
	// en Trunc es una Funcion en la cual, no permite que
	// los numero sean disparejos por asi decirlo, tienen
	// que estar cabales.
	Imprimir trunc(-15.0001)
	Imprimir trunc(16.2845)
	imprimir trunc(0.215433)
	// resultado :
	/// -15
	// 16
	// 0
FinSubAlgoritmo

SubAlgoritmo reddon_example
	// en esta funcion, lo que se logra es redondear la numeracion
	// asi no queda con numeros flotando, ponerlos enteros
	
	Imprimir redon(11.5555)
	Imprimir redon(9.9998)
	//12
	//10
FinSubAlgoritmo

SubAlgoritmo azar_example
	// en esta funcion, es para que de los numeros aliatoriamente,
	// ya que se utiliza en devolver y asignar el numero "ganador"
	// sera numero indefinidos.
	Imprimir azar(20)
	Imprimir azar(10)
	Imprimir azar(15)
	Imprimir azar(100)
	
	//18
	//6
	//5
	//75
	// dio los numeros alzar.
FinSubAlgoritmo

SubAlgoritmo longitud_example
	// este algoritmo, calcula la cantidad de las letras que esten 
	// en las lineas o parrafos.
	Imprimir Longitud("hola amigos, como estan")
	//23. cantidad de letras que esta en el parrafo
FinSubAlgoritmo
