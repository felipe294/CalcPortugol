# CalcPortugol
É uma calculadora escrita em portugol

programa
{
	funcao inicio()
	{
		cadeia nome, op
		real n1, n2, res
		escreva("---Calculadora gentil---")
		escreva("\nAntes de usar a calculadora vamos falar um pouco!")
		escreva("\nQual o seu nome? ")
		leia(nome)
		limpa()
		se (nome == "Felipe" ou nome == "felipe"){
			escreva("Nome lindo senhor ",nome,"!")
			escreva("\nVamos ver The simpsons depois? hehe")
		}senao{
			escreva("Belo nome ",nome,"!")
			escreva("\nAgora teste a calculadora")
		}
		escreva("\n\nEscolha um operador: ")
		leia(op)
		limpa()
		escreva("Insira o primeiro valor: ")
		leia(n1)
		limpa()
		escreva("Insira o segundo valor: ")
        escreva(n1, " ", op, " ")	
		leia(n2)
		limpa()
		
		se (op == "×" ou op == "*"){
			res = n1*n2
		}senao se (op == "÷" ou op == "/"){
			res = n1/n2
		}senao se (op == "+"){
			res = n1+n2
		}senao se (op == "-"){
			res = n1-n2
		}senao{
			res = 0.0
		}
		escreva("Resultado: ",n1," ",op," ",n2," = ",res)
		escreva("\n\nOBRIGADO E TCHAU")
	}
}
