Tabela verdade
--------------------------------------
|                                    |
|   F | E | D |       CF | CE | CD   |
|   0 | 0 | 0 |        1 |  0 |  0   |
|   0 | 0 | 1 |        1 |  1 |  0   |
|   0 | 1 | 0 |        1 |  0 |  1   |
|   0 | 1 | 1 |        1 |  0 |  0   |
|   1 | 0 | 0 |        0 |  0 |  1   |
|   1 | 0 | 1 |        0 |  1 |  0   |
|   1 | 1 | 0 |        0 |  0 |  1   |
|   1 | 1 | 1 |        0 |  0 |  1   |
|                                    |
--------------------------------------

Se o sensor F não estiver acionado, o robô irá para frente, sempre.
Se o sensor E estiver acionado enquanto o sensor D não estiver, o robô irá virar para a direita.
Se o sensor D estiver acionado enquanto o sensor E não estiver, o robô irá virar para a esquerda.
Se os sensores F e E estiverem acionados, o robô irá virar para a direita.
Se os sensores F e D estiverem acionados, o robô irá virar para a esquerda.
Se os três sensores estiverem acionados, o robô irá virar para a direita.


Entradas: F, E, D
Saída: CF, CE, CD

F: SW0 - PIN_U13
E: SW1 - PIN_V13
D: SW2 - PIN_T13
CF: LEDR0 - PIN_AA2
CE: LEDR1 - PIN_AA1
CD: LEDR2 - PIN_W2

Placa: DE0-CV (5CEBA4F23C7)

