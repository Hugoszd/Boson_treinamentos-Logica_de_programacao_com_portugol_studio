# Estrutura de Decisão Condicional Simples (SE)

### Conceitos
- Estrutura de control de de decisão permite tomar uma decisão durante a execução do código.
- Em determinado ponto o sistema fará uma pergunta que poderemos trabalhar conforme o resultado.
- Dependendo da resposta da pergunta o programa tomará um caminho específico.
<br/>

### Desvio condicional simples
Dado por `se<condição> então<instrução>fim`.
- Essa instrução tem por finalidade tomar uma decisão de acordo com o resultado do teste lógico feito.
- No caso do teste retornar verdadeiro, as instruções contidas entre os comandos de “então“ e “sim” serão executadas; caso contrário, nada ocorrerá.
<br/>

#### Sintaxe
```c
se(Condição){

	instruções caso a condição retorne verdadeiro.
}
instruções quando a condição foi "falsa" ou instruções após a execução "se verdadeira"
```
<br/>

#### Exemplo de diagrama com condicional simples 
<img src="/Modulo%203%20-%20Estruturas%20de%20decisão%20condicional/img/001.jpg" width="500px">
<br/>

###### Criando um programa com o diagrama dado acima
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
		escreva("Sua média foi: ", media,"\n")//Valor total da média
	}
}
```

<br/>
<br/>

[Voltar para o menu principal](https://github.com/Joshpcbrrj/Boson_treinamentos-Logica_de_programacao_com_portugol_studio)

