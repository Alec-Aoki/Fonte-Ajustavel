# SSC0180-Eletronica
# Fonte de Tensão Ajustável
## Definição
Montar uma fonte de tensão ajustável de 3V a 12V, com capacidade (corrente) de 100mA.
Ela receberá 127V, com uma corrente alternada de 60Hz.
## Componentes
| Quantidade      | Componente              | Valor   |
| --------------- | ----------------------- | ------- |
| 1x              | Ponte Reitificadora 2A  | R$3,78  |
| 1x              | Capacacitor 470UFX50V   | R$4,27  |
| 5x              | Resistor 2K2            | R$0,07  |
| 5x              | Resistor 4K3            | R$0,07  |
| 1x              | Resistor 1W 120         | R$0,39  |
| 1x              | Diodo Zener 13V 1W      | R$0,49  |
| 1x              | LED Vermelho            | R$1,26  |
| 1x              | Transistor BC368 25V 1A | R$0,43  |
| 1x              | Potenciômetro 1W 5K     | R$6,74  |
| 1x              | Transformador 9V+9V     | R$00,00 |
| 1x              | Protoboard              | R$21,05 |
| TOTAL           |                         | R$52,11 |

- TRANSFORMADOR

   Transforma a tensão de 127V em 25.1 (foram conectados as pontas +9V e -9V do transformador, gerando uma tensão média de 18V e de pico de 25.1) por meio de indução eletromagnética.

- PONTE DE DIODO

   Transforma a corrente de ALTERNADA (f = 60Hz) para CONTÍNUA (f = 120Hz) por meio de 4 diodos.
   Um diodo permite a passagem de corrente em somente uma direção.

- CAPACITOR

   Armazena a carga proveniente da tomada, descarregando-a quando a corrente alterna. Cria o efeito ripple.

- DIODO ZENER

   Funcionamento similar ao diodo comum, mas permite a passagem de corrente até um certo ponto. Nesse caso, essa corrente corresponde a uma tensão de 13V.
   Em outras palavras: se uma tensão maior que 13V chegar no Zener, ele a limitará a 13V.

- TRANSISTOR

    Permite que a tensão no celular seja ajustada pelo potenciômetro.

- PONTECIÔMETRO

    Podemos pensá-lo como uma resistência ajustável. Variando-a, variamos também a tensão que passa pelo celular. Ele pode variá-la de 12V a 0V. O resistor logo em seguida dele limita essa variação de 12V para 3V.

- LED

    Tem seu brilho aumentado conforme a corrente que passa pelo celular.


## Circuito
#### Faltsad: https://tinyurl.com/26b3eawc
![alt text](./circuito_falstad.png "Circuito no Faltsad")
#### Eagle

## Vídeo
https://youtu.be/ODlF76heZ84

## Alunos
- Alec Campos Aoki - 15436800
- Pedro Augusto Ferraro Paffaro - 
- João Pedro Castelli - 
- Marcelo Conti - 