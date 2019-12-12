# Felipe-Alves-IA

Aluno: Felipe Dermeval Alves Santos
Matrícula: 31310679

O objetivo proposto para o trabalho é utilizar tipos de buscas para o PACMAN enconrar comidas e saídas em diversos labirintos que são gerados através de instruções codificadas no python.

Comando para busca DFS

python pacman.py -l tinyMaze -p SearchAgent python pacman.py -l mediumMaze -p SearchAgent python pacman.py -l bigMaze -z .5 -p SearchAgent

Comando BFS

python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

Comando UCS

python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs python pacman.py -l mediumDottedMaze -p StayEastSearchAgent python pacman.py -l mediumScaryMaze -p StayWestSearchAgent

Comando A* search

python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic python pacman.py -l trickySearch -p AStarFoodSearchAgent

Vídeos realizados:

Video DFS: https://drive.google.com/open?id=1b9wMcrLjuC-2IR8hkXJwJgDikTMuB0y_

Video BFS: https://drive.google.com/open?id=1oNewmdlPOxB1_-FtUtnX3eZh8KEwmpLc

Video UCS: https://drive.google.com/open?id=1uILDDMcKbZKaVnzppf-MkKErTONdh_Hg

Video A* search: https://drive.google.com/open?id=1TEPOanxPDDMWPslZcDFauLtmsKL0zVew

ATIVIDADE:

(Pergunta 1) A ordem de exploração foi de acordo com o esperado? O Pacman realmente passa por todos os estados explorados no seu caminho para o objetivo? R= Sim o objetivo foi alcançado. Não, pois o mesmo faz uma busca procurando a melhor alternativa para alcançar seu objetivo.

(Pergunta 2) Essa é uma solução ótima? Senão, o que a busca em profundidade está fazendo de errado?

(Pergunta 3) A busca BFS encontra a solução ótima? Senão, verifique a sua implementação. Se o seu código foi escrito de maneira correta, ele deve funcionar também para o quebra-cabeças de 8 peças (seção 3.2 do livro-texto) sem modificações. R= Sim, pois sua busca tem uma precisão maior.

(Pergunta 4) O que acontece em openMaze para as várias estratégias de busca? R= No DFS ele percorre maior parte dos estados explorados e no Ssearch ele percorre distâncias retas que o levam direto para o seu objetivo final.
