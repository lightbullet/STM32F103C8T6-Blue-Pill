# STM32F103C8T6-Blue-Pill
The STM32F103C8T6 Blue Pill board is a development board for the ARM Cortex M3 microcontroller.

# Pinout
![STM32F103C8T6-Blue-Pill-Pin-Layout](docs/images/STM32F103C8T6-Blue-Pill-Pin-Layout.gif)

# Boot jumpers
- Boot0 = 0 & Boot1 = 0 : Normal bootloader boot with timeout
- Boot0 = 0 & Boot1 = 1 : Permanent DFU mode (no timeout)
- Boot0 = 1 & Boot1 = 0 : System ROM bootloader (serial)
- Boot0 = 1 & Boot1 = 1 : Boot to RAM
