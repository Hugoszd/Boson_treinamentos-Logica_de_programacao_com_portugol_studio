# Objetivo
Projeto teste sorteando 5 números parajogar na loteria

<details>
<summary>Código</summary>

```c
programa
{
	inclua biblioteca Util --> u
	inteiro num_5
	
	funcao inicio()
	{
		escreva("Gerar 5 números para loteria.\n")
		escreva("Os 5 números são: ")
		
		para (num_5 = 1 ; num_5 <=5; num_5++){
			
			escreva(u.sorteia(1, 50), ", ")
		}
		escreva("\n")
	}
}
```
</details>