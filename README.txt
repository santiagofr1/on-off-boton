output pin3
if{v pin6 > 2/3 vcc} --> 0
if{v pin2 < 1/3 vcc} --> 1

t0 el circuito inicia con un 0
R1 y R2 son un divisor de voltaje, cae 6v en pin2 y pin6

t1 se presiona el boton
se comienza a cargar C1, cae el voltaje de pin2 --> output 1

t2 
C1 se sigue cargando mediante R3 con el voltaje de pin3

t3 se presiona el boton
C1 tiene 12v y en el divisor hay 6v, se eleva el voltaje en pin6 --> output 0

t5 = t0