# ativida10-ex10
programa
{
	
	funcao inicio()
	{
		real populacaoA = 80000.0
		real populacaoB = 200000.0

		real crescimentoA = (populacaoA / 100) * 3
		real crescimentoB = (populacaoB / 100) * 1.5
		inteiro anos = 0

			para (crescimentoA ; populacaoA <= populacaoB ; populacaoA = ((populacaoA / 100) * 3) + populacaoA){
				populacaoB = ((populacaoB / 100) * 1.5) + populacaoB
				anos = anos +1
				escreva ("\nPopulação A = ", populacaoA ,"\nPopulação B = ", populacaoB,"\n\n")
			}
		
		escreva ("\nPopulação A = ", populacaoA ,"\nPopulação B = ", populacaoB,"\n\n")
		escreva("Se passaram ",anos," anos para a População A se igualar ou ser maior que População B")
	}
}
