#🧙‍♂️ RogueSurvive

Um mini jogo roguelike feito com **Pygame Zero**, onde o jogador controla um herói que precisa sobreviver a inimigos(goblin, troll e um ciclope) e mata-los em menos de 60 segundos, pode-se utilizar de duas poções randomicamente no cenario, que recuperam 50% de vida.

#🎮 Como Jogar

- Use as **teclas W, A, S, D** para mover o herói.
- Pressione **barra de espaço (SPACE)** para atacar inimigos próximos.
- Sobreviva por **60 segundos** para vencer.
- Colete poções para recuperar vida.
- Se a vida chegar a 0, o jogo termina.
- Se enconstar nos inimigos duas vezes sem recuperar life, sem que ataque-os, é: "Game Over"

#📜 Controles

| Tecla       | Ação                 |
|-------------|----------------------|
| W / A / S / D | Movimentar o herói  |
| Espaço       | Atacar               |
| Mouse        | Navegar no menu      |

#🧾 Funcionalidades

- Animações simples de movimento e ataque.
- Menu com opções: Iniciar Jogo, Ativar/Desativar Som, Sair.
- HUD com barra de vida, inventário, nível e cronômetro.
- Sistema de vitória/derrota baseado em tempo ou morte do herói.
- Inimigos aleatórios e poções espalhadas no mapa.

#🛠 Requisitos
- Python
- [Pygame Zero](https://pygame-zero.readthedocs.io)

Instale com:

. bash
. pip install pgzero


Para rodar o jogo:

. bash
. pgzrun nome_do_arquivo.py

# ⚔️ Classes/raças
   
. Guerreiro
. Goblin
. Troll
. Ciclope


# 📁 Recursos Esperados

- 'hero_walk.png', 'hero_attack1.png', 'hero_attack2.png'
- 'goblion_idle.png', 'goblion_walk.png'
- 'troll_idle.png', 'troll_walk.png'
- 'cyplops_idle.png', 'cyplops_walk.png'
- 'potion.png'
- 'cave_bg.png'
- 'bg_music.mp3'
-  Som opcional de movimento ('move.wav')
-  Som de hit ('hit.wav')
-  Som de ataque ('attack.wav')
-  Som de loot ('loot.wav')
-  Som de levelup ('levelup')

# 🚀 Inspiração

" O roguelike é um jogo com uma visão de cima em que todos os objetos e personagens são colocados nos quadrados do mundo do jogo. O movimento dos personagens entre as células deve ser suave e animado. "

- Este projeto independente e autoral, é um joguinho simples e que serve também como base para jogos roguelike em 2D e pode ser expandido com sistemas de inventário, geração procedural, mais inimigos, e muito mais.
