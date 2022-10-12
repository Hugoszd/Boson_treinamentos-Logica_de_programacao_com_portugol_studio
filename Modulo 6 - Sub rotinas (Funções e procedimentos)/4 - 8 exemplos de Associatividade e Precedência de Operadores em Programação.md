# 8 exemplos de Associatividade e Precedência de Operadores em Programação

<details>
<summary>Referencia</summary>
<a href="http://www.bosontreinamentos.com.br/logica-de-programacao/resumo-basico-de-operadores-em-programacao/">Bóson treinamentos em ciência e tecnologia (Básico de operadores)</a>
</details>

### Regras de precedência
Avalia qual será o operador a ser avaliado primeiro numa expressão onde temos operadores adjacentes.

```c
/*Exemplo 1: */
a + b * c 
//Será executado primeiro a multiplicação depois a soma.

/*Exemplo 2: */
(a + b) * c
//Será executado o que esta em parenteses  primeiro e depois o que vem fora dele.
```
<br/>

### Regra de associatividade
Avalia qual operador será avaliado primeiro quando 2 operadores possuem a mesma ordem de precedência e são adjacentes em uma expressão.

```c
/*Exemplo 1*/
a + b - c 
//Note, a soma easubtração possuem a mesma precedência.  
//A associetividade vai fazer ed primeiro a operação a esquerda (soma) depois a dirita (sub). 
```
<br/>

### Ordem de precedência dos operadores
<img src="/Modulo%206%20-%20Sub%20rotinas%20(Funções%20e%20procedimentos)/img/2.jpg" width="800px">

<br/>
<br/>

[Voltar para o menu principal](https://github.com/Joshpcbrrj/Boson_treinamentos-Logica_de_programacao_com_portugol_studio)

