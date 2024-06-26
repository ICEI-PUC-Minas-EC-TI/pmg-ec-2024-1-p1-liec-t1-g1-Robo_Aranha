
# Materiais

Os materiais utilizados no projeto foram:
- Shield de expansão do arduino nano
- Arduino nano
- 8 servomotores
- Bluetoth HC-05
- Jumper
- 1 led
- 1 resistor de 400 Ohms
  
# Desenvolvimento

Começamos com o hardware. Utilizamos o Arduino Nano como nossa plataforma de controle. Ele é compacto e possui recursos suficientes para o nosso projeto.
Nessa etapa, conectamos os motores, sensores e outros componentes à placa. Calibrar os movimentos da máquina foi um desafio, mas com testes e ajustes, conseguimos obter resultados satisfatórios.<br/>
A próxima etapa envolveu a criação do software embarcado para o Arduino Nano. Escrevemos o código em C/C++ para controlar os motores, interpretar os dados dos sensores e garantir a comunicação adequada.
Focamos na eficiência e na otimização do código para garantir que a máquina respondesse rapidamente aos comandos.<br/>
Para permitir o controle remoto, desenvolvemos um aplicativo simples no MIT App Inventor. Ele tinha botões para acionar os movimentos da máquina (avançar, recuar, girar etc.).
A interface do aplicativo foi projetada de forma intuitiva para facilitar o uso por qualquer pessoa, mesmo sem conhecimento técnico.<br/>
A etapa final foi integrar o código do Arduino Nano com o aplicativo. Usamos comunicação Bluetooth para estabelecer a conexão.
Quando o usuário pressionava um botão no aplicativo, ele enviava um comando via Bluetooth para o Arduino Nano, que interpretava e executava a ação correspondente na máquina.

## Desenvolvimento do Aplicativo

### Interface

Descreva o desenvolvimento das telas do aplicativo.

### Código
Inicialmente, o código foi desenvolvido para testar os motores, incluindo a calibração e a identificação. Posteriormente, adaptou-se o código para controlar o movimento da máquina e, por fim, para integrá-lo aos comandos via Bluetooth e ao aplicativo. 

## Desenvolvimento do Hardware
O hardware foi montado utilizando o Arduino Nano e um shield, resultando em uma construção mais organizada. Além disso, optamos por não utilizar protoboard para simplificar a montagem e deixar o robô mais leve

### Montagem

A montagem foi bastante trabalhosa, pois utilizamos um projeto desenvolvido por alunos do semestre passado. Além disso, enfrentamos um desafio com a placa de Bluetooth, que estava posicionada na parte inferior do robô, o que poderia causar complicações futuras, como dificultar a movimentação e danificar o módulo. Além disso, o Arduino original não estava compilando, então foi substituído por um Arduino Nano, o que tornou os cabos mais organizados. A aranha foi então direcionada para a calibragem, que não foi bem-sucedida, e durante a remontagem, peças importantes foram danificadas, o que fragilizou a estrutura do projeto.

### Desenvolvimento do Código

O desenvolvimento foi, sem dúvida, bastante desafiador, especialmente devido à dificuldade em calibrar os movimentos da aranha. 

## Comunicação entre App e Hardware

Descreva como foi o processo de comunicação entre App e arduino/ESP.
