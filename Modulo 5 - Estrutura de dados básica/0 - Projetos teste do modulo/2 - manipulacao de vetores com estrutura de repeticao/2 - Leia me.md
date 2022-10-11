# Objetivo
Projeto teste: Crie um programa que leia 5 números de matrícula de alunos. Depois de criado, o programa permite que sejam consultadas as matrículas de forma independente, e mostra a mensagem (uma por vez) informando se cada número está ou não presente na lista cadastrada (Consulta de matrículas). O programa deve ser encerrado se o usuário apertar a tecla “n”.

<details>
<summary>Código</summary>

```c
programa
{	
	//Criando as variáveis
	inteiro vetor_matr[5]
	inteiro i,j, consulta, mat_existe
	caracter continua = 's' //Iniciando o caracter com "s" de "sim".
	cadeia vetor_aluno[5]
	
	funcao inicio()
	{
		//Laço para guardar o cadastro da matricula e nome do aluno
		para(i = 0; i <= 4; i++){
			escreva("Cadastre ", i + 1, "°,número de matrícula: ")
			leia(vetor_matr [i])
			escreva("Informe o nome do aluno: ")
			leia(vetor_aluno[i])
			escreva("\n")	
		}

		//limpando dados da tela
		limpa()
		
		//Lopping para consulta de matrículas 
		enquanto((continua == 's') ou (continua == 'S')){	
			escreva("Digite a matricula que quer consultar: ")
			leia(consulta)

			//Laço para varrer o vetor tentando achar a matrícula
			para(i = 0; i <= 4; i++){
				se(consulta == vetor_matr [i]){
					mat_existe = 1
				}
			}

			//Condição caso encontre a matricula
			se (mat_existe == 1){
				escreva("\nMatricula encontrada.\n")
				
			}

			//Condição caso não encontre a matrícula
			senao{
				escreva("\nMatricula não encontrada.\n")
			}

			//Laço para informar a matricula e o nome do aluno ao final.
			para(i = 0; i <= 4; i++){
				se(consulta == vetor_matr [i]){
					escreva ("A matrícula é: ",vetor_matr [i], "\n")	
					escreva("O nome do aluno é: ",vetor_aluno[i],"\n")
				}
			}

			//Bloco para perguntar se "continua" a busca ou para
			escreva("\nSe quiser consultar novamente ? digite 's' de sim , ou 'n' de não: ") 
			leia(continua)
			limpa()
		}

	}
}
```
</details>