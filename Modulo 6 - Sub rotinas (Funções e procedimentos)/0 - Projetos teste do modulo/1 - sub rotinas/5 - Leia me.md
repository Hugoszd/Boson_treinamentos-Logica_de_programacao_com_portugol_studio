# Objetivo
Projeto exemplo: Crie um programa que use uma função para calcular e retornar a área de um círculo, solicitando ao usuário o valor do raio (r) da circunferência. A área do circulo é dada por: $A = \pi * r^2$  .

<details>
<summary>Código</summary>

```c
programa
{
	//Incluindo biblioteca matemática (Para pegar o valor de PI)
	inclua biblioteca Matematica --> m

	//Criando variáveis
	real raio
	real area_total

	//Função para calcular a área de uma circunferencia
	funcao real calcula_area (real r)
	{
		real area_circulo = 0.0
		area_circulo = m.PI *r *r
		retorne area_circulo
	}
	
	funcao inicio()
	{
		escreva("Digite o raio do circulo em cm: ")
		leia(raio)

		//Retornando o valor da função "calcula_area" para a variável "area_total" (Usando raio digitado como parametro)
		area_total = calcula_area(raio)

		//Escrevendo a area do circulo na tela
		escreva("A area do círculo é: ", area_total, "cm^2\n")
	}
}
```
</details>