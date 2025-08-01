O código em questão implementa um O código em questão implementa um jogo simples chamado "Jogo do Número Secreto". A lógica do jogo é a seguinte:

1) Inicialização:

    Ao carregar, o jogo define um número secreto aleatório entre 1 e 100.

    Ele armazena os números já sorteados em uma lista (listaDeNumerosSorteados) para evitar repetições. A lista é reiniciada quando todos os 100 números possíveis já foram sorteados.

    Uma mensagem inicial é exibida na tela pedindo ao jogador para escolher um número.

2) Mecânica do Jogo:

    O jogador insere um chute em um campo de texto.

    Quando o jogador clica no botão para verificar o chute, o código compara o valor inserido com o número secreto.

    Se o chute estiver correto, uma mensagem de parabéns é exibida, informando o número de tentativas que o jogador levou para acertar. O botão "Novo Jogo" é ativado para
    permitir que o jogador recomece.

    Se o chute estiver incorreto, o jogo dá uma dica ao jogador, informando se o número secreto é maior ou menor que o chute.

    O número de tentativas é incrementado a cada chute incorreto, e o campo de texto é limpo para o próximo palpite.

4) Reiniciar o Jogo:

    A função reiniciarJogo() é chamada quando o jogador clica no botão correspondente.

    Ela gera um novo número secreto, limpa o campo de texto, redefine a contagem de tentativas para 1, exibe a mensagem inicial e desabilita o botão "Novo Jogo" novamente,
    preparando o jogo para uma nova rodada.


Em essência, o código cria uma experiência interativa de adivinhação, gerenciando o estado do jogo (número secreto, contagem de tentativas) e a interface com o usuário por meio de 
funções que manipulam o conteúdo exibido na tela e os elementos do jogo.
