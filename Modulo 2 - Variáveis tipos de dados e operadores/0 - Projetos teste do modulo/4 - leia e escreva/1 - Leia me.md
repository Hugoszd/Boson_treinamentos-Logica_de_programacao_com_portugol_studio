# Objetivo
Projeto para testar a função "leia" (recebe dados) e "escreva" (Printa dados).

<details>
<summary>Código</summary>

```c
programa
{
	inteiro valor
	cadeia nome
	
	funcao inicio()
	{
		//Instrução leia

		leia(valor) /*Note: que o leia irá passar um número digitado para que a variavel "valor" armazenar*/
		leia(nome) /*Note: que o leia irá passar uma string digitada para que a variavel "nome" armazenar*/

		//instrução escreva
		escreva(1,"\n") /*Note: Se não insierirmos quebra de linha "\n" as escritas ficaram uma ao lado da outra sem espaço.*/ /*A virgula vai ajudar na  concatenação*/
		escreva("O número digitado foi: " + valor,"\n")/*Note: Para escrita de string, devo por palavra ou frase entre aspas "".*/
		escreva("O texto digitado foi: "+ nome, "\n" )
	}
}
```

</details>