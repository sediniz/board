Criação de Projeto Board para o Gerenciamento de Tarefas
O projeto foi criado para acompanhar a criação de tarefas e serão utilizadas pelos individuos

Os requisitos para a criação dos boards :
1 - O codigo deve iniciar disponibilizando um menu com as seguintes opções: Criar novo board, selecionar board, excluir boards e sair;

2 - O codigo deve salvar o board com suas informações no banco de dados MySQL;

Regra dos boards:
1 - Um board deve ter um nome e ser composto por pelo menos 3 colunas: 1 - coluna onde o card é colocado inicialmente, 2 - coluna para cards com tarefas concluidas e 3 - coluna para cards cancelados e a nomeclatura das colunas é de escolha livre.

2 - As colunas tem seu respectivo nome, ordem que aparece no board e seu tipo: inicial, cancelamento, final e pendente.

3 - Cada board so pode ter 1 coluna do tipo inicial, cancelamento e final, colunas do tipo pendente podem ter quantas forem necessarias.

4 - As colunas podem ter 0 ou N cards, cada card tem o seu titulo, descrição, data de criação e se está bloqueado.

5 - Um card deve navegar nas colunas seguindo a ordem delas no board, sem pular nenhuma etapa, exceto pela coluna de cards cancelados que pode receber cards diretamente de qualquer coluna que não for a coluna final.

6 - Se um card estiver marcado como bloqueado ele não pode ser movido até ser desbloqueado.

7 - Para bloqeuar um card deve-se informr o motivo de seu bloqueio e para desbloquea-lo deve-se também informar o motivo.

Menu de manipulação de board selecionado:
1 - O menu deve permitir mover o card para procima coluna, cancelar um card, criar um card, bloquea-lo, desbloquea-lo e fechar board.
Requisitos opcionais
1 - Um card deve armazenar a data e hora em que foi colocado em uma coluna e a data e hora que foi movido pra a proxima coluna.

2 - O codigo deve ser gerar um relatorio do board selecionado com o tempo que cada tarefa demorou para ser concluida com informações do tempo que levou em casa coluna.

3 - O codigo deve gerar um relatorio do board selecionado com os bloqueios dos cards, com o tempo que ficaram bloqueados e com a justificativa dos bloqueios e desbloqueios.
 
