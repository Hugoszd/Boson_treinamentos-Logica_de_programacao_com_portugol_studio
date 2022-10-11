# Sub rotinas (Funções e Procedimentos)

### Conceituando
* ub rotinas são blocos de código que definem tarefas que o programa pode usar várias vezes durante sua execução, podendo inclusive serem utilizados em outros programas.
- Sub rotinas podem ser utilizadas para cumprir tarefas específicas de um programa.
* Os comandos que definem as sub rotinas são escritos apenas uma vez, e  são escondidos  de outras rotinas.
- Os 2 tipos principais de sub rotinas são: Procedimentos e funções.
<br/>
<aside>
💡 OBS : Geralmente funções e procedimentos são criados no escopo global do programa.
</aside>
<br/>

### Função vs procedimento
| Procedimentos | Função |
| --- | --- |
| Sub rotina que executa uma tarefa sem retornar resultado ao chamador. É uma função sem retorno. | Sub rotina que executa uma tarefa, como o procedimento, porém retorna um resultado (valor) ao chamador. É uma função com retorno. |
<br/>

###### Sintaxe para criar sub rotina
```c
funcao[tipo_retorno] nome_da_funcao ([tipos_de_argumentos_necessarios])
{
	Código_da_funcao
	[retorne] valor_de_retorno //Caso necessário (Se tiver retorno  eu tenho que determinar o tipo)
}
```
<br/>

#### Chamada de sub rotina
- Após criar a função temos que invocar ela em outro local (Processo chamado de “call” ou invocação da  função).
- Lembrando que a sub rotina sempre apresenta informações, como argumentos, do que ela necessita  para realizar sua tarefa.
<br/>

#### Invocando procedimentos
- O procedimento solicitará os argumentos que ele precisa para funcionar.
- Após realizar o processo, o programa continuará as execuções de código abaixo do procedimento.
<br/>

#### Invocando função 
- A função também irá solicitar os argumentos que ela precisa para funcionar.
* Como ela retorna valor, teremos que armazenar esse valor em algum lugar (Geralmente dentro de uma variável).
- O valor também pode ser retornado para outra função ou procedimento.

```c
variável_de_gravação_para_retorno = nome_da_função ([argumentos])

//OBS: Também vamos ter casos que o retorno da função é usado diretamente em outra função.
```
<br/>

#### Usando mais de um argumento na função
- Vamos separar  os argumentos por vírgula.
- Cada argumento deve ter seu tipo especificado.
  
Sintaxe:

```c
funcao nome_da_função (tipo arg1, tipo arg2, tipo arg3, tipo argn)
{
	Código_da_função
}
```
<br/>

#### Trabalhando com funções com retorno
- Permite retornar ao chamador um valor gerado dentro de uma sub rotina, que será a chamada de função.
- Esse retorno diferencia uma função sem retorno (Procedimento) de uma função (função com retorno).
- O retorno da função deve ser gravado em algum lugar (geralmente dentro de uma variável).
- O retorno deve ter um tipo especificado (numero, caractere, cadeia  etc).
- O retorno é a última coisa a ser executada na nossa função com retorno.
  
Sintaxe:
```c
funcao tipo_de_retorno nome_da_função ([tipo argumento])
{
	Código_da_função
	retorno valor_a_ser_retornado
}
```

