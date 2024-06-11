# Indicador de Posição de Corrida


## 🗒️ Autores
- Danilo Wendler - RM: 556602
- Pedro Muzel - RM: 555983
- Lucas Raphael - RM: 555543
- Vitor Ismael - RM: 556027
- Renato Luiz - RM: 556403


## 📁 Link para o Projeto no Tinkercad
[Projeto no Tinkercad](https://www.tinkercad.com/things/lIDTg2iTIu1-indicador-posicao-de-corrida)

## 🗒️ Descrição do Projeto
Este projeto, visando aumentar a visibilidade da formula E no Brasil, utiliza um Arduino Uno para criar um sistema de indicação de posição de corrida e contador de voltas automático. O sistema exibe a posição atual do piloto  no display LCD e utiliza dois botões para incrementar e decrementar a posição. Além disso, um buzzer é utilizado para alertar quando a posição é alterada.

## 🗒️ Objetivo
O objetivo deste projeto é fornecer uma maneira prática e intuitiva de monitorar a posição dos competidores de formula E em uma corrida e contar automaticamente as voltas completadas, deixando o produto final, o site fantasy que faremos, mais intuitivo com o publico.

## 🗒️ Componentes Necessários
- Arduino Uno
- Display LCD 16x2
- Dois botões push-button
- Buzzer
- Potenciômetro 10kΩ (para ajuste do contraste do LCD)
- Resistor 220Ω (para o buzzer)
- Resistores 330 Ω (para os botões)
- Breadboard
- Fios de conexão

## 🛠️ Montagem do Circuito
### 🛠️ Conexões do Display LCD 16x2
- Conectamos o pino GND do LCD ao GND do Arduino.
- Conectamos o pino VCC do LCD ao 5V do Arduino.
- Conectamos o pino VO ao cursor central do potenciômetro de 10kΩ (os outros dois terminais do potenciômetro ao 5V e GND).
- Conectamos o pino RS ao pino digital 12 do Arduino.
- Conectamos o pino RW ao GND do Arduino.
- Conectamos o pino E ao pino digital 11 do Arduino.
- Conectamos os pinos D4, D5, D6, D7 aos pinos digitais 5, 4, 3, 2 do Arduino, respectivamente.
- Conectamos o pino LED+ ao 5V do Arduino através de um resistor de 220Ω.
- Conectamos o pino LED- ao GND do Arduino.

### 🛠️ Conexões dos Botões
Conectamos um lado do primeiro botão ao pino digital 6 do Arduino.
Conectamos o outro lado do primeiro botão ao GND através de um resistor de 10kΩ.
Conectamos um lado do segundo botão ao pino digital 7 do Arduino.
Conectamos o outro lado do segundo botão ao GND através de um resistor de 10kΩ.

### 🛠️ Conexões do Buzzer
Ligamos o terminal positivo do buzzer ao pino digital 8 do Arduino.
Ligamos o terminal negativo do buzzer ao GND do Arduino.

## 🛠️ Código Arduino
O código estará presente no vídeo apresentado e no link do projeto com o tinkercad.

## 🛠️ Instruções de Uso
Montagem do Circuito:
1. Monte o circuito conforme descrito na seção "Montagem do Circuito".
2. Certifique-se de que todas as conexões estejam firmes e corretas.

### 🛠️ Carregar o Código no Arduino:
1.Conecte o Arduino ao computador através do cabo USB.
2.Abra o Arduino IDE.
3.Copie e cole o código fornecido na seção "Código Arduino" no editor do Arduino IDE.
4.Selecione a porta correta e o modelo do Arduino (Arduino Uno).
5.Carregue o código no Arduino.

### 🗒️ Executar o Projeto:
1.Após carregar o código, o LCD deverá inicializar e exibir "Posicao Piloto:" seguido de sua posição atual.
2.Pressione os botões para incrementar ou decrementar a posição. O buzzer soará ao mudar a posição.

### 🗒️ Ajuste de Parâmetros:
Utilize o potenciômetro de 10kΩ para ajustar o contraste do LCD para melhor visualização.

## 🗒️ Requisitos
### Hardware:
Arduino Uno
Componentes listados na seção "Componentes Necessários"

## 🗒️ Dependências
- Utlizamos a Biblioteca LiquidCrystal, passada em aula para o LCD
  
## Considerações Finais
Este projeto consiste nada mais do que um indicador de posição de corrida com contador de voltas automático. Ele pode ser expandido para incluir mais funcionalidades, como conectividade com a IoT para monitoramento remoto e alertas em tempo real, como no aplicativo de cartola de futebol, proporcionando uma maior flexibilidade e usabilidade para diversas aplicações nas corridas da formula E.






