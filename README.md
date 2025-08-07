# 🎮 betFifa - Predição de Partidas de FIFA para Apostas Esportivas

Este projeto tem como objetivo prever **probabilidades de vitória de cada jogador** e a **chance de ocorrência de gols (acima de 0.5, 1.5, 2.5, 3.5)** em partidas do FIFA (EsportsBattle), auxiliando em estratégias de apostas esportivas com base em dados históricos.

# Funcionamento

- Um script realiza a extração da base de jogos do site https://football.esportsbattle.com/en/.
- Essa base passa por um tratamento para servir de treinamento para o modelo de predição.
- O modelo calcula as probabilidades de resultado e frequência de gols baseado em nos times, jogadores, campeonato em questão e estádio.
 
## 🧠 O que o modelo prevê?

- Probabilidade de vitória de cada jogador na partida
- Probabilidade de:
  - +0.5 gols
  - +1.5 gols
  - +2.5 gols
  - +3.5 gols
