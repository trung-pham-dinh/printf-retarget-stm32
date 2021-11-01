# printf-retarget-stm32
Retarget the printf() of stdio.h to send data to a custom UART(HAL library)\
Call init_uart_printf() in the beginning, then just call printf() if you want to print something
