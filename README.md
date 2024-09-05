#incluir <ultrassônico.h>
#incluir <servo.h>
#incluir "notas_musicais.h"

#definir pinoServo 7
#definir trigonometria 2
#definir Eco 3
#definir B1a 8
#definir B1B 9
#definir A1A 10
#definir A1B 11

inteirodistanciaD;
inteirodistanciaE;
inteiroṕino de campanha =6;

flutuadordistanciaObstáculo =35;

Ultrassônicoultrassônico(Trig, Eco);

Servo servo;

vazio configurar() {
Serial.começar(9600);

