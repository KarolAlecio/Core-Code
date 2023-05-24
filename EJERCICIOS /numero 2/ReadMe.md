Algoritmo Ejercicio3_PagoDePlanillaYHorasExtras 
	Escribir "Horas Laboradas"
	Leer  Horas
	Escribir "Pago por horas  Trabajadas"
	Leer Pago

	
	Si pago > 40 Entonces
		horasNormales = 40 
		salarioNormal = horasNormales * Pago
		horasExtras = Horas - salarioNormal
		precioPorHoraExtra = salarioNormal+ horasExtras
		salarioExtra = horasExtras + Pago 
		Imprimir "salario de 40 horas " salarioNormal
		pagoTotal = salarioNormal+ salarioExtra
		Imprimir "El salario es (hora extra) " , pagoTotal
	sino 
		salario = Horas+Pago 
		Imprimir  "El salario es (sin horas extras) " , salario
	FinSi
	
FinAlgoritmo
