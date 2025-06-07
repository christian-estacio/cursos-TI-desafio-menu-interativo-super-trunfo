# cursos-TI-desafio-menu-interativo-super-trunfo
Desafio: nível aventureiro
Interatividade no Super Trunfo
Menu Interativo

SUPER TRUNFO

OBJETIVO
Ganhar todas as cartas do baralho. 

O JOGO
- O jogo baseia-se na comparação dos valores de sua carta com a do outro jogador. 
- Para sua carta vencer, a característica escolhida precisa ter valor maior ou menor (em alguns casos) do que a carta dos seus adversários.
- Quando sua carta vence, você ganha a carta do seu adversário e a próxima carta de sua pilha aparece para uma nova jogada.
- O placar mostra o número de cartas que você e seus adversários possuem.
- O placar vai se alterando automaticamente a cada rodada.
- Em caso de empate as cartas ficam no monte e um placar mostra quantas cartas estão lá.
- Quando um jogador vencer a próxima rodada, ele ganha todas as cartas do monte.
- OPÇÕES DE BARALHO Existem dezenas de baralhos diferentes de Super Trunfo.
- Este contém 28 cartas com itens relacionados ao orçamento das prefeituras de Santa Catarina.
- Cada tipo tem um grau de dificuldade diferente.
- Escolha aquele que mais lhe agrada e estude bem as informações de cada carta.

COMO JOGAR
1. Observe, para o Super Trunfo escolhido, qual valor vence em cada característica: se o menor ou o maior valor.
2. Para iniciar, escolha entre as informações da sua carta, aquela que você julga ter o valor capaz de vencer as cartas dos seus adversários.  Exemplo: Se você escolher a informação “Educação”, compare com a carta do seu adversário e verifique quem venceu.
3. Se você vencer - a carta do outro jogador irá para trás do seu monte de cartas e você continua escolhendo a informação da sua próxima carta.
4. Se o outro jogador vencer - sua carta irá para trás do monte de cartas dele e a vez de escolher passa para ele.
5. Em caso de empate - as cartas irão para o monte e uma nova disputa é feita, sendo que o jogador que escolheu as cartas que empataram deve escolher novamente. O vencedor ganha as cartas que empataram e estão no monte.
6. Se um dos jogadores que empataram não possuir outra carta para jogar, a anterior volta para a mão dele para ser usada no desempate.
7. CARTA SUPER TRUNFO Existe entre as cartas uma carta SUPER TRUNFO. Esta carta vence todas as cartas do baralho independentemente do valor de suas características. Ela perde apenas para as cartas que tenham a letra A (1A, 2A, 3A, etc), marcado na parte superior de cada uma. 8. Quando a carta SUPER TRUNFO aparecer, a comparação será automática com as cartas dos adversários, sem necessidade de você escolher uma característica de sua carta.  9. FIM DO JOGO O jogo termina quando um dos jogadores ganhar todas as cartas do baralho. 

Menu Interativo: Criar um menu interativo no terminal usando a estrutura switch que permita ao jogador escolher qual atributo será usado para comparar as cartas. O menu deve ser claro e fácil de usar.
 
Comparação de Atributos: Implementar a lógica de comparação entre duas cartas com base no atributo selecionado pelo jogador. Os atributos disponíveis são:
 
Nome do país (string - usado apenas para exibir informações, não para comparação direta)
 
População (int)
 
Área (float)
 
PIB (float)
 
Número de pontos turísticos (int)
 
Densidade demográfica (float - já calculada no desafio anterior).
 
Regras de Comparação: A regra geral é: vence a carta com o maior valor no atributo escolhido. Porém, para a Densidade Demográfica, a regra inverte: vence a carta com o menor valor.
 
Exibição do Resultado: Mostrar na tela, de forma clara, o resultado da comparação, incluindo:
 
O nome dos dois países.
O atributo usado na comparação.
Os valores do atributo para cada carta.
Qual carta venceu.
Em caso de empate, exibir a mensagem "Empate!".

Requisitos não funcionais


Usabilidade: O menu e as mensagens exibidas no terminal devem ser intuitivos e fáceis de entender.
 
Performance: O sistema deve responder rapidamente às ações do usuário.
 
Manutenibilidade: Escreva um código limpo, organizado e bem comentado.
 
Segurança: (Embora menos crítico neste nível, comece a pensar em como seu código poderia lidar com entradas inválidas do usuário, como a escolha de uma opção inexistente no menu. Um default no switch pode ajudar).
 


Simplificações para o nível intermediário


Você pode usar as cartas que já foram cadastradas no desafio anterior. Não é necessário implementar o cadastro novamente neste nível.
 
Foque na criação do menu com switch e na lógica de comparação com if-else (incluindo comparações aninhadas onde fizer sentido).
 
Implemente a comparação para apenas duas cartas.

Entregando seu projeto


Desenvolva seu projeto no GitHub em um repositório público.
 
Certifique-se de que seu código está bem comentado e que o arquivo README.md do seu repositório contém instruções claras de como compilar e executar seu programa. Inclua exemplos de como usar o menu e quais são os atributos disponíveis para comparação.
 
Envie o link do seu repositório do GitHub no SAVA.
