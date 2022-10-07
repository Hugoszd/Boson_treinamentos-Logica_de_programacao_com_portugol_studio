# Operadores Lógicos e, ou e não (Operadores booleanos)

### Conceitos
- Permite trabalhar com múltiplas condições relacionais na mesma expressão.
- Retornam valores lógicos de (verdadeiro/true ou falso/false).
<br/>

### Tabela dos operadores lógicos
###### Operador E (AND)
O Operador “E” ou “AND” resulta em um valor VERDADEIRO se os dois valores de entrada da operação forem VERDADEIROs, caso contrário o resultado é FALSO. 

| Valor 1  | Valor 2 | Operação E (AND) |
| --- | --- | --- |
| Verdadeiro | Verdadeiro | Verdadeiro |
| Verdadeiro | Falso | Falso |
| Falso | Verdadeiro | Falso |
| Falso | Falso | Falso |
<br/>

###### Operador ou (OR)
O Operador “OU” ou “OR” resulta em um valor VERDADEIRO se ao menos UM dos dois valores de entrada da operação for VERDADEIRO, caso contrário o resultado é FALSO.

| Valor 1  | Valor 2 | Operação ou (OR) |
| --- | --- | --- |
| Verdadeiro | Verdadeiro | Verdadeiro |
| Verdadeiro | Falso | Verdadeiro |
| Falso | Verdadeiro | Verdadeiro |
| Falso | Falso | Falso |
<br/>

###### Operador não (NOT)
O Operador “NÃO” ou “NOT” é o único operador que recebe como entrada apenas um valor, e sua função é simplesmente inverter os valores. Ou seja, se o valor de entrada for VERDADEIRO, o resultado será FALSO e se o valor de entrada for FALSO, o resultado será VERDADEIRO.

| Valor de entrada | Operação não (NOT) |
| --- | --- |
| Verdadeiro | Falso |
| Falso | Verdadeiro |
<br/>

---

### Tabela  de negação dos operadores lógicos
###### Operador NÃO-E (NAND)
O Operador “NÃO-E” ou “NAND” é o contrário do operador E (AND), ou seja, resulta em VERDADEIRO, se ao menos um dos dois valores for FALSO, na verdade este é o operador E (AND) seguido do operador NÃO (NOT).

| Valor 1 not | Valor 2 not | Operador NÃO-E (NAND) |
| --- | --- | --- |
| Verdadeiro | Verdadeiro | Falso |
| Verdadeiro | Falso | Verdadeiro |
| Falso | Verdadeiro | Verdadeiro |
| Falso | Falso | Verdadeiro |
<br/>

###### Operador NÃO-OU (NOR)

| Valor 1 not | Valor 2 not | Operador NÃO-OU (NOR) |
| --- | --- | --- |
| Verdadeiro | Verdadeiro | Falso |
| Verdadeiro | Falso | Verdadeiro |
| Falso | Verdadeiro | Verdadeiro |
| Falso | Falso | Verdadeiro |
<br/>

---

### Tabela de operadores exclusivos
###### Operador OU-EXCLUSIVO (XOR)
O Operador “OU-EXCLUSIVO” ou “XOR” é uma variação interessante do operador OU (OR), ele resulta em VERDADEIRO se apenas um dos valores de entrada for VERDADEIRO, ou seja, apenas se os valores de entrada forem DIFERENTES.

| Valor 1 X | Valor 2 X | Operação XOR |
| --- | --- | --- |
| Verdadeiro | Verdadeiro | Falso |
| Verdadeiro | Falso | Verdadeiro |
| Falso | Verdadeiro | Verdadeiro |
| Falso | Falso | Falso |
<br/>

###### Operador NÃO-OU-EXCLUSIVO (XNOR)
O Operador “NÃO-OU-EXCLUSIVO” ou “XNOR” é o contrário do operador OU-EXCLUSIVO (XOR), ou seja, resulta VERDADEIRO se os valores de entrada forem IGUAIS.
| Valor 1 X | Valor 2 X | Operação Xnor |
| --- | --- | --- |
| Verdadeiro | Verdadeiro | Verdadeiro |
| Verdadeiro | Falso | Falso |
| Falso | Verdadeiro | Falso |
| Falso | Falso | Verdadeiro |
