# stm32f042c6t6




arm-none-eabi-objcopy f042led.elf  -O binary f042led.bin


sudo dfu-util -a 0 -s 0x08000000 --dfuse-address 0x08000000 -D f042led.bin
