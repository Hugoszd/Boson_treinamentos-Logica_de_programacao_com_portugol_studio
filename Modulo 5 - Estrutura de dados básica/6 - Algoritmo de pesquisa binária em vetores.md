# Algoritmo de pesquisa binária em vetores

<details>
<summary>Página de cálculos Omni (Diversas bases para calculo)</summary>

<a href="https://www.omnicalculator.com/math/log-2">Omni calculator</a>
</details>

### Destaques
* A pesquisa binária é um item procurado em uma lista ordenada. como temos ordenamento, a pesquisa se torna mais eficiente,
- Divide ao meio a parte da lista que pode conter o item (espaço de busca), comparando o elemento procurado com o elemento do meio da lista, até que sobre apenas um local possível para a busca.
* Aqui temos o paradigma “Dividindo para conquistar”.
<br/>

<aside>
<p>📎 OBS :  A busca linear só irá funcionar se o vetor analisado estiver ordenado de valor menor para o maior.</p>
<img src="/Modulo%205%20-%20Estrutura%20de%20dados%20básica/img/6.jpg" width="600px">
</aside>
<br/>

#### Representação exemplo de arvore binária
<img src="/Modulo%205%20-%20Estrutura%20de%20dados%20básica/img/7.jpg" width="500px">

###### Note
Queremos achar o número 6, por exemplo.
1. A divisão do vetor é dada no número 4.
2. Se o 6 for maior que 4 procuraremos na direita, se não for procuraremos na esquerda.
3. Seguindo, com a procura a direita, vamos dividir o vetor no 7.
4. Como 6 é menor que 7, procuraremos na esquerda.
5. Lá esta o número 6, conforme vemos na figura (Usamos 3  passos para achar).
<br/>

#### Entendendo a sintaxe
Dado o array abaixo, como acharíamos o número 7 ?
<img src="/Modulo%205%20-%20Estrutura%20de%20dados%20básica/img/8.jpg" width="800px">

```c
//Vamos precisar de 4 variaveis 
inicial = 0 //indica inicio do vetor
final = 9 // indica final do vetor
meio //Criamos a variável para definir depois qual será o meio.
encontrado = falso //Variavel flag para nos sinalizar se foi encontrado ou não.

//1° Vamos definir o meio 
meio = 4 

//2° Comparamos o valor 7 com o valor do meio. 
7 > 4 // Então procuraremos a direita do meio (4)

//3° Agora vamos mudar o valor de "Inicial", que será a primeira posição depois do meio (4)
inicial = 5 //Atribuindo novo inicio do vetor
final = 9 //A posição final neste caso se mantem

//4° Agora vamos atribuir o novo meio
meio = 7 //Atribuindo novo  meio do vetor

//5° Vamos começar comparando o número que queremos achar com esse novo meio
7 == 7 //Aqui já o podemos parar pois já achamos o 7.

//6° Como encotramos,a variável sinalizadora vai ser alterada para "verdadeiro"
encontrado = verdadeiro
```
<br/>
<br/>

[Voltar para o menu principal](https://github.com/Joshpcbrrj/Boson_treinamentos-Logica_de_programacao_com_portugol_studio)




