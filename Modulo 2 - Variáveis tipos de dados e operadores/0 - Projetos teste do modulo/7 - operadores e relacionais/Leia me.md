# Objetivo
Projeto teste comparação de 2 números

<details>
<summary>Código</summary>

```c
programa
{
	logico x, y, z //Variáveis do tipo boolean
	inteiro n1,n2
	
	funcao inicio()
	{
		escreva("Digite um número: ")
		leia(n1)
		
		escreva("Digite outro número: ")
		leia(n2)

		/*Testando operadores relacionais */
		x = n1 == n2//Perguntando se n1 é igual a n2 e armazenando a resposta em x.
		escreva("\nOs números ", n1, " e ", n2, " são iguais ? ", x, "\n" )
		
		y = n1 > n2//Perguntando se n1 é igual a n2 e armazenando a resposta em x.
		escreva("O número ", n1, " é maior que o número ", n2, " ? ", y, "\n")

		z = n1 != n2
		escreva("Os números ", n1, " e ", n2, " são diferentes ? ", z, "\n")
	}
}
```

</details>