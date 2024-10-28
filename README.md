# Pepper-V2
V2 pepper PCB test

## Changes for Rev-3
- Replace the SWD and SWCLK on J7 with some I2C and UART capable GPIOs from Pico. The SWD and SWCLK weren't connected in Rev2 the way I thought they would be
- Replace TMP36 temperature sensor with a TMP235A (similar but cheaper)
- add ability to turn off SiPM 30V from Pico
- make test poinst 1.2mm in diameter (were 0.7mm)
- add logos (woo hoo) and CPERL/CLASSE names
