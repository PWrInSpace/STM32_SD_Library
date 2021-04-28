# STM32_SD_Library
Easy to implement library for SD card spi connection for STM32 &amp; HAL/CubeIDE.

Sources:
https://01001000.xyz/2020-08-09-Tutorial-STM32CubeIDE-SD-card/
http://elm-chan.org/fsw/ff/ffsample.zip

Setup guide:

1. Create or open new Cube Ide / CubeMX project and don't forget to turn on generatinc .c / .h files for peripherals, turn on debug (Serial Wire):

PIC TODO

2. Set up SPI interface as Full-Duplex Master:

PIC TODO

3. Set up FAST file system:

PIC TODO

4. Set up slave select pin and name it as shown below:

PIC TODO

5. Generate project code.
6. Copy the FASTFS folder to your project directory - replace if needed
7. In FASTFS/Target/user_diskio_spi.h file change the HAL library for your processor and spi handler number:

PIC TODO

8. Use an example code to save something on SD:

PIC TODO
