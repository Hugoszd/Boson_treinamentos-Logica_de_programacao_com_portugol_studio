# Objetivo
Projeto teste: Calcule o fatorial de um número com uma função recursiva e mostre o resultado na tela.

<details>
<summary>Código</summary>

```c
programa
{	
	//Criando variáveis
	inteiro num = 0
	inteiro fat = 0

	//Função para calculo de fatorial de forma recursiva
	funcao inteiro calcula_fatorial(inteiro n)
	{
		//Trabalhando caso  base 
		se((n == 0) ou (n == 1)){
			retorne 1	
		}
		
		//Trabalhando retorno recursivo (Chamando a propria função "calcula_fatorial")
		senao{
			retorne n * calcula_fatorial(n - 1)
		}
	}
	
	funcao inicio()
	{
		escreva("Calculo do fatorial de um número\n")

		//Laço para impedir que usuário digite número negativo
		enquanto(verdadeiro){
			escreva("Digite um número positivo: ")
			leia(num)
			se(num < 0){
				escreva("\nErro ! Só conseguimos calcular fatorial de números positivos.\n")	
			}
			senao{
				pare
			}
		}

		//Chamando a função recursiva para calcular o fatorial de um número
		fat =  calcula_fatorial(num)

		//Imprimindo resultado na tela
		escreva("O fatorial de : ", num, " é: ", fat, "\n")
		
		
	}
}
```
</details>