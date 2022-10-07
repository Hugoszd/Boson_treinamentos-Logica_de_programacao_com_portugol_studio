# Objetivo
Projeto para testar de calculador de equação de segundo grau (▲)

<details>
<summary>Código</summary>

```c
programa
{
	inteiro a, b, c, delta 
	
	funcao inicio()
	{
		escreva("Calculo do ▲ de uma equação do segundo grau \n")
		
		escreva("Digite o valor de a: ")//Digitando a.
		leia(a)
		
		escreva("Digite o valor de b: ")//Digitando b.
		leia(b)

		escreva("Digite o valor de c: ")//Digitando c.
		leia(c)

		escreva("\nEquação ficou: " + a + "x² + " + b + "x + " + c + " = 0")//Demostrando equação.

		
		delta = b * b - 4 * a * c /*Calculando Delta*/
		escreva("\nO ▲ da equação é: ", delta,"\n")//Mostrando o resultado de ▲ (delta) na tela
	}
}
```

</details>