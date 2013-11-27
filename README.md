Complete-Python-Project-For-Arduino-
====================================

Handy python tool for Arduino Board (Based on  Command_API and the Pyserial)


Example :

from Arduino import Arduino

import time

board=Arduino("9600","COM3")

while True:

    print board.Internal_Temp()
    
    time.sleep(1)
    
