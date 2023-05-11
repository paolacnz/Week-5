Algoritmo sumOfPairs
	Definir num, sum_even, salir Como Entero
    sum_even <- 0
    salir <- 0
	
    Repetir
        Escribir "Ingrese un número del 1 al 100:"
        Leer num
		
        Si num >= 1 Y num <= 100 Entonces
            Si num % 2 == 0 Entonces
                sum_even <- sum_even + num
            Fin Si
        Sino
            salir <- 1
        Fin Si
		
    Hasta Que salir = 1
	
    Escribir "La suma de los números pares ingresados es:", sum_even
FinAlgoritmo
