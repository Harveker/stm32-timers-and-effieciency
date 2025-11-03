# STM32 Timers and Efficiency

An embedded systems project for STM32F401CCU microcontroller focusing on timer implementations and efficient code practices.

## Hardware
- STM32F401CCU6 (Black Pill development board)
- ARM Cortex-M4 with FPU
- 84 MHz maximum clock frequency

## Build Requirements
- ARM GCC toolchain (`arm-none-eabi-gcc`)
- Make
- OpenOCD or ST-Link for flashing

## Building
```bash
make
```

## Flashing
```bash
make flash
```
or use your preferred flash tool with the generated `.bin` or `.hex` file.

## Development Environment
This project can be opened with:
- VSCode with Cortex-Debug extension
- STM32CubeIDE
- Any text editor with ARM toolchain support

## License
See individual component licenses in the Drivers directory.
