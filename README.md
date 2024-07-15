<h1>Terminal RPG</h1>

<h2>Descrição do Projeto</h2>

Um RPG de terminal desenvolvido como trabalho acadêmico para a disciplina de Estrutura de Dados.
Este projeto visa demonstrar a aplicação prática de conceitos fundamentais de estruturas de dados em um ambiente de jogo interativo.
O jogo foi feito em C++ utilizando a biblioteca ncurses para fornecer uma interface de texto.

<h2>Objetivo do Projeto</h2>

Este projeto tem como objetivo: <br>
<ul>
  <li>Aplicar conceitos de estruturas de dados em um contexto prático.</li>
  <li>Desenvolver habilidades em C++.</li>
  <li>Criar um jogo interativo que demonstre a utilização de fila e lista duplamente encadeada.</li>
</ul>

<h2>Funcionalidades do Jogo</h2>
<ul>
  <li><b>Interface de texto:</b> Foi utilizada a biblioteca ncurses para uma experiência de terminal. O jogo é todo feito em ASCII.</li>
  <li><b>Sistema de combate por turnos:</b> Implementado usando a estrutura de fila para gerenciar a ordem dos ataques entre o jogador e os inimigos.
  Nos turnos, tanto o inimigo quanto o jogador podem errar o ataque, atacar normalmente ou atacar com poder especial. O poder especial tem chance de 50% de sangramento no defensor.</li>
  <li><b>Inventário:</b> Implementado usando a estrutura de lista duplamente encadeada. Em que é possível coletar itens e escolher quais serão utilizados.</li>
</ul>

<h2>Demonstração</h2>

Aqui está um pequeno vídeo do jogo em ação:

[![20240715-0648-38 6451372](https://github.com/user-attachments/assets/1d10db92-6895-4d51-88b2-628f920d93de)](https://github.com/user-attachments/assets/60030478-367b-48bc-909c-e94e9cf3eb0f)

<h2>Como executar o jogo</h2>

1. Clone o repositório:
```bash
  $ git clone https://github.com/isaheloisah/RPG-em-C-.git
````
2. Navegue até o repositório do projeto.
3. Compile o código:
```bash
  g++ -o main main.cpp game.cpp -lncurses
````
4. Execute o jogo:
```bash
  ./main
````

<h1>Requisitos</h1>

<ul>
  <li>C++11 ou superior</li>
  <li>Biblioteca ncurses</li>
  <li>Terminal do Linux. Caso você deseja executar no Windows, recomendo o Cyngwin</li>
</ul>

<h2>Contribuições</h2>

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests com melhorias ou correções.
