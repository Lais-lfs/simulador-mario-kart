# Simulador de Corridas do Mario Kart 🏎💨
Jogue o Mario Kart de forma diferente, usando a sua sorte nos dados! 🎲

<table>
  <tbody>
    <tr>
      <td><img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/header.gif" width="150px"></td>
      <td>Mario Kart é um jogo de corrida arcade da Nintendo com personagens icônicos, pistas malucas e itens para atrapalhar os adversários. Aqui o desafio é criar uma lógica de um jogo de vídeo game para simular corridas de Mario Kart, levando em consideração as regras e mecânicas abaixo.
</td>
    </tr>
  <tbody>
<table>


## 💻 Técnicas e tecnologias utilizadas
- `JavaScript`: aplicação da lógica das regras e mecânicas do jogo, como sorteio do número do dado de 6 lados, somatório com as características dos jogadores levando em consideração o tipo de pista sorteado, atribuição de pontos, etc.
- `Node.js`: simulação do jogo pelo terminal.

## 🎮 Jogadores
<table>
  <tbody>
    <tr>
      <td><b>Mario</b> <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/mario.gif" width="70px"></td>
      <td>Velocidade: 4 <br> Manobrabilidade: 3 <br> Poder: 3</td>
      <td><b>Peach</b> <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/peach.gif" width="90px"></td>
      <td>Velocidade: 3 <br> Manobrabilidade: 4 <br> Poder: 2</td>
      <td><b>Yoshi</b> <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/yoshi.gif" width="90px"></td>
      <td>Velocidade: 2 <br> Manobrabilidade: 4 <br> Poder: 3</td>
    </tr>
    <tr>
      <td><b>Bowser</b> <br><br>
        <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/bowser.gif" width="90px"></td>
      <td>Velocidade: 5 <br> Manobrabilidade: 2 <br> Poder: 5</td>
      <td><b>Luigi</b> <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/luigi.gif" width="90px"></td>
      <td>Velocidade: 3 <br> Manobrabilidade: 4 <br> Poder: 4</td>
      <td><b>Donkey Kong</b> <br> <img src="https://github.com/Lais-lfs/simulador-mario-kart/blob/main/docs/dk.gif" width="90px"></td>
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

## 🎲 Como jogar

1. Certifique-se de ter o **Node.js** instalado. <br>
   Para verificar, execute no terminal:  
     ```sh
     node -v
     ```

2. Clone este repositório em seu computador e acesse a pasta do projeto:  
   ```sh
   git clone https://github.com/Lais-lfs/simulador-mario-kart.git
   cd simulador-mario-kart
   ```

3. Instale as dependências:
    ```sh
    npm install
    ```

4. Abra o terminal e inicie o jogo usando o seguinte comando:
    ```sh
    node src/index.js
    ```

5. Divirta-se! 🎮
