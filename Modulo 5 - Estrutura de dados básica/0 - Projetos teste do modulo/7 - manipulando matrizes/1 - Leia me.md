# Objetivo
Projeto teste: Crie um programa que permita que o usuário insira 9 números e transforme em uma matriz 3 por 3 e mostre na tela.

<details>
<summary>Código</summary>

```c
programa
{
	inteiro matriz[3][3]
	inteiro linha
	inteiro coluna
	
	funcao inicio()
	{
		//Preenchendo a matriz com dados (Para cada linha eu vou preencher todas as colunas) laço dentro de laço
		para(linha = 0; linha < 3; linha ++){
			para(coluna = 0; coluna <= 2; coluna ++){
				escreva("Ditite um número qualquer: ")
				leia(matriz[linha][coluna])
				escreva("\n")
			}
		}

		//Limpando os dados da tela 
		limpa()
		escreva("A matriz completa é:\n")
		
		//Escrever a matriz completa na tela
		para(linha = 0; linha < 3; linha ++){
			para(coluna = 0; coluna <= 2; coluna ++){
				
				//condição para organizar os números nas colunas da matriz que será apresentada na tela
				se(coluna < 2){
					escreva(matriz[linha][coluna], " |")
				}
				senao{
					escreva(matriz[linha][coluna], "\n")
				}
		
			}	
		}
	}
}
```
</details>