## 🎮 betFifa - Predição de Resultado em Partidas de FIFA.

Este projeto tem como objetivo prever **probabilidades de vitória de cada jogador** e a **chance de ocorrência de gols (acima de 0.5, 1.5, 2.5, 3.5)** em partidas de FIFA.

### Overview

- Um script realiza a extração da base de jogos do site https://football.esportsbattle.com/en/.
- Essa base passa por um tratamento para servir de treinamento para o modelo de predição.
- O modelo calcula as probabilidades de resultado e frequência de gols baseado em nos times, jogadores, campeonato em questão e estádio.
 
### 🧠 O que o modelo deve prever?

- Probabilidade de vitória de cada jogador na partida
- Probabilidade de:
  - +0.5 gols
  - +1.5 gols
  - +2.5 gols
  - +3.5 gols

### Estrutura

![alt text](efifa_predictor\src\imgs\image.png)