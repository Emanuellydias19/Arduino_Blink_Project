### Introdução 

Um circuito eletrônico é tipo a "estrada" onde a energia elétrica corre pra fazer as coisas acontecerem. As trilhas de uma placa de circuito impresso (PCI) são os caminhos que guiam essa energia. Quem transforma essa energia elétrica em movimento é o motor, porem nosso foco esta no LED, que transforma energia em luz!

_____________________________________

### Componentes Essenciais
- Todo circuito precisa de três coisas básicas:

1. **Fonte:** Fornece a energia (tipo a bateria ou a tomada).
2. **Condutores:** Os fios ou trilhas que levam a energia pra lá e pra cá.
3. **Carga:** O que usa a energia, como o LED ou um motor.

_____________________________________

### Tipos de Fonte

- **Fonte Transformadora:** Pegue uma tomada (corrente alternada, AC) e transforma em corrente contínua (DC) pra alimentar os circuitos. Super útil pra projetos caseiros! <br>


- **Fonte de Corrente Alternada:** Direto da tomada, mas a gente não usa tanto assim no Arduino, prefere-se a DC.

--------------------------------------

## Componentes que usamos 

#### Resistor
Esse é o **"freio"** da **corrente elétrica**, sabe? Ele controla quantos elétrons passam. Esquenta um pouco e reduz a corrente, mas não mexe na tensão (os volts). O legal é que dá na mesma colocar ele no terminal positivo ou negativo — a ordem não importa, desde que esteja na série com o LED pra proteger ele.

**Faixas Coloridas:** As listrinhas no resistor (tipo laranja-vermelha-preta = 220Ω) mostram quanto ele aguenta. 

Existe um aplicativo que te ajuda a identificar com praticidade, nome : Resistor. 
<br>

#### LED (Light Emitting Diode) 

O LED é o cara que brilha no nosso projeto piscadinha. Ele é um diodo emissor de luz, ou seja, acende quando a corrente elétrica passa por ele. A perna mais comprida é o positivo (ânodo), e a mais curta é o negativo (cátodo). Se você ligar ele direto numa bateria de 9V sem um resistor pra controlar a corrente, ele frita na hora — então, cuidado pra não queimar nosso astro! 

**OBS:** O resistor (como o de 220Ω que usamos) é tipo um "guarda-costas" que protege ele.
<br>

##### O Que é um Diodo?

Agora,  um diodo é tipo uma **"porteira" ou "válvula"** da eletrônica. Ele é um componente feito de material semicondutor (geralmente silício) que deixa a corrente elétrica passar só em um sentido.

 Imagina uma rua de mão única: a corrente vai do ânodo (o lado positivo) pro cátodo (o lado negativo), mas não o contrário. Se tentar forçar a corrente no sentido errado, ele **bloqueia**. 

 <br>

 #### Jumper

Esses fiozinhos tipo 22 AWG ou 3mm são os heróis das conexões. Eles encaixam direitinho na protoboard e fazem a ponte entre o positivo (volts) e o GND (terra, negativo). Sem eles, nada de energia circulando.

<br>


#### Protoboard

A nossa "mesa de trabalho" sem solda! É onde a gente monta o circuito, conectando o LED, o resistor e os jumpers. Super prática pra testar ideias sem bagunça.

<br>

#### Arduino

O cérebro da operação! Com a entrada USB, a gente manda o código (o tal do sketch) pra ele controlar o LED. É o homem que dá vida pro projeto piscadinha acontecer...


_____________________________________________________

## Componentes importantes estudados 

#### Capacitor
Esse cara carrega e descarrega energia super rápido. Tem tipos como eletrolítico (com polaridade, cuidado pra não inverter!), cerâmico e poliéster. Se mexer errado, pode levar um choque, então fica esperto!
<br>
#### Relé
Um interruptor eletromecânico high-tech. Tem uma bobina que, quando energizada, vira um eletroímã e puxa um contato pra ligar ou desligar algo. Perfeito pra controlar coisas maiores com eletrônica.
<br>

####  Semicondutores

Feitos de silício, ficam no meio-termo entre condutores (deixam corrente passar) e isolantes (bloqueiam). São a base de muitos componentes.

- **Diodo:** Tipo uma "porteira" — deixa a corrente passar só num sentido. O LED é um diodo.

- **Transistor:** Revolucionou a eletrônica, deixando tudo mais leve e prático. Tem coletor, emissor e base — a base controla o fluxo entre os outros dois. É tipo o "cérebro" dos circuitos modernos.

- **Chips** (Circuitos Integrados - CI): Um emaranhado de resistores, diodos e transistors numa caixinha só. As perninhas (terminais) conectam tudo na protoboard, condensando um monte de componentes em um só lugar.

_______________________________________

## Código Básico 


