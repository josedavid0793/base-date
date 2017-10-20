# base-date
base date es un proyecto como estudiante de programación que me permitirá familiarizarme con este tema.




//crear una calculadora en PSeInt

Proceso calculadora
	
	a1=0;
	a2=0;
	menu=0;
	
	escribir "inserte numero 1 : ";
	leer a1;
	escribir "inserte numero 2 : ";
	leer a2;
	
	
	escribir "(1) sumar ";
	escribir "(2) restar";
	escribir "(3) multiplicar";
	escribir "(4) dividir";
	escribir "(5) porcentaje";
	escribir "(6) raiz cuadrada";
	
	leer menu;
	
	//proceso
	
	segun menu hacer
		1:escribir " va a sumar )";
			escribir " la suma es =",a1+a2;
		2:escribir "va a restar )";
			escribir " la resta es =",a1-a2;
		3:escribir " va a multiplicar)";
			escribir " la multiplicacion es =",a1*a2;
		4:escribir " va a dividir )";
			escribir " la division es =",a1/a2;
		5:escribir "va a sacar el porcentaje )";
			escribir " el porcentaje es =",a1*a2/100;
		6:escribir " va a sacar la raiz cuadrada )";
			escribir " la raiz cuadrada es =",a1^0.5;
			
		de otro modo:
			escribir " no se encuentra el numero ";
			
			
			
		
			
	FinSegun
	
	
	
	
	
	
	
FinProceso
