# Objetivo
Projeto calculando a média do aluno com 3 notas

<details>
<summary>Código</summary>

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
</details>