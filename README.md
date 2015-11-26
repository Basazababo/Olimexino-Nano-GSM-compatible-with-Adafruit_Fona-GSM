# Olimexino-Nano-GSM-module is compatible-with-Adafruit_Fona-GSM Arduino Library

Olimexino Nano GSM module use SIM800H while AdaFruit Fona GSM module uses SIM800L, both uses SIM800 series. So, you should use Adafruit_fona Library to communicate with Olimexino Nano GSM
========================================================================================================
Olimexino Nano GSM module use SIM800H while AdaFruit Fona GSM module uses SIM800L, both uses SIM800 series.
So, you should use Adafruit_fona Library to communicate with Olimexino Nano GSM
Nano GSM module need 2A (3.7 to 4.2V DC) to  work well, it can not be powered by Arduino Board, if you don`t have enough power, 
this lead to shut-downs or restarts of the GSM module.


UART Rx of GSM module to  D3
UART Tx of GSM module to D2
UART GND of GSM Module to Arduino GND
CON1 Pin2 to Ground of Battery 
CON1 pin 6 to Positive terminal of The Battery
CON1 pin 14 to D4

