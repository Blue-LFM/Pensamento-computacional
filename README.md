Você foi contratado pela prefeitura da cidade para ajudar a melhorar a segurança em uma rua próxima a uma escola. Nessa rua existe uma faixa de pedestres, mas muitas vezes os carros passam ao mesmo tempo em que as pessoas tentam atravessar, o que pode causar situações perigosas.
Para resolver esse problema, a prefeitura decidiu instalar um sistema de sinalização simples utilizando luzes. O sinal dos carros possui três luzes: verde, amarelo e vermelho. 
O sinal dos pedestres possui duas luzes: vermelho e verde.
A prefeitura pediu que você desenvolva uma simulação desse sistema utilizando Arduino no Tinkercad, controlando as luzes por meio de LEDs.

Análise:
O sinal dos carros possui 3 luzes: verde, amarelo e vermelho; ou seja, 3 LEDs.
O sinal dos pedestres possui duas luzes: vermelho e verde; ou seja, 2 LEDs.
Logo, serão necessários 5 LEDs.

Encontrar uma solução: 
As luzes devem acender e apagar em intervalos, sendo que as luzes de mesma cor não devem acender ao mesmo tempo. 
Deve haver um intervalo entre o sinal vermelho dos carros e o sinal verde dos pedestres, e entre o sinal vermelho dos pedestres e o sinal verde dos carros.

Implemementar uma solução:
Entre o acender da luz vermelha dos pedestres e o acender da luz verde dos carros, há um intervalo de 10 segundos, evitando possiveis acidentes.
Entre a luz verde e a luz amarela dos carros, há um intervalo de 30 segundos.
Entre a luz amarela e vermelha dos carros, há um intervalo de 15 segundos.
Entre a luz vermelha dos carros e a luz verde dos pedestres, há um intervalo de 10 segundos.
Há um intervalo de 45 segundos entre a luz verde e a luz vermelha dos pedestres.

Avaliação da solução: Em situações da vida real, essa solução seria eficiente para um bom andamento do trânsito.
