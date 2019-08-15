This contains the design of a printed circuit board that can be powered by an Aeotec Nano Dimmer. It provides a touch pad that acts as an external momentary switch to the Nano Dimmer for controlling its load.

The size of the circuit board is suited for replacing the smarts in a Legrand Adorne touch switch.

The CAMOutputs can be zipped up and sent to a board fabrication shop.

Tuning ...

R1 (4k7Ω) was chosen to roughly match the LED intensity of an original Legrand Adorne touch switch.

According the the AT42QT1010 sensor datasheet (http://ww1.microchip.com/downloads/en/devicedoc/40001946a.pdf), touch sensitivity can be increased by increasing Cs, usually from 2–50nF. This (C2, 10nF) was chosen to match that on a SparkFun Capacitive Touch Breakout board (https://www.sparkfun.com/products/12041). On the bench, however, this seemed to sensitive and  was changed to 6.6nF (3 2.2nF stacked).
