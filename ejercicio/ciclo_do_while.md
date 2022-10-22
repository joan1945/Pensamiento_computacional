ciclo do while para adivinar un numero entre el 1 y el 100


Algoritmo sin_titulo
	num_sec <- azar (100)
	num <- 0 
	
	//escribir num_sec
	
	Repetir
		escribir " adivina el numero "
		leer num
		Si num > num_sec Entonces
			escribir " tu numero es mayor "
		SiNo
			escribir " tu numero es menor "
			
		Fin Si
		Hasta Que num = num_sec
	escribir " le atinaste "
FinAlgoritmo


![image](https://user-images.githubusercontent.com/115374130/197362583-7921a57d-3ea8-40b2-9901-520caf9a74ef.png)
