# homework-done-in-pseint
En psint me da el ok! tengo problemas para cambiar al idioma python


definir numero Como Entero
	definir monto Como Real
	escribir "Edad Ingresante"
	leer numero
	
	Si numero < 4 Entonces
		monto = 0.0
		Escribir "estrada Gratis"
	Sino
		Si numero < 12 Entonces
			monto <- 150.0 / 3
		escribir "Entrada Niño"	
		Sino
			Si numero < 18 Entonces
				monto <- 150.0 / 2
				Escribir "Entrada Adolecente"
			Sino
				Si numero <= 60 Entonces
					monto <- 150.0
					escribir "Entrada Mayores"
				SiNo
					si numero > 60 Entonces
						monto <- 0.0
						escribir "Entrada Jubilados"
					FinSi
					
				
				FinSi
			FinSi
		FinSi
	FinSi
	
	Escribir "$ ", monto
