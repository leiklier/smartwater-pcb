# Smartwater


This repository contains project files for the PCB design of an IoT sensor node responsible for datalogging of pollution parameters in rivers. 

---

The product features a state-of-the art [ATmega4809](https://www.microchip.com/wwwproducts/en/ATMEGA4809) MCU, and transmits sensor data over LoRaWAN using the [RN2483A](https://www.microchip.com/wwwproducts/en/RN2483) module. By connecting it to a solar panel, the device will self-supplied with energy because of its built-in solar charger. It is designed for use with single cell Li-ion batteries. The sensors connecting to the device are all considered to be analog.

The design was done in Altium 19 in collaboration with [Bjørn Brodtkorb](https://github.com/bjornbrodtkorb) as part of the subject [TTT4270](https://www.ntnu.no/studier/emner/TTT4270/2018) at NTNU.

![3D model of the PCB](./static/PCB_3D_Screenshot.png)