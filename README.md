# STM32UART
UART to serial monitor on stm32f446re nucleo board. Uses Polling mode, the microcontroller waits for transmission and reception.

Serial monitor used is the TM Terminal eclipse library, this can be implemented in the STM32CubeIde, so it made things easier :3. 
Just make sure to use the same parameters defined in the code, 115200 baud, 8N1 (8bits, no parity bits, 1 start bit)


