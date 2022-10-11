# Declaração e Atribuição de valores a Vetores

### Conceito
- Vetor é um array de uma só dimensão.
- Equivale a uma lista de dados.
- Os vetores só armazenam dados do mesmo tipo.
- Podemos acessar os dados individualmente através dos indices.
- A primeira posição do vetor é : `numero_inicial -1` ou zero
- Altima posição do vetor é : `numero_final - 1`
<br/>

#### Representação
<img src="/Modulo%205%20-%20Estrutura%20de%20dados%20básica/img/4.jpg" width="700px">
<br/>

###### Sintaxe
```c
tipo nome_vetor[quant_de_posições]
```
<br/>

### Atribuindo valor a posição do vetor
```c
/*OBS: Usaremos como exemplo um vetor de 4 posições*/

//Atribuindo valor após declaração:
/*Aqui vamos precisar informar o valor total de posições do vetor*/
inteiro vetor[4]
vetor[0] = 1
vetor[1] = 2
vetor[2] = 3
vetor[3] = 4

//Atribuindo valor na declaração:
/*Aqui não vamos precisar informar o valor total de posições do vetor*/
/*Os valores são atribuidos entre chaves e separados por virgula*/
inteiro vetor[] = {1, 2, 3, 4}
```
