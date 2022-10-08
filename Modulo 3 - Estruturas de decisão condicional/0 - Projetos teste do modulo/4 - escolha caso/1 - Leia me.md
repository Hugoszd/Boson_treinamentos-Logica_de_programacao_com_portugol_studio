# Objetivo
Projeto teste escolha a letra

<details>
<summary>Código</summary>

```c
programa
{	
	caracter opcao
	
	funcao inicio()
	{
		escreva("Digite uma letra: Opções válidas são apenas (a, b, c): ")
		leia(opcao)
		
		escolha(opcao){
			caso 'a':
				escreva ("A opção escolhida foi a letra (A) \n")
				pare
			caso 'b':
				escreva ("A opção escolhida foi a letra (B) \n")
				pare
			caso 'c':
				escreva ("A opção escolhida foi a letra (C) \n")
				pare	
			caso contrario:
				escreva("Vc digitou uma opção inválida \n")
		}
	}
}
```
</details>