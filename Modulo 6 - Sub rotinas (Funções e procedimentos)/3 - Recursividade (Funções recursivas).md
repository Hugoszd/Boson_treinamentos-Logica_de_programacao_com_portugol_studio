# Recursividade (Funções recursivas)

### Conceituando
- Recursividade é definida como uma sub rotina que pode invocar a si mesma.
* Para resolver esse problema, a função se divide em 2 casos:
    - Base
    - Geral
<br/>
- Uma função recursiva pode chamar a si mesmo de forma direta ou indireta
    - Direta → Quando invoca a si mesma diretamente.
    - indireta → Quando invoca a si mesma por meio de outra função.
<br/>

### Como funciona a recursividade
- Uma função recursiva é invocada para resolver um problema.

* A função é capaz de resolver diretamente o caso mas simples do problema (Caso base).
    - Quando a função é chamada no caso base ela retorna um resultado.

- Se usarmos essa mesma função em um caso mais complexo, ela o divide em duas partes conceituais:
    - Uma que a função sabe resolver (caso base)
    - E uma que ela não sabe resolver (geral)
<br/>


####💡Operação de recursividade

- Para que a recursividade funcione, a parte que ela não sabe resolver  deve se parecer com o problema original, mas sendo ligeiramente menor ou mais simples que o problema em si.
* A função chama a si própria para tentar resolver o problema maior (Chamada recursiva/ passo recursivo).
- O passo recursivo é executado novamente, sobre uma versão mais simples do problema, até chegar ao **caso base**
<br/>

###### Representação
<img src="/Modulo%206%20-%20Sub%20rotinas%20(Funções%20e%20procedimentos)/img/1.jpg" width="600px">




