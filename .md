# promedio
promedio 5 alumnos
Algoritmo promedios_alumnos_final
			escribir "ingresar nombres de alumnos y notas ";
		// alumno 1		
		escribir "nombre del alumno 1";
		leer nombreA1
		escribir "notas del alumno 1";
		leer nota1A1
		leer nota2A1
		leer nota3A1
		// alumno 2
        escribir "nombre del alumno 2 ";
		leer nombreA2
		escribir "notas del alumno 2 ";
		leer nota1A2
		leer nota2A2
		leer nota3A2
		// alumno 3 
		escribir "nombre del alumno 3 ";
		leer nombreA3
		escribir "notas del alumno 3 ";
		leer nota1A3
		leer nota2A3
		leer nota3A3
		// alumno 4 
		escribir "nombre del alumno 4 ";
		leer nombreA4
		escribir "notas del alumno 4 ";
		leer nota1A4
		leer nota2A4
		leer nota3A4
		// alumno 5 
		escribir "nombre del alumno 5 ";
		leer nombreA5
		escribir "notas del alumno 5 ";
		leer nota1A5
		leer nota2A5
		leer nota3A5
		// desarrollo 	(((   alumno 1  )))
		escribir nombreA1;
		// nota mayor  ( parte 1 )
		Si nota1A1 > nota2A1 Entonces
			Si nota1A1 > nota3A1 Entonces
			    escribir " nota mayor de alumno " ,nota1A1;
			SiNo
			    escribir " nota mayor de alumno " , nota3A1
			Fin Si
			// nota mayor  ( parte 2 )
		SiNo   
			si nota2A1  >  nota3A1 entonces
			    escribir " nota mayor de alumno " , nota2A1;
			sino  
			    escribir " nota mayor de alumno ", nota3A1
			fin si
		Fin Si
				// nota menor ( parte 1 )
		si nota1A1 < nota2A1 Entonces
			si nota1A1 < nota3A1 Entonces
				escribir " nota menor de alumno " , nota1A1;
			sino 
				escribir " nota menor de alumno " , nota3A1;
			FinSi
		// nota menor ( parte 2 )	
		sino 
			si nota2A1 < nota3A1 Entonces
				escribir " nota menor de alumno " , nota2A1;
			sino 
				escribir " nota menor de alumno " , nota3A1
			FinSi
		FinSi
		//promedio alumono 1
		promedioa1  <- (nota1A1 + nota2A1+ nota3A1) /3;
		escribir " promedio final ", promedioa1 ;
		
		
		// desarrollo 	(((   alumno 2 )))
		escribir nombreA2;
		// nota mayor  ( parte 1 )
		Si nota1A2 > nota2A2 Entonces
			Si nota1A2 > nota3A2 Entonces
			    escribir " nota mayor de alumno " ,nota1A2;
			SiNo
			    escribir " nota mayor de alumno " , nota3A2
			Fin Si
			// nota mayor  ( parte 2 )
		SiNo   
			si nota2A2  >  nota3A2 entonces
			    escribir " nota mayor de alumno " , nota2A2;
			sino  
			    escribir " nota mayor de alumno ", nota3A2 ;
			fin si
		Fin Si
		// nota menor ( parte 1 )
		si nota1A2 < nota2A2 Entonces
			si nota1A2 < nota3A2 Entonces
				escribir " nota menor de alumno " , nota1A2;
			sino 
				escribir " nota menor de alumno " , nota3A2;
			FinSi
		// nota menor ( parte 2 )	
		sino 
			si nota2A2 < nota3A2 Entonces
				escribir " nota menor de alumno " , nota2A2;
			sino 
				escribir " nota menor de alumno " , nota3A2 ;
			FinSi
		FinSi
		//promedio alumono 2
		promedioa2  <- (nota1A2 + nota2A2+ nota3A2) /3;
		escribir " promedio final ", promedioa2 ;
		
		
		// desarrollo 	(((   alumno 3 )))
		escribir nombreA3;
		// nota mayor  ( parte 1 )
		Si nota1A2 > nota2A3 Entonces
			Si nota1A3 > nota3A3 Entonces
			    escribir " nota mayor de alumno " ,nota1A3;
			SiNo
			    escribir " nota mayor de alumno " , nota3A3
			Fin Si
			// nota mayor  ( parte 2 )
		SiNo   
			si nota2A3 >  nota3A3 entonces
			    escribir " nota mayor de alumno " , nota2A3;
			sino  
			    escribir " nota mayor de alumno ", nota3A3 ;
			fin si
		Fin Si
		// nota menor ( parte 1 )
		si nota1A3 < nota2A3 Entonces
			si nota1A3 < nota3A3 Entonces
				escribir " nota menor de alumno " , nota1A3;
			sino 
				escribir " nota menor de alumno " , nota3A3;
			FinSi
		// nota menor ( parte 2 )	
		sino 
			si nota2A3 < nota3A3 Entonces
				escribir " nota menor de alumno " , nota2A3;
			sino 
				escribir " nota menor de alumno " , nota3A3 ;
			FinSi
		FinSi
		//promedio alumono 3
		promedioa3  <- (nota1A3 + nota2A3+ nota3A3) /3;
		escribir " promedio final ", promedioa3 ;
		
		
		// desarrollo 	(((   alumno 4 )))
		escribir nombreA4;
		// nota mayor  ( parte 1 )
		Si nota1A4 > nota2A4 Entonces
			Si nota1A4 > nota3A4 Entonces
			    escribir " nota mayor de alumno " ,nota1A4;
			SiNo
			    escribir " nota mayor de alumno " , nota3A4
			Fin Si
			// nota mayor  ( parte 2 )
		SiNo   
			si nota2A4  >  nota3A4 entonces
			    escribir " nota mayor de alumno " , nota2A4;
			sino  
			    escribir " nota mayor de alumno ", nota3A4 ;
			fin si
		Fin Si
		// nota menor ( parte 1 )
		si nota1A4 < nota2A4 Entonces
			si nota1A4 < nota3A4 Entonces
				escribir " nota menor de alumno " , nota1A4;
			sino 
				escribir " nota menor de alumno " , nota3A4;
			FinSi
		// nota menor  ( parte 2 )
		sino 
			si nota2A4 < nota3A4 Entonces
				escribir " nota menor de alumno " , nota2A4;
			sino 
				escribir " nota menor de alumno " , nota3A4 ;
			FinSi
		FinSi
		//promedio alumono 1
		promedioa4  <- (nota1A4 + nota2A4+ nota3A4) /3;
		escribir " promedio final ", promedioa4 ;
		
		
		// desarrollo 	(((   alumno 5 )))
		escribir nombreA5;
		// nota mayor  ( parte 1 )
		Si nota1A5 > nota2A5 Entonces
			Si nota1A5 > nota3A5 Entonces
			    escribir " nota mayor de alumno " ,nota1A5;
			SiNo
			    escribir " nota mayor de alumno " , nota3A5
			Fin Si
			// nota mayor  ( parte 2 )
		SiNo   
			si nota2A5 >  nota3A5 entonces
			    escribir " nota mayor de alumno " , nota2A5;
			sino  
			    escribir " nota mayor de alumno ", nota3A5 ;
			fin si
		Fin Si
		// nota menor ( parte 1 )
		si nota1A5 < nota2A5 Entonces
			si nota1A5 < nota3A5 Entonces
				escribir " nota menor de alumno " , nota1A5;
			sino 
				escribir " nota menor de alumno " , nota3A5;
			FinSi
			// nota menor ( parte 2 )	
		sino 
			si nota2A5 < nota3A5 Entonces
				escribir " nota menor de alumno " , nota2A5;
			sino 
				escribir " nota menor de alumno " , nota3A5 ;
			FinSi
		FinSi
		//promedio alumono 5
		promedioa5  <- (nota1A5 + nota2A5+ nota3A5) /3;
		escribir " promedio final ", promedioa5 ;
FinAlgoritmo
