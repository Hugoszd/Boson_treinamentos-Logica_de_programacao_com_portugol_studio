# Como criar e manipular Matrizes (Vetores bi dimensionais)

### Conceituando matriz
- Em matemática, uma matriz (m por n) é um conjunto de elementos dispostos na linha ( m ) e colunas( n ).
- São vetores de 2 dimensões (Linhas e colunas), lembrando uma tabela. Algo como vetores interligados.
- Na programação costumamos usar ( i ) para indicar linha e ( j ) para indicar a coluna do elemento.
- A matriz geralmente é representada por uma letra maiúscula.
<br/>

#### Representação de matriz na matemática
<img src="/Modulo%205%20-%20Estrutura%20de%20dados%20básica/img/9.jpg" width="600px">
<br/>

#### Na computação usa-se matriz para diversos tipos de representações
Exemplos:
- Representação de imagens.
- Dados para plotagem de gráficos.
- Mapeamento e cálculos de distância.
- Jogos 2d
- Implementação de estruturas  de dados especiais.
- Cálculos tabulares (Como em planilhas).
  
Entre outras finalidades
<br/>

#### Entendendo a contagem usada na matriz na programação
Observação
- Note, a numeração de linhas e colunas se inicia em zero. Portanto, a última posição será sempre n -1.
- Note, sempre vamos começar a contar a linha e depois a coluna, para identificar a posição de um dado
  
<img src="/Modulo%205%20-%20Estrutura%20de%20dados%20básica/img/10.jpg" width="500px">
<br/>

O valor 22 está na posição ( 0,0 ).

O valor 15 está na posição ( 2,1 ).

O valor 32 está na posição ( 1,2 ).

O valor 96 está na posição ( 3,2 ).
<br/>

###### Sintaxe para a declaração de matriz no Portugol studio

```c
tipo_de_dado nome_da_matriz[x][y]
/*OBS:*/ 
// x e y correspondem ao número de linhas e colunas da  matriz, repectivamente.
// A quantidade de objetos que podem entrar na matrizserá resultado de (x * y).
```

<br/>

###### Também podemos declarar matrizes com constantes

```c
const inteiro x = 5
const inteito y = 3

inteiro matriz[x][y]
```

<br/>

###### Podemos acessar ou atribuir dado de a posição específica da matriz

```c
//Inserindo
nome_da_matriz[pos_em_x] [pos_em_y] = valor_que_queremos_inserir

//escrevendo na tela
escreva(nome_da_matriz[pos_em_x] [pos_em_y])
```

<br/>
<br/>

[Voltar para o menu principal](https://github.com/Joshpcbrrj/Boson_treinamentos-Logica_de_programacao_com_portugol_studio)



