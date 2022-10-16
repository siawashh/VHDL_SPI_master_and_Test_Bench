# VHDL SPI Master + Test Bench
# Serial peripheral interface
Serial peripheral interface (SPI) is one of the most widely used interfaces between microcontroller and peripheral ICs such as sensors, ADCs, DACs, shift registers, SRAM, and others. SPI is a common communication protocol used by many different devices. For example, SD card modules, RFID card reader modules, and 2.4 GHz wireless transmitter/receivers all use SPI to communicate with microcontrollers.
#  VHDL code will..
Creates master based on input configuration.
// Sends a byte one bit at a time on MOSI
// Will also receive byte data one bit at a time on MISO.
// Any data on input byte will be shipped out on MOSI.
# Test bench code will..
test the protocol with a few senario
# this is a tested and standard VHDL code + test bench for SPI (Serial Peripheral Interface) Master
