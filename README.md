# STM32_UART
UART coursework:

1) Pseudocode for UART_Tx w/o HAL

   - RCC to be enabled for GPIOA (USART1_Tx @ PA9) & for USART1 Peripheral  
   - MODER to be configured for PA9     
   - Setup AFR register   
   - USART_BRR (Here: 2400bps)   
   - USART_CR1 (Transmit Enable & USART Enable)   
   - SR to check status   
   - DR to load data for transmit  
