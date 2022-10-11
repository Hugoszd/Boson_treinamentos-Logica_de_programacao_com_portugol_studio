# Objetivo
Projeto teste trocando valores entre variáveis com ajuda de variável auxiliar.

<details>
<summary>Código</summary>

```c
programa
{
	inteiro x, y, aux
	
	funcao inicio()
	{
		/*Atribuindo valor as variáveis: */
		escreva("Digite o valor de x: ")
		leia(x)
		escreva("Digite o valor de y: ")
		leia(y)
		
		/*Mostrando as variáveis com valores iniciais na tela*/
		escreva("\nO valor inicial de x é: ", x, "\n")
		escreva("O valor inicial de y é: ", y, "\n")
		
		/*Trocando os valores das variáveis*/
		aux = x
		x = y
		y = aux

		/*Imprimindo na tela*/
		escreva("\nO valor final ficou: x = ", x, " e y = ", y)
	}
}
```
</details>