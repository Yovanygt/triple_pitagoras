# PROYECTO 1 TRIPLE DE PITAGORAS
<CENTER><H1>PSEINT </H1></CENTER>

Algoritmo  pitagora500
    Escribir "Triangulos de pitagoras hasta  500:"
	
    Para a <- 1 Hasta 500 Con Paso 1 Hacer
        Para b <- a Hasta 500 Con Paso 1 Hacer
            Para c <- b Hasta 500 Con Paso 1 Hacer
                Si a*a + b*b = c*c Entonces
                    Escribir "(", a, ", ", b, ", ", c, ")"
                FinSi
            FinPara
        FinPara
    FinPara 
	si a + b + c <= 500 Entonces 
		Escribir  "es un triple de Pitagoras." 
	sino  
		escribir"es un triple de Pitagoras, pero su suma supera 500."
		
	FinSi
	
FinAlgoritmo 

<CENTER><H1>CODIGO EN C++ </H1></CENTER>
#include <iostream>

int main(){
	std::cout<<"TRIPLE DE PITAGORAS NO MAYOR A 500" <<std:: endl;
	
	for (int p = 1; p<=500; ++p) {
		for(int q = p; q<=500; ++q){
			for(int r = q; r<=500; ++r){
				if (p*p+q*q == r*r){
					std::cout<<"("<< p <<","<< q <<","<< r <<")" << std:: endl;
					if (p+q+r <=500){
						std::cout<<"es un triple de pitagoras" <<std::endl;	
					}
						
					else{
					
						std::cout<<"supera la suma de 500 pero si es un triple de pitagoras"<<std::endl;
						
					
						}	
																	
				}
						
				
			}
			
					
			
		}
		
		
	}
	
	
	return 0;
}

<CENTER><H1>CODIGO EN PHYTON </H1></CENTER>
trío de pitagoras en python


print("Trios Pitagoricos hasta 500:")

for p in range(1, 501):

    for q in range(p, 501):

        for r in range(q, 501):

            if p * p + q * q == r * r:
                print("({}, {}, {}) es un triple de pitagoras".format(p, q, r), end= " ")
            elif p * p + q * q < r * r:

                print("({}, {}, {}) supera la suma de 500 pero es un triple
                 de pitagoras".format(p, q, r))
#   t r i p l e _ p i t a g o r a s  
 #   t r i p l e _ p i t a g o r a s  
 