# Objetivo
Projeto para testar o escopo global e local das variáveis

<details>
<summary>Código</summary>

```c
programa
{//Escopo global
	
	real numero_global //Criando variável global
	
	funcao inicio()
	{//Escopolocal
		
		numero_global = 10.0 /*Startando variável global*/
		real numero_local_inicio = 12.0 /*Criando e startando variável local*/

		escreva("O numero global é: " + numero_global + "\n")
		escreva("O numero local da func inicio é: " + numero_local_inicio + "\n")
		escreva("A multi. de numCalcula por numGlobal é: "+ calcula() + "\n")
		escreva("Foi tudo !!! Agora, segue o baile." + "\n")
	}
	
	funcao real calcula() //Criando função global do tipo "real".
	{
		real numero_local_calcula = 5.0 //Variável local de "calcula"
		retorne numero_local_calcula * numero_global //Retorno da função "calcula".
	}
}
```

</details>