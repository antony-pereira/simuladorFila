# Simulador de Fila em um Posto Bancário
Projeto desenvolvido para a disciplina `Modelagem e Avaliação de Desempenho de Sistemas Computacionais`
## Explicação
Todo o código está bem comentado, basicamente a ideia é simular o tempo de fila em um posto bancário, a primeira versão era com apenas 1 atendente, a versão final requisitada pela professora seria com a opção de escolher quantos atendentes existem antes de iniciar a simulação, fizemos isso e o programa se adapta e faz os cálculos corretos baseado nessa escolha.

É feita a geração do tipo de cada cliente aleatoriamente, o tipo determina o seu TS (tempo de serviço). 

Depois disso toda a simualação é feita e todos os resultados guardados (TEC,TS, Tempo chegada no Relogio, Tempo Inicio de Serviço, Fim de Serviço, Tempo na Fila, Tempo Total no Sistema e Tempo ocioso)

Com isso são feitas algumas médias de cada simulação, com elas fazemos a média das médias e o desvio padrão, tendo esses 2 valores é feito o cálculo do Intervalo de Credibilidade de cada um.

No código é possivel visualizar alguns gráficos que foram usados no relatório entregue, além de toda explicação e resultados comparativos com 1, 2 e 3 caixas. 
