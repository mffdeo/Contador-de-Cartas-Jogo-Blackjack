# Contador-de-Cartas-Jogo-Blackjack

No jogo de casino Blackjack, um jogador pode determinar se tem uma vantagem sobre a próxima mão da casa, mantendo o número relativo de cartas altas e baixas restantes no baralho. Isso se chama "contar as cartas". <br>

Ter cartas mais altas restantes no baralho favorece o jogador. A cada carta é atribuído um valor de acordo com a tabela abaixo. Quando o contador for positivo, o jogador deve apostar alto. Quando a contagem for zero ou negativa, o jogador deverá apostar baixo. <br>

Mudança na contagem	Cartas<br>
+1 --->	2, 3, 4, 5, 6 <br>
 0 ---> 7, 8, 9 <br>
-1 --->	10, 'J', 'Q', 'K', 'A' <br>
<br>Você vai escrever uma função de contagem de cartas. A função receberá um parâmetro card, que pode ser um número ou uma string, e incrementar ou decrementar a variável global count de acordo com o valor da carta (veja a tabela). Em seguida, a função retornará a string com o valor atual de contagem (variável count) e a string Bet se a contagem for positiva, ou Hold se a contagem for zero ou negativa. A contagem atual e a decisão do jogador (Bet ou Hold) deve ser separado por um único espaço. <br>

Exemplo de saída: -3 Hold ou 5 Bet
