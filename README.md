# Circuito Temporizador e Controlador de Corrente 
Projeto final da disciplina de Laboratório de Microcontroladores e Aplicações do Departamento de Computação da UFSCar.

## Proposta 
O projeto consiste de um circuito temporizador e controlador de corrente implementado utilizando Arduino, que utiliza um medidor de corrente não invasivo, ou seja, um medidor que não "interrompe" o circuito para fazer a medição, e um relé para o controle do circuito permitindo ou não a passagem da corrente a partir de dados fornecidos pelo usuário, como tempo de funcionamento do aparalho e corrente máxima desejada (A) por meio de uma interface usando pushbuttons e um display LCD.

<img src="https://github.com/brunoinfo/teste-de-circuito/blob/master/Imagens/projeto_circuito_v_09_2.jpg" width="500">

### Proposta inicial e mudanças ao longo do projeto

Inicialmente, estava foi proposto um circuito que apenas mede a corrente atual a partir do sensor não-invasivo, e quando uma corrente máxima pré-definida fosse atingida, o aparelho seria desligado. Com o passar do tempo, com o aprendidado e o aprofundamento das bibliotecas do Arduino, pensamos também em incluir uma função de temporizador para o circuito, algo que julgamos ser de relevancia para um circuito do tipo.

### Material
 - Arduino MEGA 2560
 - LCD Keypad Shield
 - Módulo Relé Arduino
 - Medidor de Corrente não-invasivo (SCT013 - 20A/1V)
 - Outros componentes (resistores, capacitor, cabos, conectores, entre outros)

### Grupo
 - Bruno Padua
 - João Guilherme Luchetti 
 - Rafael Uryu
