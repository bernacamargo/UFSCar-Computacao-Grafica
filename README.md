## Computação Gráfica
Repositório das atividades da disciplina de Computação Gráfica, ministrada pelo Pr° Dr° Mario Liziér em 2019/1 do curso de Ciência da Computação da Universidade Federal de São Carlos.

#### Integrantes:

- Bernardo Camargo [@bernacamargo](https://github.com/bernacamargo)
- Angelo de Souza [@angelobzsouza](https://github.com/angelobzsouza)
- Mariane Malheiros [@maryanne25](https://github.com/maryanne25)

#### Descrição:

Este projeto utiliza a biblioteca JavaScript [threeJS](https://github.com/mrdoob/three.js/) com o objetivo de analisar e estudar o comportamento objetos 3D.

Atividade 1 - Entrega: 07/05

- Visualização de um modelo mais complexo, contendo um número maior de vértices e faces, fornecidos por um arquivo (por exemplo, obj);
- Utilização simples de shaders, apenas redimensionamento para o volume de visão;
  Sem posicionamento correto, textura, iluminação, animação, etc...


Atividade 2 - Entrega: 04/06

- Visualização de pelo menos dois objetos diferentes;
- Alguma iteração do usuário (teclado ou mouse), movendo pelo menos um dos objetos 
- Construção das matrizes na CPU para envio a GPU:
- Matriz de Transformação do modelo (uma diferente para cada modelo);
- Matriz de Visualização (uma para toda a a cena).
- Duas posições distintas de câmeras
# Projeto de Computação Gráfica 2019
## Universidade Federal de São Carlos - Sorocaba
Repositório de atividades do curso de Computação Gráfica, ministrada pelo Pr° Dr° Mario Liziér em 2019/1 no curso de Ciência da Computação da Universidade Federal de São Carlos.

#### Integrantes:

- [Angelo Souza](https://github.com/angelobzsouza) - 726496
- [Bernardo Camargo](https://github.com/bernacamargo) - 620343
- [Mariane Malheiros](https://github.com/maryanne25) - 

---
#### Objetivo:
O objetivo desse projeto é utilizar e implementar conceitos de computação gráfica. Conceitos como carregamento de objetos, aplicação de texturas, movimentações e interações com o usuário e a criação dos shaders serão abordados ao longo das fases de desenvolivmento.

#### Descrição
O projeto foi desenvolvido utlizando a bibliteca [Three.js](https://github.com/mrdoob/three.js/) que utiliza o WebGL para a criação e manipulação de modelos 3D.

#### Setup
Para abrir o projeto, basta executar o arquivo index.html na pasta de cada atividade para visualizar o desenvolvimento do mesmo até aquela determinada fase.

---

### Fases e Terefas Realizadas

#### Atividade 1 - Entrega: 07/05

- Visualização de um modelo mais complexo, contendo um número maior de vértices e faces, fornecidos por um arquivo (por exemplo, obj);
  - Foi adicionado o modelo de um carro a cena
- Utilização simples de shaders, apenas redimensionamento para o volume de visão;
  - Utilizamos as classes da Three.js para realizar esse item
- Interação com o usuário
  - Foi adicionada a posiblidade de mover o carro para "frente" ou para "trás". Lembrando que esses termos são genéricos, uma vez que não há pontos de refência ainda


#### Atividade 2 - Entrega: 04/06

- Visualização de pelo menos dois objetos diferentes;
  - Foi adicionado o modelo de uma árvore a cena
- Interação com o usuário;
  - Além do controle do carrinho, também foi adicionado a possibilidade de trocar de câmera através dos botões numéricos
- Construção das matrizes na CPU para envio a GPU:
  - As matrizes são fornecidas como parâmetros para a rendeziação do objeto, portanto, estão fora da CPU e são enviadas para a GPU
- Matriz de Transformação do modelo (uma diferente para cada modelo)
  - Matrizes utilizadas para inserir os objetos em cena
- Matriz de Visualização (uma para toda a a cena);
  - Matrizes utilizadas para criar câmeras diferentes
- Duas posições distintas de câmeras
  - São utilizadas duas posições de cameras diferentes. Essas posições são alteradas utlizando uma matriz de transformações.
- Vizualição dos eixos em cena
  - Foi adicionada uma visualização dos eixos x, y e z para facilitar o entendimento dos conceitos para o grupo ao longo dessa e das próximas fases
- Luz na cena
  - Foi adicionado luz na cena para ter uma melhor visualização dos objetos
