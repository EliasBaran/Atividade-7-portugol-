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



Exercicio 4

programa { 
    inclua biblioteca Util --> U
	funcao inicio() {
		
		inteiro num
		
		escreva ("gerando numeros...\n")
		para (inteiro i = 0; i < 51; i++) {num = U.sorteia (1,50), escreva (num + "\n")} 
		
	}
}



Exercicio 5

programa {
	funcao inicio() {
		
		inteiro N[10]
		
		para (inteiro i = 0; i < 10; i++) {escreva ("informe um numero: ") leia (N[i])}
		
		para (inteiro y = 0; y < 10; y++) {
		    se (N[y] % 2 == 0) escreva ("o numero ", N[y], " na posicão ", y, " é par \n")}
		
	}
}



Exercicio 6

programa {
	funcao inicio() {
		
		inteiro Nale[30]
		inteiro N
		inteiro Con = 0
		
		para (inteiro i = 0; i < 30; i++) {Nale[i] = sorteia (1, 15)}
		
		escreva ("informe o numero para busca: ")
		leia(N)
		limpa()
		
		para (inteiro y = 0; y < 30; y++) {
		    se (Nale[y] == N) {escreva ("numero encontrado na posicão: ", y, "\n")}
		    senao {Con++}}
		    
		escreva ("seu numero apareceu: ", 30 - Con, " vezes")
		
	}
}
