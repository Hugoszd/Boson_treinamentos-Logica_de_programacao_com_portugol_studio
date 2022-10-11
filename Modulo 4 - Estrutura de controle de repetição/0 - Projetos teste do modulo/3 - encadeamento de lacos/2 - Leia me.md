# Objetivo
Projeto teste perguntando quantos números sortear, sorteando eles e voltando a perguntar (Para dentro de enquanto)

<details>
<summary>Código</summary>

```c
programa
{
	//Biblioteca que gera números aleatórios
	inclua biblioteca Util --> u
	
	inteiro quant_num, i
	
	funcao inicio()
	{
		escreva("Digite zero (0) para encerrar o programa.\n")
		

		//Criando looping de sorteios infinitos
		enquanto(verdadeiro){
			escreva("Digite quantos números deseja sortear: ")
			leia(quant_num)
			
			//Criando condição para encerrar o looping
			se(quant_num == 0){
				pare
			}
			//Criando looping para gerar números aleatórios entre 1 e 100
			para(i = 1; i <= quant_num; i++){
				escreva(u.sorteia(1, 100), "\n")
			}
		}
	}
}
```
</details>