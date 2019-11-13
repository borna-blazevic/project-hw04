# project-hw04

FOR ADC:


Temperature sensor
The temperature sensor has to generate a voltage that varies linearly with temperature. The
conversion range is between 1.7 V and 3.6 V. The temperature sensor is internally
connected to the same input channel as VBAT, ADC1_IN18, which is used to convert the
sensor output voltage into a digital value. When the temperature sensor and VBAT
conversion are enabled at the same time, only VBAT conversion is performed.
As the offset of the temperature sensor varies from chip to chip due to process variation, the
internal temperature sensor is mainly suitable for applications that detect temperature
changes instead of absolute temperatures. If an accurate temperature reading is needed,
then an external temperature sensor part should be used.

from https://github.com/dumpram/project-lectures-fer/blob/master/lecture03/stm32f429zi.pdf

Did not really know how to change convert voltage to temperature, so used a formula for simmilar boards.
The temperature shows, around 25.6 degrees celsius which seems OK.

FOR BOTH:

Did not really get into the LCD, because it is not mentioned in the homework specification and exams are close, focused on trying to understand initialisation for ADC and MEMS components.
