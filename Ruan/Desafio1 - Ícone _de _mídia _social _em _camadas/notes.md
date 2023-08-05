# Anotações do Projeto Mídia social

- Criar as camandas utilizando a tag <span>.

- Transformação 2D ou 3D de um elemento.

- Transições CSS

- Opacidade / tranparência do CSS

- Hover

- nth-child ()

## Tag <span>

A tag <span> é um contêiner embutido usado para marcar uma parte de um texto ou uma parte de um documento. É facilamente estilizada por CSS ou manipulada com JavaScript usando o atributo class ou id. É também muito parecida com o elemento <div>, mas <div> é um elemento de nível de bloco e <span> é um elemento inline. 

## Propriedade de tranformação CSS 2D

A  propriedade transform aplica uma transformação 2D ou 3D a um elemento. Esta propriedade permite girar, dimensionar, mover, inclina, etc., elementos.

- O translate ()método move um elemento de sua posição atual (de acordo com os parâmetros fornecidos para o eixo X (horizontal) e o eixo Y (vertical)). No exemplo abaixo o elemento esta movendo 50px para direita e 100px para baixo conforme sua posiução atual. 

transform: translate (50px, 100px);

- O rotate() método gira um elemento no sentido horário ou anti-horário de acordo com um determinado grau. No exemplo abaixo o elemntyo está movendo 20 graus para a direita. número positivo rotaciona para a direita e número negativo rotacionaoara esquerda.

transform: rotate(20deg);

- O scale()método aumenta ou diminui o tamanho de um elemento (de acordo com os parâmetros fornecidos para largura e altura). 
transform: scale(2, 3);

Diminuindo 

transform: scale(0.5, 0.5)

Podemos também Aumenta ou diminuir somente a lagura utilizando o eixo X e y.

Aumentando eixo X (horizontal) e eixo y (vertical)

transform: scalex(2)
transform: scaley(2)

Diminuindo eixo X (horizontal) e eixo y (vertical)

transform: scalex(0.5)

transform: scaley(0.5)

- O skew() um método inclina um elemento ao longo dos eixos X e Y pelos ângulos fornecidos. O exemplo a seguir inclina o elemento <div> 20 graus ao longo do eixo X e 10 graus ao longo do eixo Y:

div {
  transform: skew(20deg, 10deg);
}

Se o segundo parâmetro não for especificado, ele terá um valor zero. Portanto, o exemplo a seguir inclina o elemento <div> 20 graus ao longo do eixo X:


div {
  transform: skew(20deg);
}

Podemos também inclinar somente o X ou Y especificadamente.

O exemplo a seguir inclina o elemento <div> 20 graus ao longo do eixo X:

div {
  transform: skewX(20deg);
}

O exemplo a seguir inclina o elemento <div> 20 graus ao longo do eixo Y:

div {
  transform: skewY(20deg);
}

- O matrix()método combina todos os métodos de transformação 2D em um.

O método matrix() recebe seis parâmetros, contendo funções matemáticas, que permitem girar, dimensionar, mover (traduzir) e inclinar elementos.

Os parâmetros são os seguintes: matrix (scaleX(), skewY(), skewX(), scaleY(), translateX(), translateY())

div {
  transform: matrix(1, -0.3, 0, 1, 0, 0);
}







    
