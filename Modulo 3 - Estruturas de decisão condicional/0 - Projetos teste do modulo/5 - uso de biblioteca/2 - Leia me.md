# Objetivo
Projeto teste fazendo radiciação de qualquer número com qualquer índice

<details>
<summary>Código</summary>

```c
programa
{
	inclua biblioteca Matematica --> m
	real radicando, indice, raiz
	
	funcao inicio()
	{
		//Pedindo numero para o radicando.
		escreva("Digite um número para o radicando: ")
		leia(radicando)

		//Pedindo numero para o indice.
		escreva("Digite um número para o índice: ")
		leia(indice)

		//Retornando numeros escolhidos para a operação de radiciação.
		escreva("\nO radicando é :",radicando, "\n")
		escreva("O indice é :",indice, "\n")  

		raiz = m.raiz(radicando, indice)

		escreva ("\nA radiciação do radicando: ", radicando, " e do indice: ", indice, " e: ", raiz, "\n")
	}
}
```
</details>