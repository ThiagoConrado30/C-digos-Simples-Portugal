# Codigo caixa

cadeia usuario
        cadeia senha 
        real produto
        real soma = 0
        inteiro cont = 0
		real valorRecebido
        real troco
        
		
		escreva ("Nome de usuario\n")
		leia (usuario)
		escreva ("Senha\n")
		leia(senha)
		 se (senha == ("290389") e usuario == ("Thiago")) { 
		 	escreva ("Carregando....\n")
		 	escreva ("Digite o valor do produto, use ponto e não virgula\n")
		 	escreva ("Tecle numero 0 para total\n")
		 } senao { escreva ("Acesso Negado senha ou usuario incorreto\n")
	
	 }  
	    enquanto (produto > 0 ) { 
			leia(produto) 
	     cont++
		 soma = soma + produto
         
		}
           escreva ("Total\n", soma)
		   escreva ("\n digite o valor recebido\n")
		   leia (valorRecebido)
		   troco = valorRecebido - soma
           
		   
		 	
		     escreva ("Troco \n",troco) 
		    
		   	 
		   }
        
   	}    
	      
