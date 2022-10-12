# Declaração e Atribuição de Variáveis em Lógica de Programação

### Conceito de variável
São areas da memoria onde armazenamos temporariamente dados para processamento durante a execução do programa.

Possui características como :
- Identificação (”Nome”)
- Endereço (Parte onde ela esta na memória. Representada por um número)
- Tipo de dado (Primitivo ou composto)
- Tamanho (Quanto de espaço vai ocupar)
- Valor (”Conteúdo”)
<br/>


#### Representação da memoria
<img src="/Modulo%202%20-%20Variáveis%20tipos%20de%20dados%20e%20operadores/img/001.jpg" width=400px>
<br/>

### Convenção para nomes de variáveis
- Pode ter um ou mais caracteres.
- O primeiro caractere sempre é uma letra.
- Não pode ter espaço em branco.
- Não podemos usar símbolos (Com raras exceções, como no snake case).
- Não podemos usar números.
- Não podemos usar palavras reservadas da linguagem.
<br/>

##### Convenção para nome composto de variáveis
<img src="/Modulo%202%20-%20Variáveis%20tipos%20de%20dados%20e%20operadores/img/002.jpg" width=700px>
<br/>
<br/>

### Declaração e atribuindo valores a variáveis
Quando queremos usar uma variável temos que ter em mente que o primeiro passo é declara-la (criar ela).
- Podemos declarar mais de uma varável por vez
- A criação segue (Tipo de dado + espaço + nome da variável)

```c
//Declarando uma variável (Criando)
int a ;

//Criando mais de uma ao mesmo tempo
int a , b ;
```
<br/>

Após a declaração da variável podemos atribuir dados a ela usando o sinal de “=” (Chamado de sinal de atribuição).
```c
//1° Podemos criar depois atribuir 
int a; 
a = 10;

//2° Podemos criar já atribuindo o valor
int a = 10;

//3° Podemos atribuir o valor de uma variável pra outra
int a =10;
int b = a;
```

<br/>
<br/>

[Voltar para o menu principal](https://github.com/Joshpcbrrj/Boson_treinamentos-Logica_de_programacao_com_portugol_studio)
