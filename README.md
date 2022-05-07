programa
{
	
	funcao inicio()
	{
	real Mnumero1, Mnumero2, Mnumero3, Mnumero4

		escreva("Digite o primeiro numero:")
		leia(Mnumero1)
		escreva("Digite o segundo numero:")
		leia(Mnumero2)

		
		escreva("\n O resultado do primeiro calculo é:", calcula (Mnumero1, Mnumero2))
		// chama a função no escreva
		
		escreva("\n    Digite o terceiro numero:")
		leia(Mnumero3)
		escreva("Digite o quarto numero;")
		leia(Mnumero4)

		escreva ("\n O resultado do segundo calculo é:", calcula (Mnumero3, Mnumero4), "\n")
		// chama a função no escreva
	}

	// Função que realiza um calculo e retorna o resultado
	funcao real calcula (real a, real b)
	{
		real resultado
		resultado=a+b
		retorne resultado
	}
	
}
