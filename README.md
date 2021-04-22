# Atividade-7-portugol-

Exercicios 1 e 2

programa {
	funcao inicio() {
		
		inteiro N[5]
		
		para (inteiro i = 0; i < 5; i++) {
		    leia (N[i])}
		
		//numero 1
		para (inteiro y = 0; y < 5; y++) {escreva (N[y], " ")}
		
		
		//numero 2
		para (inteiro y = 4; y >= 0; y--) {escreva (N[y], " ")}
		 
	}
}



Exercicio 3

programa { funcao inicio() {

	inteiro N[4]
	inteiro Med
	
	para (inteiro i = 0; i < 4; i++) {leia (N[i])}
	
	Med =  N[0] + N[1] + N[2] + N[3]
	Med = Med / 4
	
	escreva ("sua primeira nota foi ", N[0], ", sua segunda foi ", N[1], ", sua terceira foi ", N[2], " e sua quarta foi ", N[3])
	escreva (", portanto sua media foi de ", Med, " pontos")
	
}
}

