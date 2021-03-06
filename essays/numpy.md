---
layout: essay
type: essay
title:  Biblioteca Numpy
# All dates must be YYYY-MM-DD format!
date: 2019-12-02
labels:
  - Numpy
  - Bibliotecas ML
  - Aprender ensinando
---


## O que é NumPy?

<p>Quando os modelos matemáticos começaram a demandar um poder computacional muito grande, viu-se a necessidade de uma biblioteca que permitisse trabalhar com arranjos, vetores e matrizes de N dimensões, assim nasceu o NumPy, a principal biblioteca científica do Python e que se equipada com o software proprietário Matlab. NumPy foi implementado em C, por isso sua grande velocidade na realizações das operaçÕes matemáticas.</p>

<p>Para a utilização dessa biblioteca, há a necessidade de instalação. No windows, já com o Python instalado, abra o prompt de comando em modo administrador e digite: </p>

<img class="ui fluid medium image" src="../images/numpy4.png">

<p>Terminado a instalação, basta fechar o prompt de comando e já é possível utilizar o NumPy junto ao Python com o comando: import numpy</p>

<p>Como todas as bibliotecas é possível utilizar um apelido para a mesma, uma boa prática ao utilizar numpy é apelida-lo de np:</p>
	
<img class="ui fluid medium image" src="../images/importnumpy.png">

<p>Com o NumPy importado, podemos criar arrays, abaixo o exemplo de 1D e 2D:</p>

<p>Nesse exemplo, foi criado uma lista de elementos e em seguida ela foi transformada em um arranjo, com isso ganhamos muitas vantagens para trabalhar com esses números</p>

<img class="ui fluid image" src="../images/numpy1.png">
	
<p>Com esse arranjo, trabalhar com elementos matemáticos em cada item se torna muito rápido. No exemplo, é possível ver uma lista multiplicada por um dado número e um arranjo multiplicado por esse número, no segundo caso cada valor é multiplicado individualmente:</p>

<img class="ui fluid image" src="../images/numpy2.png">
	
<img class="ui fluid image" src="../images/numpy3.png">

<p>Visualizamos uma sequência númerica em uma dimensão (1D), podemos ter 2D, 3D e nD, visualmente fica cada vez mais dificil exemplificar, mas NumPy se torna uma ferramenta incrível e extremamente rápida para lidar com uma grande quantidade de números, exatamente por essas execuções simultâneas em grandes dimensões.</p>

<img class="ui fluid image" src="../images/numpy5.png">

<p>Com quatro dimensões, podemos imaginar um array contendo diversos arrays de três dimensões.</p>

<p>No exemplo abaixo vemos a multiplicação de matrizes sendo feita sem a função especifica do NumPy, ele expande os arranjos e executa as operações matemáticas.</p>

<img class="ui fluid image" src="../images/numpy6.png">

<p>Utilizando a função "dot" conseguimos efetuar a multiplicação dos arranjos da maneira correta, conforme a algebra linear</p>

<img class="ui fluid image" src="../images/numpy7.png">


<p>Abaixo algumas outras funções do NumPy que permite gerar matrizes com todos os elementos 0, 1 ou com valores aleatórios, muito úteis em algumas aplicações.</p>

<img class="ui fluid image" src="../images/numpy8.png">
	









