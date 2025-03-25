Se o S1 está ligado, significa que a água está acima do nível ideal, logo a válvula 1 é acionada para a vazão da água.

Se S1 e S2 estiverem ligados, significa que a água está muito acima do nível ideal, logo as válvulas 1 e 2 são acionadas para uma vazão maior da água.

Se nenhum dos sensores estiver ligado, significa que a água está abaixo do nível ideal, logo V3 é acionada para encher o reservatório.

Se um dos sensores superiores (S1 e S2) estiver ligado enquanto algum de seus sensores inferiores estiver desligado, significa que algum sensor está quebrado, logo o alarme é acionado. Quando o alarme é acionado, as válvulas V1 e V2 se ligam para esvaziar o reservatório, enquanto a V3, naturalmente, permanece fechada.

Entradas: S0, S1, S2
Saída: V1, V2, V3, ALARME

S0: SW0 - PIN_U13
S1: SW1 - PIN_V13
S2: SW2 - PIN_T13
V1: LEDR0 - PIN_AA2
V2: LEDR1 - PIN_AA1
V3: LEDR2 - PIN_W2
ALARME: LEDR3 - PIN_Y3

Placa: DE0-CV (5CEBA4F23C7)

