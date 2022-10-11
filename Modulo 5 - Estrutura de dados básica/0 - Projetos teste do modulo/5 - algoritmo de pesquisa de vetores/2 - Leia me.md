# Objetivo
Projeto teste: Consideraremos um mercado que tenha 4 frutas em estoque (Morango, banana, caju e amora). Crie um algoritmo que pergunte a um usuário qual fruta ele deseja comprar. Caso a fruta esteja disponível, mostre uma mensagem de “fruta disponível”. Se não estiver disponível, mostre uma mensagem de fruta indisponível. PS: Armazene os nomes das frutas em um array.

<details>
<summary>Código</summary>

```c
programa
{
	//Incluindo biblioteca de texto para converter as strings para minúsculo
	inclua biblioteca Texto --> t

	//Criando variáveis
	cadeia vet_frutas[] = {"morango", "banana", "caju", "amora"}
	cadeia fruta
	inteiro pos_vet
	
	funcao inicio()
	{
		escreva("Digite a fruta que deseja comprar: ")
		leia(fruta)

		//Fazendo o valor assimilado por "fruta" ficar sempre em caixa baixa
		fruta = t.caixa_baixa(fruta)

		//Criando lógica de pesquisa no array
		pos_vet = 0
		enquanto ((pos_vet < 3) e (vet_frutas[pos_vet] != fruta)){
			pos_vet ++
		}

		//Condição caso encontre ou não encontre a fruta pesquisada
		se (vet_frutas[pos_vet] == fruta){
			escreva("\nFruta disponivel ! \n")
		}
		senao{
			escreva("\nFruta acabou ! \n")
		}
	}
}
```
</details>