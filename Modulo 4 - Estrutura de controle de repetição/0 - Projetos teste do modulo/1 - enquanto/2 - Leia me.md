# Objetivo
Projeto teste: De bem vindo a x usuários.

<details>
<summary>Código 1° forma</summary>

```c
programa
{

	cadeia nome_do_us
	
	funcao inicio()
	{
		escreva("Digite seu nome ou aperte X para parar o programa: ")
		leia(nome_do_us)

		enquanto (nome_do_us != "x"){
			escreva("\nBem vindo ", nome_do_us, " !")

			/* Solicitando mais dados a cada volta*/
			escreva("\nDigite seu nome ou aperte X para parar o programa: ")
			leia(nome_do_us)
		}
		escreva("\nAsta la vista, baby !")
	}
}
```
</details>

<details>
<summary>Código 2° forma</summary>

```c
programa
{
	cadeia nome

	funcao inicio()
	{
		//Gerando looping infinito proposital
		enquanto(verdadeiro){
			escreva("Digite seu nome ou X para sair: ")
			leia (nome)
			se(nome == "x"){
				pare
			}
			escreva("\nSeja bem vindo: ",nome, "\n")
		}
	}
}
```
</details>