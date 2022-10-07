# O que é Escopo de Variáveis ?

### Conceitos de escopo de variáveis
- Escopo se refere ao local onde ela é declarada e acessada, e  ao seu tempo de vida (duração).
- Variáveis somente podem ser usadas dentro do escopo no qual elas foram criadas.
<br/>

### Escopo das variáveis
| Variáveis globais  | Variáveis locais |
| --- | --- |
| Se tornam visíveis em todo o programa (Escopo amplo). | se tornam visíveis somente no local onde foram declaradas (Escopo restrito). |
| Declaradas no inicio do programa, ou em um local especial (dependendo da linguagem usada) | Declaradas dentro de funções e métodos. |
| Existe durante todo o tempo de vida do programa. | Existe somente enquanto a função onde foi declarada estiver sendo executada. |
| Permite que compartilhemos seus dados com funções e métodos. | Seus dados só podem ser usados dentro da função ou método que está inserida. |
<br/>

<aside>
💡OBS : Temos que usar as variáveis globais com cuidado pois por padrão o programa já será iniciado salvando elas na memória. O uso exagerado de variáveis no escopo global pode sobre carregar o uso da memoria durante a execução. Outro detalhe é que erros em variáveis globais são mais complicados para analisar durante a depuração.
</aside>