# AulaDeMetodos

menuDoPrograma();


criaEPreencheVetor() {
	int[] vetor = new int[5];
	for(int i = 0, i < 5, i++) {
		vetor[i] = read();	
	}
	return vetor;
}

calcularVetorFinal(primeiroVetor, segundoVetor) {
	int[] vetor = new int[5];

	for(int indice = 0, indice < 5, indice++ ) {

	if(primeiroVetor[indice] % 2 == 0) {
		vetor[indice] = primeiroVetor[indice] * segundoVetor[indice];
'	} else {
		vetor[indice] = Math.pow(primeiroVetor[indice], segundoVetor[indice]);
	}

	return vetor;
}


menuDoPrograma(){
	var resposta = "Sim";
	do {
		int[] vetorA = criaEPreencheVetor();
		int[] vetorB = criaEPreencheVetor();

		int[] vetorC = calcularVetorFinal(vetorA, vetorB);
		
		imprimeResultado(vetorC);
		

		System.out.println("Deseja continuar");
		respota = read();
	} while(resposta == "Sim");	
	
}

imprimeResultado(vetor) {
	for(){
		System(vetor[indice])
	}
	
}
