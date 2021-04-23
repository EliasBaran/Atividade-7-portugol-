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



Exercicio 7

programa {
	funcao inicio() {
		
		inteiro listadeimpares[5]
		inteiro listadepares[5]
		inteiro ordem[10]
		inteiro N
		
		para (inteiro i = 0; i < 5; i++) {escreva ("informe um numero impar: ") leia(N)
		  se (N % 2 == 1) {listadeimpares[i] = N}
		  senao {escreva ("\nnumero não corresponde as expectativas \n") i--}}
		
		limpa() 
		
	    para (inteiro y = 0; y < 5; y++) {escreva ("informe um numero par: ") leia(N)
	      se (N % 2 == 0) {listadepares[y] = N}
	      senao {escreva ("\nnumero não corresponde com as expecatativas \n") y--}}
	      
	    limpa()
	    N = 0
	    
	    para (inteiro x = 0; x < 10; x++) {ordem[x] = listadeimpares[N] x++ ordem[x] = listadepares[N] N++}
	    
	    para (inteiro z = 0; z < 10; z++) {escreva (ordem[z], " - ")}
		
	}
}


Exercicio 8
programa {
	funcao inicio() {
	    
		inteiro x = 0
		inteiro Num[3][3] = { {72, 81, 9},
		                      {10, 29, 0},
		                      {16, 23, 4}  }
		
		para (inteiro i = 0; i < 3; i++) { 
		    se (i < 3) {escreva (Num[x][i], " ")}}
		    escreva ("\n") x++
		    
	    para (inteiro i = 0; i < 3; i++) { 
		    se (i < 3) {escreva (Num[x][i], " ")}}
		    escreva ("\n") x++
		    
		para (inteiro i = 0; i < 3; i++) { 
		    se (i < 3) {escreva (Num[x][i], " ")}}
		    
	}
}



Exercicio 9

programa {
	funcao inicio() {
	    
	    inteiro S = 0
		inteiro N[3][3] = { {72, 81, 9},
		                    {10, 29, 0},
		                    {16, 23, 4}  }
		
		para (inteiro y = 0; y < 3; y++) {
		    
		    para (inteiro x = 0; x < 3; x++){ 
		        
		        S = S + N[y][x]}}
		        
		 escreva ("o valor total foi de: ", S)
		
	}
}



Exercicio 10

programa {
	funcao inicio() {
		
		inteiro N[3][5]
		inteiro Par[3][5]
		
		para (inteiro y = 0; y < 3; y++) {
		    para (inteiro x = 0; x < 5; x++) { 
		         escreva ("informe um numero: ")
		         leia (N[y][x])
		        
		    se (N[y][x] % 2 == 0) {Par[y][x] = N[y][x]}}}
		    
		limpa()
		    
	    para (inteiro y = 0; y < 3; y++) {
		    para (inteiro x = 0; x < 5; x++) {
		         escreva (Par[y][x])
		    
		    se (Par[y][x] != 0) {escreva (" é par e foi encontrado na linha ", y, " posicao ", x, "\n")}}}

	}
}


