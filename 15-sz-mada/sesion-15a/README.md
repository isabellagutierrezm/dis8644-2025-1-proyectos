# sesion-15a

[17 de junio del 2025]

Llevamos las protoboards a que fueran documentadas en fotos

Actualizamos la proto en sí, sacando el LED que estaba en el circuito original del detector de sombra, aumentando la velocidad de la secuencia de LEDs, y desordenando cómo se verían

Comenzamos a trabajar en la PCB; decidimos separarla en 3, una con el circuito principal, otra con los LEDs de la secuencia y el LDR, y una tercera con el circuito del micrófono engañoso

## BOM proyecto-02

|QTY|REFERENCE|VALUE|FOOTPRINT|OBS
|:-:|-|-|-|-
|3|U1,U4,U5|~|Socket 8-pin|-
|1|U2|~|Socket 14-pin|-
|1|U3|~|Socket 18-pin|-
|4|R2,R3,R4,R5,R8,R10,R11|10k|Resistencia|-
|5|R7,R9,R12|1k|Resistencia|-
|1|R6|100k|Resistencia|-
|1|R1|LDR|LDR|-
|3|C1,C4,C7|474n|Condensador cerámico|474
|1|Q1|PN2222A|Transistor|-
|1|MK1|MIC|Micrófono electret|-
|3|C3,C5,C6|1u|Condensador electrolítico|-
|1|C2|100u|Condensador electrolítico|-
|12|D1~D11|LED|LED 5mm|-
|1|RV1|500k|Potenciómetro|-
|3|U1,U4,U5|NE555|DIP-8|Van en los socket U1, U4, y U5
|1|U2|LM324|DIP-14|Va en el socket U2
|1|U3|CD4017|DIP-16|Va en el socket U3
