# Computação Gráfica - UFABC

## Atividade 1

- Nome dos integrantes: Fernando Schroder / Gabriel Yuto
- RAs: 11---- / 11201721879
- Link WebAssembly: https://gabrielyuto.github.io/computacao-grafica-atividade-1/atividade-1/index.html

## Descrição da aplicação:

Utilizando como base a aplicação relacionada a geração de triângulos coloridos, o objetivo deste projeto é explorar as funcionalidades dos widgets presentes na biblioteca Dear ImGui e nos modos das primitivas suportadas pelo OpenGL.
Dessa forma, por meio de um ComboBox, criamos um seletor de primitivas que permite alterar de modo dinâmico o parâmetro que é passado ao GLDraw. Dentre as geometrias exploradas, incluimos no comboBox as seguintes definições:

- GL_POINTS: cada vértice forma um ponto que será desenhado na tela como um pixel ou como um quadrilátero centralizado no vértice. O tamanho do ponto/quadrilátero pode ser definido pelo usuário17;
- GL_LINES: cada grupo de dois vértices forma um segmento de reta;
- GL_LINE_STRIP: os vértices são conectados em ordem para formar uma polilinha;
- GL_LINE_LOOP: os vértices são conectados em ordem para formar uma polilinha, e o último vértice forma um segmento com o primeiro vértice, formando um laço;

![Primitivas](images/gl-primitivas.png)

(notas de aulas)
