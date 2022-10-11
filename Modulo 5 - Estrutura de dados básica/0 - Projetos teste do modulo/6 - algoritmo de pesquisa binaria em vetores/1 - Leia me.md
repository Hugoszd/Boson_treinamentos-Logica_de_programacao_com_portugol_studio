# Objetivo
Projeto teste: Crie um vetor de 10 posições com números aleatórios e organize do menor para o maior. Na sequencia, crie um algoritmo de pesquisa de um número (que será informado pelo usuário) e diga se ele esta ou não no vetor com números aleatórios.

<details>
<summary>Código</summary>

```c
programa
{
	//Incluindo biblioteca de utilitários
	inclua biblioteca Util --> u

	//Criando variáveis
	inteiro cont, cont_a, cont_b
	inteiro aux
	inteiro vet[10]
	
	funcao inicio()
	{
		preenche_ordena_vetor(vet)

		//Imprimindo o vetor na tela (Para conferirmos os números presentes nele)
		para(cont_a = 0; cont_a <= 9; cont_a++){
			escreva (vet[cont_a] + " ")
		}
		
		//Pulando linha
		escreva("\n")

		//Implementando pesauisa binária
		inteiro inicial = 0 //Variável de inicio do vetor (Inicializada com 0)
		inteiro final = 9 //Variável de final do vetor (Inicializada  com a última posição do vetor (9) )
		inteiro meio //Variável do meio (Geralmente não inicializada)
		logico encontrado = falso //Variável flag de tipo lógico (Inicializada como falso poisainda não pesquisamos)
		inteiro busca //Variável que irá receber o número que queremos buscar (Geralmente atribuida pelo usuário)

		//Pedindo valor para "busca"
		escreva("Digite o valor que quer pesquisar: ")
		leia(busca)

		//Laço para encontrar o número da variável "busca"
		enquanto ((inicial <= final) e (nao encontrado)){
			meio = (inicial + final) / 2

			//Condição para comparação da variável "meio" com a variável "busca".
			se(vet[meio] == busca){
				encontrado = verdadeiro 
			}
			//Determinando para qual lado irei em caso de "meio" maior que "busca" (Movimenta final para esquerda)
			senao se (vet[meio] > busca){
				final = meio -1 //Deslocará o final do vetor para antes do meio
			}
			//Determinando para qual lado irei em caso de "meio" maior que "busca" (Movimenta inicio para direita)
			senao {
				inicial = meio + 1 //Deslocará o inicio do vetor para depois do meio
			}
		}

		//Agindo caso a nossa flag vire verdadeira (Caso encontremos o número da variável "busca").
		se(encontrado == verdadeiro){
			escreva("\nSim ! O número procurado se encontra no vetor.\n")
		}
		//Agindo caso a nossa flag permaneça falsa (Caso não encontremos o número da variável "busca")
		senao{
			escreva("\nNão ! o número procurado não esta presente no vetor.\n")
		}
		
	}

	//Criando função a parte para preencher e ordenar o vetor
	funcao preenche_ordena_vetor(inteiro vetor[]){
		//preenchendo vetor
		para (cont = 0; cont <= 9; cont++){
			vet[cont] = u.sorteia(1, 20)
		}
		
		//ordenando vetor
		para (cont_a = 0; cont_a <= 9; cont_a++){
			para(cont_b = cont_a + 1; cont_b <= 9; cont_b++){
				se(vetor[cont_a] > vetor[cont_b]){
					aux = vet[cont_b]
					vetor[cont_b] = vetor[cont_a]
					vetor[cont_a] = aux
				}
			}
		}
	}
	
}
```
</details>