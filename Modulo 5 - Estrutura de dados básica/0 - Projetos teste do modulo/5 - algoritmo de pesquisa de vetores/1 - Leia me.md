# Objetivo
Projeto teste: Crie um programa onde eu possa inserir 5 números e decidir qual número procurar dentre os 5.

<details>
<summary>Código</summary>

```c
programa
{
	inteiro num, pos, i
	inteiro vet[5]
	
	funcao inicio()
	{
		//Preenchendo o array.
		para(i = 0; i < 5; i++){
			escreva("Digite um valor: ")
			leia(vet[i])
		}

		//Valor a pesquisar
		escreva("Digite o valor que vamos pesquisar: ")
		leia(num)

		//Definindo posição inicial para "pos".
		pos = 0
		 
		//Criando a pesquisa linear no array.
		enquanto((pos < 4) e (vet[pos] != num)){
			pos++	
		}

		//Condição para achar o número pesquisado no vetor
		se(vet[pos] == num){
			escreva ("\nO número que procuramos foi: ", num, "\n")
			escreva("Número encontrado na posição: ", pos, "\n")
		}
		senao{
			escreva ("\nO número que procuramos foi: ", num, "\n")
			escreva("O número procurado não existe no vetor. \n")
		}

		/* Imprimindo vetor completo na tela */
		escreva("\nO vetor completo é: ")
		para(i = 0; i < 5 ; i++){
			escreva(vet[i], ", ")
		}
		escreva("\n")
	}
}
```
</details>