# Objetivo
Projeto teste: Crie uma matriz 10 por 10 e preencha com números aleatórios entre 1 e 100.

<details>
<summary>Código</summary>

```c
programa
{
	//Incluindo biblioteca "útil" para gerar números aleatórios.
	inclua biblioteca Util --> u
	
	//Criando variáveis
	inteiro matriz[10][10]
	inteiro lin, col
	inteiro soma = 0 //Variávelresponsavel pela soma de valores (acumuladora)
		
	funcao inicio()
	{
		//Laço encadeado para preenchimento da matriz com números aleatórios
		para(lin = 0; lin < 10; lin++){
			para(col = 0; col < 10; col++){
				matriz[lin][col] = u.sorteia(1, 100)
			}
		}

		//Escreve dados da matriz na tela
		para(lin = 0; lin < 10; lin++){
			para(col = 0; col < 10; col++){
				
				//condição para escrever os números da matriz de forma tabular
				se(col < 9){
					se(matriz[lin][col] < 10){
						escreva(0,0, matriz[lin][col], " |")
					}
					senao se ((matriz[lin][col] >= 10) e (matriz[lin][col] <= 99)){
						escreva(0, matriz[lin][col], " |")
					}
					senao{
						escreva(matriz[lin][col], " |")
					}
				}
				//condição para pular linha a cada 10 números
				senao{
					se(matriz[lin][col] < 10){
						escreva(0,0, matriz[lin][col], "\n")
					}
					senao se ((matriz[lin][col] >= 10) e (matriz[lin][col] <= 99)){
						escreva(0, matriz[lin][col], "\n")
					}
					senao{
						escreva(matriz[lin][col], "\n")
					}
				}
			}
		}
	}
}
```
</details>