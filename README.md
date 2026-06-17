# Ping Pong Game (GameMaker)

Um jogo de ping pong clássico e simples desenvolvido no GameMaker. O projeto suporta partidas contra a Inteligência Artificial (Singleplayer) ou confrontos locais entre dois jogadores (Multiplayer).

## 🚀 Funcionalidades
* **Modo 1 Jogador:** Jogue contra uma IA com dificuldade balanceada.
* **Modo 2 Jogadores:** Desafie um amigo localmente no mesmo teclado.
* **Controle de Pontuação:** Marcador automático de pontos na tela.
* **Mecânica Clássica:** Física simples de colisão e aceleração da bola.

## 🎮 Como Jogar

### Controles
* **Jogador 1 (Esquerda):** * `W` - Mover para cima
    * `S` - Mover para baixo
* **Jogador 2 / IA (Direita):**
    * `Seta para Cima` - Mover para cima
    * `Seta para Baixo` - Mover para baixo
* **Reiniciar Partida:** `R`
* **Sair do Jogo:** `Esc`

## 🛠️ Pré-requisitos
Para abrir e editar este projeto, você precisará do:
* [GameMaker](https://gamemaker.io/) (versão LTS ou estável recente)

## 📁 Estrutura do Projeto
O projeto utiliza os seguintes recursos básicos do GameMaker:
* `Objects`: `obj_player1`, `obj_player2` (ou `obj_ia`), `obj_ball` e `obj_game_control`.
* `Sprites`: Sprites simples para as raquetes, bola e interface gráfica (GUI).
* `Rooms`: `rm_menu` (opcional) e `rm_game` (sala principal do jogo).

## 📝 Como Executar
1. Baixe ou clone este repositório.
2. Abra o GameMaker e selecione **Open Project**.
3. Navegue até a pasta do projeto e selecione o arquivo `.yyp`.
4. Clique no botão **Run** (ou pressione `F5`) para testar o jogo.

## 📄 Licença
Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
