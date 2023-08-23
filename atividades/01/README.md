# GDD (Game Design Document)

Um "Game Design Document" (GDD) é um documento crucial para o desenvolvimento de jogos, pois descreve em detalhes a visão, a mecânica e todos os elementos importantes do jogo. Embora o conteúdo exato de um GDD possa variar dependendo do projeto, alguns tópicos importantes que geralmente são incluídos são:

1. **Visão Geral do Jogo:**
   - Shooter com perspectiva over-the-top; gameplay loop baseado em fases onde o personagem controlado pelo jogador deve limpar a arena de inimigos. A variedade e quantidade de inimigos muda de acordo com a dificuldade.
   
2. **Mecânica de Jogo:**
   - Movimentação: O player movimenta o personagem pelas teclas "WASD"
   - Combate: A mira do jogador é controlada pelo mouse; O botão esquerdo dispara a arma empunhada pelo jogador
   - Interações com o cenário: Caixas de armas serão espalhadas pelo nível, estas caixas representam upgrades que deixaram o jogador mais forte
   - Inimigos: Os inimigos se aproximarão do jogador, caso consigam encostá-lo, o jogador perde vida (HP)
3. **História e Narrativa:**
   - Personagem principal do jogo será o aluno da UniFil GAL LEVY; Os inimigos serão diversos tipos de zumbis Judeus.
   - Numa nova remanescência de neo-nazis do Discord que decidem dominar o mundo com uma arma química que transforma os Judeus em zumbis, o protagonista Gal Levy - O Último Judeu luta contra seus inimigos para salvar a raça judaica.
4. **Personagens e Inimigos:**
   - O personagem principal Gal Levy conta com o armamento inicial de uma pistola. Este armamento pode ser melhorado ao coletar caixas de upgrade espalhados pelos níveis - Armas mais fortes e armaduras que aumentam a vida do jogador podem ser encontradas nessas caixas
   - .
5. **Níveis e Ambientes:**
   - Haverá 2 níveis, um com ambientação diurna e outra noturna, esta última, o player jogará com visibilidade limitada, trazendo um desafio maior.
   - Layout dos níveis, obstáculos e itens importantes.
6. **Arte e Estilo Visual:**
   - Direção de arte, estilo gráfico e referências visuais.
   - O jogo será renderizado em 3D, personagens e ambientação são inspirados no jogo de tabuleiro Zombicide. Utilizaremos assets prontos do marketplace do Unity para os modelos de personagem principal, inimigos e ambientação. 
   
7. **Áudio e Trilha Sonora:**
   - Efeitos sonoros assim como os modelos virão do marketplace da Unity, trilha sonorá será composta por músicas não-licenciadas escolhidas pelos desenvolvedores
   - Nível noturno e diurno terão trilhas sonoras diferentes, sendo diurno músicas com estilo de uplifting e noturno dark.
8. **Interface do Usuário (UI):**
   - Design da interface do usuário, incluindo menus, HUD e outras telas de interação.
   - Haverão 3 telas - Tela inicial¹; Tela de seleção de nível²; Tela de pausa³
   - Tela: Menu principal¹
        Conteúdo:
        * Título do jogo
        * Botões: Novo jogo; Seleção de fase; Sair do jogo
   - Tela: Seleção de nível²
        Conteúdo:
        * Nome da tela
        * Botões: Fases(Diurna/Noturna); Voltar ao menu principal
   - Tela: Menu de pausa3
        Conteúdo:
        * Nome da tela
        * Botões: Retomar jogo; Voltar ao menu principal
9. **Progressão e Recompensas:**
   - A progressão do jogo acontecerá nos níveis; Conforme o jogador elimina inimigos, mais fortes os mesmos ficam. O jogador terá acesso a um arsenal mais forte conforme ele explora o nível.
   - Inimigos tem chance de derrubar itens que fortalecem o jogador (armas e armadura).
10. **Controle de Jogo e Mapeamento de Teclas:**
    - Movimentação
    - - As teclas "A" e "D" movimentam o personagem no eixo X.
    - - As teclas "W" e "S" movimentam o personagem no eixo Y.
    - Combate
    - - O ponteiro do mouse direciona a mira do personagem.
    - - O botão esquerdo do mouse dispara a arma do jogador.
11. **Fluxo do Jogo:**
    - Diagrama de fluxo que mostra como o jogador avança pelo jogo e como as partes se conectam.
12. **Considerações Técnicas:**
    - Plataformas de destino: PC
    - Requisitos de desempenho e otimização.
13. **Equipe de Desenvolvimento:**
    - Leone Raffo -
    - Leandro Ribeiro -
    - Pedro Paulo -
    - Bruno Marchese -
    - Gal Levy -
14. **Cronograma de Desenvolvimento:**
    - Planejamento do tempo estimado para diferentes fases do desenvolvimento.
