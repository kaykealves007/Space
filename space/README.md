
1.  ![CAPITAL CODE-LOGO](http://capitalcode.com.br/spacecapital.jpg)

2.  # [Capital Code](http://capitalcode.com.br)- Space Capital, conheça os planetas de uma forma diferente! #

3.  ![VERSÃO DO SW](https://img.shields.io/badge/Spacel%20Capital--%20version-v.1.1.7-blue.svg)

4.  ![CURSO](https://img.shields.io/badge/Curso-01-orange.svg)
	![CURSO02](https://img.shields.io/badge/Curso-02-green.svg)

5.  O **Space  Capital**  é uma nova forma de interagir com os planetas, com um simples toque na superfície do
6.  planeta você consegue ver a sua distância em km até o sol.

7.  O Space  Capital foi feito totalmente com Javascript e Jquery, apresentando assim o mais alto desempenho
8.  no  Front-end.

9.  ## Interação com o usuário

10.  O evento do clique, aciona a função que seta as informações sobre o planeta:

11.  <div class="planet p-1" onclick="setDistancia('90')">

12.  ## Número com animação

13.  Ao clicar no botão, a função "setDistancia"  é chamada e uma animação do contador é realizada dessa forma:

14.  function setDistancia($distancia){
15.  $('#distancia').animateNumber({ number: $distancia })
16.  }

17.  ## Plugin para contador

18.  -  [jquery-animateNumber](https://github.com/aishek/jquery-animateNumber)

19.  Para mais informações acesse [a nossa plataforma](http://capitalcode.com.br).