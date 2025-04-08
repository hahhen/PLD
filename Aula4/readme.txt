Tabela verdade
------------------------------------------------------
                                        
   8 | 4 | 2 | 1 |        y0| y1| y2| y3| y4| y5| y6|
   ---------------        ---------------------------
   0 | 0 | 0 | 0 |        1 | 1 | 1 | 1 | 1 | 1 | 0 |
   0 | 0 | 0 | 1 |        0 | 1 | 1 | 0 | 0 | 0 | 0 |
   0 | 0 | 1 | 0 |        1 | 1 | 0 | 1 | 1 | 0 | 1 |
   0 | 0 | 1 | 1 |        1 | 1 | 1 | 1 | 0 | 0 | 1 |
   0 | 1 | 0 | 0 |        0 | 1 | 1 | 0 | 0 | 1 | 1 |
   0 | 1 | 0 | 1 |        1 | 0 | 1 | 1 | 0 | 1 | 1 |
   0 | 1 | 1 | 0 |        1 | 0 | 1 | 1 | 1 | 1 | 1 |
   0 | 1 | 1 | 1 |        1 | 1 | 1 | 0 | 0 | 0 | 0 |
   1 | 0 | 0 | 0 |        1 | 1 | 1 | 1 | 1 | 1 | 1 |
   1 | 0 | 0 | 1 |        1 | 1 | 1 | 0 | 0 | 1 | 1 |
   1 | 0 | 1 | 0 |        1 | 1 | 1 | 0 | 0 | 1 | 1 |
   1 | 0 | 1 | 1 |        0 | 0 | 1 | 1 | 1 | 1 | 1 |
   1 | 1 | 0 | 0 |        1 | 0 | 0 | 1 | 1 | 1 | 0 |
   1 | 1 | 0 | 1 |        0 | 1 | 1 | 1 | 1 | 0 | 1 |
   1 | 1 | 1 | 0 |        1 | 0 | 0 | 1 | 1 | 1 | 1 |
   1 | 1 | 1 | 1 |        1 | 0 | 0 | 0 | 0 | 1 | 1 |

------------------------------------------------------

Cada entrada possui dois fios: um direto e um com uma porta NOT.
Existem 16 portas AND4 que representam cada número possível do display.
Os segmentos do display, que acendem com o bit 0, possuem portas OR que recebem as saídas dos ANDs que não necessitam do segmento.

Entradas: 1, 2, 4, 8
Saída: y0, y1, y2, y3, y4, y5, y6,

1: SW0 - PIN_U13
2: SW1 - PIN_V13
4: SW2 - PIN_T13
8: SW3 - PIN_T12
y0: HEX00 - PIN_U21
y1: HEX01 - PIN_V21
y2: HEX02 - PIN_W22 
y3: HEX03 - PIN_W21
y4: HEX04 - PIN_Y22
y5: HEX05 - PIN_Y21
y6: HEX06 - PIN_AA22

Placa: DE0-CV (5CEBA4F23C7)