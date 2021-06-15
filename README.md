# PWM_Example
PWM examples

1. L053R8_PWM
- NUCLEOL053R8 board
- STM32CubeMX 6.2.1
- STM32CubeIDE 1.6.1
- Timer2 Ch1~Ch4
- Timer clock / Target PWM frequency = ARR * Prescaler

ex1) PWM frequency : 1Hz</br>
32000000 / 1 = ARR * Prescaler</br>
Prescaler = 1600(Actual settin gvalue : 1600-1)</br>
ARR = 20000(Actual setting value : 20000-1)</br>
(Other combination of Prescaler and ARR is possible if 32000000=ARR*Prescaler contion is met)</br>

ex2) PWM frequency : 50Hz</br>
32000000 / 50 = ARR * Prescaler</br>
Prescaler = 64(Actual setting value : 64-1)</br>
ARR = 10000(Actual setting value : 10000-1)</br>
(Other combination of Prescaler and ARR is possible if 640000=ARR*Prescaler contion is met)</br>
