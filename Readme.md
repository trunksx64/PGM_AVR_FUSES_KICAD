# XTW2 Clone ::: Revisión R1 :: Versión 1.20

![](https://github.com/trunksx64/XTW_2_CLONE_KICAD/blob/main/Images/pcb_front.png)
![](https://github.com/trunksx64/XTW_2_CLONE_KICAD/blob/main/Images/front.png)

## Razón de Ser e Inspiración

Este pequeño stick se diseñó como una prueba de aprendizaje para el uso de los microcontroladores STM32 y además por error al tratar de leer la memoria de un programador XTW2, este quedo inutilizable.
originalmente este programador de memorias salió dañado, presentando muchos errores principalmente en la lectura de Memorias Eeproms, se tomó la iniciativa de crear un software tanto para el STM32 y una GUI para Linux.
Aún están en desarrollo por mi parte, falta de tiempo en realidad, se espera en un futuro terminarlo.

## Características del Hardware

  * Microcontrolador STM32F103C8T6.
  * Base ZIF de 16pines, similar de la Marca 3M.
  * Puerto USB 2.0 Macho tipo A.
  * Pinhead de 5 pines para Programamcion y Debug ST-LINK.
  * Testpoint para Puerto UART Basico.
  * Boton de Reset.

## Características Específicas

Se tomó un tamaño similar al Original, agregando algunos componentes para usarlo en Debug mediante STM32CubeIDE, distribuyendo un poco mejor los componentes y usando tamaños más comerciales como sencillos de soldar.

## Microcontrolador

* Architecture 32-bit.
* STM32F103C8T6:

	* ARM®32-bit Cortex®-M3 CPU Core 
		* 72 MHz maximum frequency,1.25 DMIPS/MHz (Dhrystone 2.1) performance at 0 wait state memory access
		* Single-cycle multiplication and hardware division
	
	* Memories 
		* 64 or 128 Kbytes of Flash memory
	*	 20 Kbytes of SRAM
	
	* Clock, reset and supply management 
		* 2.0 to 3.6 V application supply and I/Os
		* POR, PDR, and programmable voltage detector (PVD)
		* 4-to-16 MHz crystal oscillator
		* Internal 8 MHz factory-trimmed RC
		* Internal 40 kHz RC
		* PLL for CPU clock
		* 32 kHz oscillator for RTC with calibration

	* Low-power 
		* Sleep, Stop and Standby modes
		* VBAT supply for RTC and backup registers
	
	* 2 x 12-bit, 1 μs A/D converters (up to 16 channels) 
		* Conversion range: 0 to 3.6 V
		* Dual-sample and hold capability
		* Temperature sensor
	
	* DMA 
		* 7-channel DMA controller
		* Peripherals supported: timers, ADC, SPIs, I2Cs and USARTs
	
	* Up to 80 fast I/O ports 
		* 26/37/51/80 I/Os, all mappable on 16 external interrupt vectors and almost all 5 V-tolerant
		* Debug mode 
		* Serial wire debug (SWD) & JTAG interfaces
	
	* 7 timers 
		* Three 16-bit timers, each with up to 4 IC/OC/PWM or pulse counter and quadrature (incremental) encoder input
		* 16-bit, motor control PWM timer with dead-time generation and emergency stop
		* 2 watchdog timers (Independent and Window)
		* SysTick timer 24-bit downcounter
	
	* Up to 9 communication interfaces 
		* Up to 2 x I2C interfaces (SMBus/PMBus)
		* Up to 3 USARTs (ISO 7816 interface, LIN, IrDA capability, modem control)
		* Up to 2 SPIs (18 Mbit/s)
		* CAN interface (2.0B Active)
		* USB 2.0 full-speed interface
	
	* CRC calculation unit, 96-bit unique ID 
	* Packages are ECOPACK® 

## Versiones

* 2023 : 1.0.0 : Primera Versión.
* 2023 : 1.0.0 : Diseño de Liberias para Modelo 3D del Socket ZIF.
* 2023 : 1.2.0 : Se Agrego Boton de Reset, Pin SWO para Debug, Dos Testpoint para UART.

## ERRATAS

* Ninguna en el Momento.

## Créditos

xDNA Electronics & Desing es una microempresa Personal, que se dedica y encarga de elaborar proyectos de Control y Automatización por pedido, su idea es colaborar y ayudar a quines a si lo requieran, el proyecto se hizo principalmente como Hobby el cual gracias a terceros se pudo implementar y hacer su creación, por lo cual se da la libertad de usarlo para experimentar sin hacer uso comercial del mismo.

## Licencia

![](https://github.com/trunksx64/GAME_CAT_R3_KICAD/blob/main/Images/creative_commons.png)

Licensed under Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)
