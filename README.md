# Arduino-piscadinha
Este repositório documenta a realização da tarefa de autoestudo em Arduino, conforme as instruções fornecidas. O objetivo principal é demonstrar o controle de um LED externo (off-board) em um circuito simulado no Tinkercad, criando um efeito de "pisca-pisca" com cadência personalizada.

## Etapas Realizadas

1. Instalação da Arduino IDE;
2. Blink com LED Interno: Realizado o teste inicial com o LED interno do Arduino Uno, configurando o pino 13 como saída e enviando comandos HIGH/LOW com delays. Evidências (fotos/capturas de tela) foram postadas no GitHub (ver seção de Evidências abaixo);
3. Simulação no Tinkercad:  Montagem do circuito;

## Montagem do Circuito 
#### Componentes:

- Arduino Uno.
- Protoboard.
- LED (off-board, cor qualquer).
- Resistor de 220Ω (para limitar corrente e proteger o LED).
- Fios jumper para conexões.


#### Conexões:

- Pino 13 do Arduino → Ânodo do LED (via resistor 220Ω).
- Cátodo do LED → GND do Arduino.
- Alimentação: Porta USB do Arduino.

OBS: No Tinkercad, arraste os componentes para o workspace, conecte os fios e cole o código no editor de blocos/código.

## Evidências
#### Capturas de Tela:

- **Circuito montado:** ![foto_led_piscando1](https://github.com/user-attachments/assets/29a52445-7009-401a-b53c-8638886af752)
- **Vídeo de Demonstração:** https://youtu.be/vkqzBNprj80?si=9eMyGPg9JfVdR2Ci
- **Led que pisca no Thinkercad:** <img width="1280" height="488" alt="arduino_blink_project" src="https://github.com/user-attachments/assets/baf96ec2-c4d9-45a4-9ef2-a58d35c0731b" />


  ### Referências

1. Documentação Arduino: https://docs.arduino.cc/language-reference/pt/
2. Tutoriais Tinkercad: https://www.youtube.com/watch?v=OqaxjUXTAGw
4. Vídeos Assistidos: https://www.youtube.com/watch?v=t0tCMcDhbZE 
