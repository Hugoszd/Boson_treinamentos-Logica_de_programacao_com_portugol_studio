# Estrutura de Decisão Condicional Encadeada (Se, senão se, senão)

### Desvio aninhado
Dado por varias condições para escolha da mais adequada.
- Verifica condições sucessivas para enquadrar a tomada de decisão do caso.
- A última condição é uma negação de todas as outras. Caso o programa não se enquadre em nenhuma das posteriores, agirá conforme essa (Cadeia começa com o “se” e termina com o ”senão”).
  
<aside>
💡OBS: Entre a primeira condição(SE) e última(SENÃO) podemos usar quantos (SE SENÃO) forem necessários para expressar a lógica que queremos implementar.
</aside>
<br/>

#### Sintaxe
```c
se(1° Condição){

	instruções caso a condição 1 retorne verdadeiro.
}
Senao se(2° condição) {
	instruções caso a 1 condição falsa e a 2 verdadeira

}senão se(3° condição) {
	instruções caso a 1 e 2 condição forem falsas e a 3 condição verdadeira
}
senão{
	instruções caso todas as condições forem falsas.
}
instruções após a verificações de ses e senão
```
<br/>


### Exemplo de fluxograma aplicado na média do aluno
<img src="/Modulo%203%20-%20Estruturas%20de%20decisão%20condicional/img/004.jpg" width="750px">
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

		se(media >= 7.0) {//Condição para aprovar o aluno (1° teste lógico)
			escreva("Resultado: Aprovado, chefe ! \n") 
		}
		senao se (media >= 5.0) {//Condição para a recuperação do aluno(2° teste lógico)
			escreva("Em recuperação ! Calma que ainda da. \n")
		}
		senao {//Condição para a reprovação do do aluno (caso todas as outras retornem falso)
			escreva("Reprovado. Esse ano não deu, fera. Mas ano que vem tem mais \n")
		}
				
		escreva("Sua média foi: ", media,"\n")//Valor total da média
	}
}
```


