# descrição do que foi feito em cada atividade

## Explicação:

A)o microcontrolador envia um sinal de 3,3 ou 5 volts e aciona-se uma saída optoacoplada à triac em 127Vca / 1A ou @230Vca / 1A.
- O led emissor recebe sinal a partir dos 5V de entrada;
- O transistor receptor chaveia, enviando o sinal de 127 para o amplificador operacional, acionando o triac;
- Quando o triac recebe o pulso no gate ele inicia a condução do anodo 1 para o anodo 2.

B)o microcontrolador envia um sinal de 3,3 ou 5 volts e aciona-se uma saída à relé (optoacoplada) com contato NA, 100 a 240Vca/ 5A resistivo.
- Led emissor recebe o sinal de 5V , permitindo o chaveamento do transistor emissor;
- Quando o transistor receptor chaveia ele aciona outro transistor que energiza a bobina;
- Quando passa corrente pela bobina ela cria um campo magnético que fecha o contato e permite a passagem dos 220V.

C)o microcontrolador envia um sinal de 3,3 ou 5 volts e aciona-se uma saída transistorizada em 24Vcc/500mA carga resistiva;
- Led emissor recebe o sinal de 5V , permitindo o chaveamento do transistor emissor;
- Quando o transistor receptor chaveia ele aciona outro transistor que permite a passagem dos 24V.

D)vem um sinal do campo de 24Vcc e gera uma saída de 3,3 ou 5 volts optoacoplada para o microntrolador;

E) vem um sinal do campo de 127 / 230 Vca (sem uso de transformador - fonte sem trafo) e gera uma saída de 3,3 ou 5 volts optoacoplada para o microntrolador.


