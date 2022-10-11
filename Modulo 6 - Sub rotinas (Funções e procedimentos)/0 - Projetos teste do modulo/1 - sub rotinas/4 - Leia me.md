# Objetivo
Projeto teste: Trabalhando com função sem retorno com mais de um argumento. Crie um software que peça um número inicial e final e mostre todo o range entre eles.

<details>
<summary>Código</summary>

```c
programa
{
	//Criando variáveis
	inteiro num_inicial, num_final
	
	//Criando função com múltiplos argumentos (Mostra números)
	funcao contar_numeros(inteiro x, inteiro y)
	{
		para(inteiro i = x; i <= y; i++){
			se(i == y){
				escreva(i, "\n")	
			}
			senao
				escreva(i, ", ")
		}
	}
	
	
	funcao inicio()
	{
		//Solicitando número inicial e final
		escreva("Digite o número inicial: ")
		leia(num_inicial)
		escreva("Digite o número final: ")
		leia(num_final)
	
		//Limpando a tela e mostrando mensagem
		limpa()
		escreva("Mostrando números do inicial ao final:\n")
		
		//Invocando a função "contar_numeros" para exibir os números de inicial a final
		contar_numeros(num_inicial, num_final)
	}
}
```
</details>