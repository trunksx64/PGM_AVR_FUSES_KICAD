# Restore AVR FUSES SMD ::: Revisión R1 :: Versión 1.10

![](https://github.com/trunksx64/PGM_AVR_FUSES_KICAD/blob/main/Images/pcb_front.png)
![](https://github.com/trunksx64/PGM_AVR_FUSES_KICAD/blob/main/Images/front.png)

## Razón de Ser e Inspiración

Este escudo para Arduino UNO se diseñó teniendo en mente inicialmente una forma para restaurar los FUSES del Atmega328P que por error u olvido se programaban mal en esta placa.
Haciendo inutilizables estos microcontroladores con programadores seriales como el AMTEL-ICE o MPLAB-SNAP, al inicio se diseñó como un simple restaurador, pero se vio la idea de dotarlo de más características como hacerlo un programador HIGH VOLTAJE, 
por lo cual se incluyo la etapa de elevación de tensión para obtener 12~14VDC, esta hizo que los pines disponibles del Arduino no fueran suficientes, se incluyo un expansor MCP23S08, para la comunicación de los Datos de 8Bits y el resto para el control de la programación en paralelo.
La idea a futuro es diseñar y crear una GUI multiplataforma para programas el Atmega328P y microcontroladores compatibles hacia abajo en número de pines.

## Características del Hardware

 * Socket ZIF de 28 Pines similar a la Marca 3M.
 * Expandor de puerto SPI MCP23S08.
 * Botones para Reset de la Placa UNO y Accion de programación.
 * Dos LEDS de estado de Programación.
 * Control de Alimentacion VCC y Elevador de Tensión para VPP.
 * Resistencias de protección, para evitar daño si el Microcontrolador es puesto al revez.
 * Diseño de Escudo (Shield) compatible con Arduino UNO R3.

## Características Específicas

Se tomó el Expansor MCP23S08, usando el protocolo SPI para garantizar la máxima velocidad de Datos para la Programación. 
El levador de tensión usa un juego de Diodo y Bobina simple, de fácil adquisición en el mercado con amplio valores sin problema alguno, todo esto implementado el control por PWM y ADC para controlar la estabilidad de la tensión de VPP para el microcontrolador.

## Versiones

* 2023 : 1.0.0 : Primera Versión.
* 2023 : 1.1.0 : Diseño de Liberias para Modelo 3D del Socket ZIF.

## ERRATAS

* Ninguna en el Momento.

## Créditos

xDNA Electronics & Desing es una microempresa Personal, que se dedica y encarga de elaborar proyectos de Control y Automatización por pedido, su idea es colaborar y ayudar a quines a si lo requieran, el proyecto se hizo principalmente como Hobby el cual gracias a terceros se pudo implementar y hacer su creación, por lo cual se da la libertad de usarlo para experimentar sin hacer uso comercial del mismo.

## Licencia

![](https://github.com/trunksx64/GAME_CAT_R3_KICAD/blob/main/Images/creative_commons.png)

Licensed under Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)
