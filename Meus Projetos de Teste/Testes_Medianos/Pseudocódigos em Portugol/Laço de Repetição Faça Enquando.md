//Função deste algoritmo: calcular a média aritmética do total das vendas do primeiros 4 meses do ano
//Autor: Aquiles Mauro (Zero ILumi)

programa
{
	
	funcao inicio()
	{
	 inteiro contador, limite, resultado, qualtabuada
	 contador = 0
	 limite = 10
	 escreva("qual tabuada você quer: ")
	 leia(qualtabuada)
	 escreva("qual o limite você quer de multiplicador: ")
	 leia(limite)
	 		faca
	 		{
	      	resultado = qualtabuada*contador
	      	escreva("\n"+qualtabuada+"x"+contador+"="+resultado)
	      	contador ++
	 		}enquanto(contador<=limite)
	}
}