CC= arm-none-eabi-gcc
CFLAGS=-c -mcpu=cortex-m4 -mthumb -std=gnu11 -Wall -O0
LDFLAGS= -nostdlib -T stm32_ls.ld
all:carwiper.o carwiper1.o MyStm32f407xx_gpio_driver.o stm32_startup.o finalled.elf

carwiper.o:carwiper.c
	$(CC) $(CFLAGS) -o $@ $^

carwiper1.o:carwiper1.c
	$(CC) $(CFLAGS) -o $@ $^
	
MyStm32f407xx_gpio_driver.o:MyStm32f407xx_gpio_driver.c
	$(CC) $(CFLAGS) -o $@ $^

stm32_startup.o:stm32_startup.c
	$(CC) $(CFLAGS) -o $@ $^

finalled.elf:main.o MyStm32f407xx_gpio_driver.o stm32_startup.o
	$(CC) $(LDFLAGS) -o $@ $^		
	
clean:
	rm -rf *.o *.elf
