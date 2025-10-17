# arduino-ponderada
Este repositório documenta a realização da tarefa de autoestudo em Arduino, conforme as instruções fornecidas. O objetivo principal é demonstrar o controle de um LED externo (off-board) em um circuito simulado no Tinkercad, criando um efeito de "pisca-pisca" com cadência personalizada.

## Etapas Realizadas

1. Instalação da Arduino IDE;
2. Blink com LED Interno: Realizado o teste inicial com o LED interno do Arduino Uno, configurando o pino 13 como saída e enviando comandos HIGH/LOW com delays. Evidências (fotos/capturas de tela) foram postadas no GitHub (ver seção de Evidências abaixo);
3. Simulação no Tinkercad:  Montagem do circuito;

Link do projeto no Tinkercad:

## Montagem do Circuito 
#### Componentes:

- Arduino Uno.
- Protoboard.
- LED (off-board, cor qualquer).
- Resistor de 220Ω (para limitar corrente e proteger o LED).
- Fios jumper para conexões.


#### Conexões:

- Pino 6 do Arduino → Ânodo do LED (via resistor).
- Cátodo do LED → GND do Arduino.
- Alimentação: Use a porta USB do Arduino para simulação no Tinkercad.

OBS: No Tinkercad, arraste os componentes para o workspace, conecte os fios e cole o código no editor de blocos/código.
