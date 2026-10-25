# Raízes de Alagoas

Jogo educativo de plataforma 2D sobre a história de Alagoas, para estudantes do ensino fundamental. O jogador acompanha João, um estudante de 14 anos que é levado a momentos marcantes da história do estado.

Desenvolvido no **Programa Semente de Iniciação Científica (PSIC) do Centro Universitário CESMAC**, em 2024 e 2025.

## Fases

| Fase | Período histórico |
|---|---|
| 1 | Criação da Capitania de Alagoas (1817) e o primeiro governador, Sebastião de Melo e Póvoas |
| 2 | Cabanada (1832): cabanos e indígenas contra os senhores de engenho e o governo imperial |
| 3 | Proclamação da República (1889) e Deodoro da Fonseca |
| 4 | Cangaço (anos 1930): Lampião nas redondezas de Arapiraca |

Cada fase tem cutscenes de abertura e de encerramento com o contexto histórico, além de menu, seleção de fases, tela de game over e créditos.

## Mecânicas

- Movimentação lateral, pulo e pulo duplo.
- Inimigos eliminados ao serem pisados; ao ser tocado por um inimigo ou cair do mapa, o jogador volta ao início da fase.
- Diálogos com personagens históricos e câmera que acompanha o jogador.

## Tecnologias

Unity 6 (6000.0.37f1), C#, Universal Render Pipeline 2D, Timeline e Input System.

## Equipe

- Luana Karoline Lira Mateus
- Rafaela Urtiga Malta
- João

Orientação: Prof. Carlos Alberto Correia Lessa Filho (CESMAC).

### Contribuição de Rafaela Urtiga Malta

- Movimentação e personalização dos personagens, com ajuste de tamanho e velocidade (`Player.cs`).
- Mecânicas de fase: eliminação do inimigo ao ser pisado e retorno ao início da fase ao ser tocado ou ao cair.
- Sistema de vida, morte e reinicialização da fase (`Player rafa/ColisorGameOver.cs`, `ResertarMilitarTrigger.cs`, `ResetarViuvaTrigger.cs`).
- Câmera que acompanha o jogador (`Player rafa/CameraPlayer.cs`).
- Início dos diálogos.

## Créditos de arte e música

- Arte: assets gratuitos do OpenGameArt, Cainos (Pixel Art Platformer – Village Props) e Simple Pixel UI, além de imagens geradas com ChatGPT.
- Músicas: AVGVSTA (OpenGameArt).

Os assets de terceiros pertencem aos seus autores e seguem as licenças originais.

## Como abrir

1. Instale o Unity Hub e o editor Unity 6000.0.37f1.
2. Clone o repositório e abra a pasta pelo Unity Hub.
3. Abra a cena `Assets/_Main/Scenes/Menu.unity` e clique em Play.
