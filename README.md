# Simulador de Mario Kart
Jogue o jogo do Mario Kart de forma diferente, usando a sorte nos dados.

## Objetivo
Mario Kart é uma série de jogos de corrida desenvolvida e publicada pela Nintendo. Nosso desafio será criar uma lógica de um jogo de vídeo game para simular corridas de Mario Kart, levando em consideração as regras e mecânicas abaixo.

## 💻 Técnicas e tecnologias utilizadas
- `JavaScript`: aplicação da lógica das regras e mecânicas do jogo, como sorteio do número do dado de 6 lados, somatório com as características corretas dos jogadores, atribuição de pontos, etc.
- `Node.js`: simulação do jogo pelo terminal.

## 🎮 Jogadores
<table>
  <tbody>
    <tr>
      <td>Mario <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/mario.gif" width="80px"></td>
      <td>Velocidade: 4 <br> Manobrabilidade: 3 <br> Poder: 3</td>
      <td>Peach <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/peach.gif" width="100px"></td>
      <td>Velocidade: 3 <br> Manobrabilidade: 4 <br> Poder: 2</td>
      <td>Yoshi <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/yoshi.gif" width="100px"></td>
      <td>Velocidade: 2 <br> Manobrabilidade: 4 <br> Poder: 3</td>
    </tr>
    <tr>
      <td>Bowser <br><br>
        <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/bowser.gif" width="100px"></td>
      <td>Velocidade: 5 <br> Manobrabilidade: 2 <br> Poder: 5</td>
      <td>Luigi <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/luigi.gif" width="100px"></td>
      <td>Velocidade: 3 <br> Manobrabilidade: 4 <br> Poder: 4</td>
      <td>Donkey Kong <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/dk.gif" width="100px"></td>
      <td>Velocidade: 2 <br> Manobrabilidade: 2 <br> Poder: 5</td>
    </tr>
  </tbody>
</table>

## 🕹️ Regras e Mecânicas:
**Jogadores:**

O Computador deve receber dois personagens para disputar a corrida em um objeto cada.

**Pistas:**

- Os personagens irão correr em uma pista aleatória de 5 rodadas
- A cada rodada, será sorteado um bloco da pista que pode ser uma **reta**, **curva** ou **confronto**
  - Caso o bloco da pista seja uma **RETA**, o jogador deve jogar um dado de 6 lados e somar o atributo **VELOCIDADE**, quem tiver o maior somatório vence e ganha um ponto.
  - Caso o bloco da pista seja uma **CURVA**, o jogador deve jogar um dado de 6 lados e somar o atributo **MANOBRABILIDADE**, quem tiver o maior somatório vence e ganha um ponto.
  - Caso o bloco da pista seja um **CONFRONTO**, o jogador deve jogar um dado de 6 lados e somar o atributo **PODER**, quem tiver menos pontos perde a rodada e um ponto.
  - Nenhum jogador pode ter pontuação negativa (valores abaixo de 0).

Condição de vitória:
- Ao final, vence o jogo quem acumulou mais pontos.
