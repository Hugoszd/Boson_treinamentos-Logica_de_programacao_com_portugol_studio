# Objetivo
Projeto teste: Deixe que o usuário escolha 9 números, monte uma matiz e exiba os números.

<details>
<summary>Código</summary>

```c
programa
{
	// Criando a matriz
	inteiro matriz[3][3]
	
	//Criando variáveis para ajudar no preenchimento dos dados na matriz
	inteiro lin, col
	
	funcao inicio()
	{
		// Pedindo dados para popular a matriz
		para(lin = 0; lin <=2; lin++){
			para(col = 0; col <= 2; col++){
				escreva("Digite um número: ")
				leia(matriz[lin][col])
			}
		}escreva("\n")

		// Imprimindo números da matriz em tela
		para(lin = 0; lin <=2; lin++){
			para(col = 0; col <= 2; col++){
				se(col < 2){
					escreva(matriz[lin][col], ", ")	
				}
				senao{
					escreva(matriz[lin][col], "\n")
				}
			}
		}
	}
}
```
</details>