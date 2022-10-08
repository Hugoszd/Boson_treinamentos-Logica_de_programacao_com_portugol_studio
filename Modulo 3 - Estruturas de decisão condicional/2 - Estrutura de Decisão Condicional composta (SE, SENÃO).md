# Estrutura de Decisão Condicional composta (SE, SENÃO) 

#### Desvio condicional composta
Dado por `se<condição> então<instrução>senão<instruções>fim`.
- Essa instrução tem por finalidade tomar uma decisão de acordo com o teste lógico estabelecido.
- Neste caso temos uma segunda condição. Caso o programa não atenda a condição “se” verdadeira, poderá ser enquadrado na condição “senão”, que seria a condição “se falsa”. Caso nenhuma das condições seja atendida o programa continuará sua execução ignorando as 2 instruções.
<br/>

#### Sintaxe
```c
se(Condição){

	instruções caso a condição retorne verdadeiro.
}
Senao {
	instruções caso a condição retorne falso.
}fim
instruções após a verificação se e senão (Verdadeiro e falso)
```
<br/>

#### Exemplo de fluxograma
<img src="/Modulo%203%20-%20Estruturas%20de%20decisão%20condicional/img/002.jpg" width="700px">
<br/>

### Resolvendo o problema da média com desvio condicional composto
<img src="/Modulo%203%20-%20Estruturas%20de%20decisão%20condicional/img/003.jpg" width="600px">
<br/>

###### Código
```c
programa
{
	real nota_1, nota_2, nota_3 //Variáveispara guardar as notas do trimestre.
	real media //Variável para guardar a média geral nos 3 semetres.
	
	funcao inicio()
	{
		escreva("Entre com a primeira nota do aluno: ")
		leia(nota_1)//Pegando a primeira nota.
		
		escreva("Entre com a segunda nota do aluno: ")
		leia(nota_2)//Pegando a segunda nota.

		escreva("Entre com a terceira nota do aluno: ")
		leia(nota_3)//Pegando a segunda nota.

		media = (nota_1 + nota_2 + nota_3) / 3 //Guardando a média das 3 notas.

		se(media >= 7) {//Condição para aprovar o aluno
			escreva("Resultado: Aprovado, chefe ! \n") 
		}
		senao {//Note que aqui não precisamos por condição. A instru será executada com "se" falso.
			escreva("Resultado: Reprovado. Deu ruim -_- \n")
		}
		
		escreva("Sua média foi: ", media,"\n")//Valor total da média
	}
}
```

