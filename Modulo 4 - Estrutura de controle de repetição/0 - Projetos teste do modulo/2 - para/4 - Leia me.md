# Objetivo
Projeto teste sorteando x numeros com para

<details>
<summary>Código</summary>

```c
programa
{
	inclua biblioteca Util --> u
	inteiro quant_num, num
	
	funcao inicio()
	{
		escreva("Digite a quantidade de número que quer sortear: ")
		leia(quant_num)
		
		para (num = 1 ; num  <= quant_num; num ++){
			
			escreva(u.sorteia(1, 50), ", ")
		}
		escreva("\n")
	}
}
```
</details>