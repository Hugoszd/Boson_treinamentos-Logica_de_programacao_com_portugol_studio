# Ordenação de Vetores com o algoritmo Selection Sort

### Conceito
- É possível ordenar as posições de um array em ordem crescente ou decrescente.
- Um método simples que podemos usar para organizar as posições é o `selection sort`.
<br/>

<aside>
💡 OBS: Existem outros algoritmos de organização de arrays que podemos ver. Tais como:

- Bubble sort
- Cocktail shaker sort
- Heapsort
- insertion sort
- Merge sort
- Quicksort
</aside>

#### Algoritmo de troca de posições de um array de acordo com o ordenamento (Para o exemplo vamos usar um array de 3 posições)
<aside>
💡 Lembrando : Aqui também vamos precisar de uma variável auxiliar, como visto na aula de “Rotina de Troca de Valores entre Variáveis”
</aside>
<br/>

Etapa 1: Vamos comparar as 2 primeiras posições. 
1. Se o valor da pos 0 for menor do que pos 1, os valores se mantem onde  estão.<br/><br/>
2. Se o o  valor de pos 0 for maior do que pos 1, o valor de pos 0 é copiado para auxiliar, pos 1 é copiado para pos 0 e auxiliar é copiado para pos 1.<br/><br/>
3. Vamos seguir comparando pos zero com as demais posições e fazendo sempre como nos passo a e b em todas essas etapas.
<br/>

Etapa 2: Vamos comparar as próximas 2 casas e agir como vimos no passo 1 até montarmos nosso vetor em ordem crescente. (Número total de comparação $\frac{(n^2 - n)}{2}$ → Onde “n” é o número de elementos do vetor).

  * No caso que vimos fica: $\dfrac {9 - 3}{2} = 3$ . Total de 3 comparações.
