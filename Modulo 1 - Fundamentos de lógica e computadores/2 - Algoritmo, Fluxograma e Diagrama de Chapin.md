# Algoritmo, Fluxograma e Diagrama de Chapin
### Reforçando conceito de algoritmo
- Sequência de instruções ordenada, finita e não ambígua que são executadas mecanicamente para fazer uma tarefa.
- O algoritmo deve ter um fim, pode se comunicar com o mundo exterior, e executar suas instruções em um tempo finito.
- Cada linha do algoritmo deve executar uma única instrução.
- Como uma receita de bolo.
<br/>

#### Exemplo de algoritmo para fazer o café com filtro de papel (Descrição narrativa)
<img src="/Modulo%201%20-%20Fundamentos%20de%20lógica%20e%20computadores/img/004.jpg" width=400px>
<details>
  <summary>Observação:</summary>
    <p>1 - Temos algumas ações que podem ser desdobradas em ações menores (Como: “7. ferva a agua). A essas ações damos o nome de <b>não primitivas</b>.</p>
    <p>2 - Ja ações que não podem ser desdobradas em menores (Como: “1. pegue o coador”) damos o nome de <b>primitivas</b>.
    <p>Ferver a agua é um sub algoritmo. Podemos desenvolve-lo a parte :</p>
    <img src="/Modulo%201%20-%20Fundamentos%20de%20lógica%20e%20computadores/img/005.jpg" width=300px>
</details>
<br/>

<aside>
💡 OBS: O objetivo do algoritmo computacional é de chegar nas ações primitivas. Desenvolver a lógica de instruções até chegar em partes indivisíveis.
</aside>
<br/>

#### Como representar um algoritmo ?
Podemos usar de alguns meios para criar a parte conceitual do nosso algoritmo. Isso vai nos facilitar na hora de elaborar previamente os passos que vamos seguir posteriormente usando a linguagem de programação.
<p><b>Algumas formas de elaborar esses passos são : </b></p>

###### Português estruturado (Foco desse curso)
* Vamos representar o programa com uma instrução por linha usando a nossa linguagem normal. Temos o inicio e o fim do programa e entre esses 2 termos vamos escrever as instruções. Lembrando que apenas uma instrução por linha. 
<br/>

###### Fluxograma  (Veremos um pouco)
* Descreve o fluxo de dados e instruções usando desenhos geométricos básicos. Esses desenhos possuem representações para entrada, saída e processamento dos dados. Indicado para algoritmos de pouca extensão.

<p>Simbologia básica dos fluxogramas :</p> 
<img src="/Modulo%201%20-%20Fundamentos%20de%20lógica%20e%20computadores/img/006.jpg" width=500px>
<br/>
<img src="/Modulo%201%20-%20Fundamentos%20de%20lógica%20e%20computadores/img/007.jpg" width=500px>
<br/>

###### Diagrama de Chapin
* Desenvolvido inicialmente por Nassi Shneiderman e ampliado por Ned Chapin. **Substitui o fluxograma tradicional por um diagrama de quadros** que apresenta uma visão hierárquica e estruturada da lógica do programa. Facilita a codificação do algoritmo por representar melhor algumas coisas, como recursividade.
<img src="/Modulo%201%20-%20Fundamentos%20de%20lógica%20e%20computadores/img/008.jpg" width=280px>
<br/>

#### Exemplo de algoritmo
Problema: Calcular a média de um aluno baseado nas 4 notas que recebeu no ano. Em caso onde aluno tirou nota 7 ou superior, o aluno estará aprovado. Caso tire nota menor que 7, o aluno estará reprovado.

###### Algoritmo em português
<img src="/Modulo%201%20-%20Fundamentos%20de%20lógica%20e%20computadores/img/009.jpg" width=350px>
<br/>

###### Algoritmo em fluxograma
<img src="/Modulo%201%20-%20Fundamentos%20de%20lógica%20e%20computadores/img/010.jpg" width=450px>
<br/>

###### Algoritmo em diagrama de Chapin (Estrutograma)
<img src="/Modulo%201%20-%20Fundamentos%20de%20lógica%20e%20computadores/img/011.jpg" width=700px>