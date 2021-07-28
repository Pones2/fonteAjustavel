# Fonte Ajustavel
## Fonte Tensão ajustável feita para a Disciplina: SSC0180 - Eletrônica para Computação
## Gabriel Barbosa 12543415 | Felipe Momma 12543700 | Murillo Martins 12701599
<br></br>
<h2>Descrição do Projeto</h2>
 Construção de uma fonte retificadora capaz de transformar corrente alternada de tensão de 127 volts em uma corrente contínua, tensão ajustável entre 3 e 12 volts com capacidade de 100mA.
<h2>Componentes : </h2>
<h3>Funções</h3>
<ul>
  <li><b>Transformador :</b> O transformador funciona através da diferença no número de enrolamentos em duas bobinas e, baseando-se no fato de que a potência é preservada na entrada e na saída, consegue diminuir a tensão na razão das voltas das bobinas.</li>
  <li><b>Ponte de Diodos :</b> A ponte de diodos tem a função de não deixar a corrente fluir no sentido contrário ao desejado, redirecionando-a quando for necessário.
</li>
  <li><b>Capacitor :</b> O capacitor carrega quando a corrente flui no sentido de carga e quando a tensão não é suficiente para alimentar o resto do circuito, o capacitor descarrega, fornecendo a corrente para a carga. A ponte de diodos impede que o capacitor descarregue de volta na fonte de alimentação.
</li>
 <li><b>Resistor do Zener :</b> Utiliza-se um resistor em série com o diodo zener para limitar a corrente que passa por este e evitar que queime.</li>
  <li><b>Diodo Zener :</b> É um tipo especial de diodo que, quando deixa passar a corrente, limita o circuito a uma tensão específica. No caso do nosso projeto utilizamos um zener que limita em 13 V, um pouco abaixo do mínimo fornecido pelo capacitor. Isso possibilita entregar uma corrente contínua com oscilações muito baixas.
</li>
  <li><b>Potenciômetro :</b> é um componente eletrônico que possui resistência elétrica ajustável. Geralmente, é um resistor de três terminais onde a conexão central é deslizante e manipulável. Se todos os três terminais são usados, ele atua como um divisor de tensão.</li>
  <li><b>Transistor :</b> O transistor precisa de uma diferença de potencial mínima para ligar, então quando a tensão na carga se eleva ao ponto da diferença de potencial ficar menor que a diferença mínima exigida pelo transistor, ele desliga. Dessa forma, garante-se que a tensão não passará de um valor determinado que, no caso do nosso projeto, é um pouco acima de 12 V.</li>
 <li><b>Carga :</b> Por fim, temos a carga que vai receber os 100 mA a 12V. Para os testes dessa fonte, utilizamos uma resistência de 120 Ohms. A carga está ligada em paralelo com o resistor do zener e tem a sua tensão limitada pelo diodo e pelo transistor e regulada de 3 a 12 V por um potenciômetro.</li>
</ul>  

<h3>Preços</h3>
<table style="width:100%">
  <tr>
    <th>Componente</th>
    <th>Quantidade</th>
    <th>Preço</th>
  </tr>
  <tr>
    <td>Transformador 18V</td>
    <td style="text-align: center">1</td>
    <td><a href= https://produto.mercadolivre.com.br/MLB-1221271612-transformador-trafo-1818v-500ma-bivolt-eletronica-eletrica-_JM>R$ 34,99</a></td>
  </tr>
  <tr>
    <td>Diodo 1N4004</td>
    <td>4</td>
    <td><a href= https://www.baudaeletronica.com.br/diodo-1n4004.html?gclid=EAIaIQobChMIkYnW7vH-8QIVjYCRCh3U7Q48EAQYAiABEgL5-vD_BwE>R$ 0,13 x 4 = R$ 0,52</a></td>
  </tr>
    <tr>
    <td>Capacitor 560µF</td>
    <td>1</td>
    <td><a href= https://produto.mercadolivre.com.br/MLB-1475225607-20x-capacitor-eletrolitico-560uf25v-105-10x16mm-capxon-_JM>R$ 1,65</a></td>
  </tr>
    <tr>
    <td>Diodo Zener 1N4743</td>
    <td>1</td>
    <td><a href= https://www.baudaeletronica.com.br/diodo-zener-1n4743-13v-1w.html?gclid=EAIaIQobChMIpqbytPT-8QIVSwmRCh3EQQS9EAQYAyABEgIXp_D_BwE>R$ 0,21</a></td>
  </tr>
    <tr>
    <td>Potenciômetro 2000Ω</td>
    <td>1</td>
    <td><a href= https://www.baudaeletronica.com.br/potenciometro-linear-de-2k-2000.html?gclid=EAIaIQobChMIr-jl7fT-8QIVVQiRCh1NgQfmEAQYAiABEgIYpvD_BwE>R$ 2,04</a></td>
  </tr>
    <tr>
    <td>Resistor 240Ω</td>
    <td>3</td>
    <td><a href= https://www.baudaeletronica.com.br/resistor-240r-5-1-4w.html?gclid=EAIaIQobChMIp5nCpff-8QIVUwiRCh3iTgPXEAQYASABEgLgEvD_BwE>R$ 0,06 x 3 = R$ 0,18</a></td>
  </tr>
      <tr>
    <td>Resistor 100Ω</td>
    <td>2</td>
    <td><a href= https://www.baudaeletronica.com.br/resistor-100r-5-1-4w.html?gclid=EAIaIQobChMI7dTq2YT_8QIVHx-tBh0sMwn5EAQYAiABEgKN0PD_BwE>R$ 0,08 x 2 = R$ 0,16</a></td>
  </tr>
      <tr>
    <td>Transistor</td>
    <td>1</td>
    <td><a href= https://www.baudaeletronica.com.br/transistor-npn-2n3904.html?gclid=EAIaIQobChMI6ca8pvr-8QIVYw2tBh1npw87EAQYASABEgLTV_D_BwE>R$ 0,40</a></td>
  </tr>
        <tr>
    <td ><b>Total</b></td>
    <td></td>
    <td><b>R$ 40,15</b></td>
  </tr>
</table>
<h2>Cálculos do Projeto</h2>
<ul>
 <li><b>Transformador :</b> A tensão na entrada do transformador é a seguinte:
  <img src = https://files.catbox.moe/eya2db.png></img>

A razão do transformador escolhida para esse projeto foi de 0,1:

Pico na saída: 179,6 * 0,1 = 17,96 V;

Pico obtido no Falstad: 17, 38 V;

Escolhemos um valor de tensão comercial que entrega 18 V na saída.
</li>
  <li><b>Ponte de Diodos : </b>Modelo dos diodos: 1N4004
 
Há sempre dois diodos ligados e cada diodo consome 0,7V, logo, há uma queda de tensão de 2 * 0,7 = 1,4 V.
 
Tensão depois da ponte de diodos = 18 - 1,4 = 16,6 V.
 
Tensão depois da ponte de diodos obtida no Falstad: 16,475.
 
</li>
  <li><b>Capacitor : </b>Cálculo da capacitância considerando um ripple de 10%:
<img src = https://files.catbox.moe/zp9wyj.png></img>

OBS: Utilizando o capacitor de 560, a simulação apresentou uma tensão de pico depois do capacitor de 16,397 V e tensão mínima de 15,62 V, o que representa um ripple de aproximadamente 5%.

</li>
  <li><b>Resistor do Zener : </b>Calculamos esse resistor da seguinte maneira:
<img src = https://files.catbox.moe/c37h4k.png></img></li>
  <li><b>Carga : </b>Considerando que o diodo zener corta em 13 V e que o transistor precisa de 0,7 V para funcionar, a tensão que chega na carga é de 13 - 0,7 V = 12,3 V. Portanto, a corrente será:

<img src = https://files.catbox.moe/woutte.png></img></li>
 </ul>
<h2>Circuito no Falstad</h2>
<h3>Imagem</h3>
<img src = https://files.catbox.moe/m1duee.png></img>
<h3>Link</h3>
  <li><a href = https://tinyurl.com/yz3e4p9p>Link do Falstad</a></li>
  <li><a href= https://files.catbox.moe/bmcvo9.txt>Arquivo do Projeto</a></li>
<h2>PCB no EAGLE</h2>
<img src = https://files.catbox.moe/p8rpio.png></img>
<img src = https://files.catbox.moe/dpqbjg.png></img>
<h2>Vídeo da apresentação</h2>
<li><a href = colocar link>Link do Vídeo</a></li>
