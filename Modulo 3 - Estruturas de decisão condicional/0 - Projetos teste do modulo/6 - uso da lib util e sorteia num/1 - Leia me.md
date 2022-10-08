# Objetivo
Projeto teste usando a funcionalidade sorteia da biblioteca útil para sortear intervalo de números

<details>
<summary>Código</summary>

```c
programa
{
	inclua biblioteca Util --> u //incluindo e dando "alias" a lib "Util"
	inteiro num_inicial, num_final, num_sorteado
	
	funcao inicio()
	{
		escreva("Digite o primeiro número do intervalo do sorteio: ")
		leia(num_inicial)// Pegando o primeiro número.

		escreva("Digite o último número do intervalo do sorteio: ")
		leia(num_final)// Pegando o último número.

		escreva("\nO intervalo do sorteio começa no: " + num_inicial + " e termina no número: " + num_final, "\n")

		num_sorteado = (u.sorteia(num_inicial, num_final))

		escreva("O numero sorteado entre: ", num_inicial, " e ", num_final, " é: ", num_sorteado, "\n")
		
	}
}
```
</details>