"# Instruments-for-CIROH" 

# Submersible Water Level and Ice Thickness Monitoring Sensor Prototype

## Overview

This repository contains the development and testing of a prototype for novel observation sensors designed to continuously measure changes in water level using pressure loggers. The goal is to collect observations in real-time and facilitate the monitoring of water levels.


## Components

### 1. Submersible Sensor Unit

The submersible sensor unit consists of the following components:

| Component Name                                                                                                                                                             | Quantity | Description                                                              | Unit Price (USD)                                                                                                                                            | Total Cost (USD)                                                                                                                                             |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|--------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Submersible Water Level Sensor](submersiblePressureSensors.md)                                                                                                            | 1        | Measures water pressure at specific depth                                | [$720](submersiblePressureSensors.md#L9)                                                                                                                    | [$720](submersiblePressureSensors.md#L9)                                                                                                                     |
| [Ice Thickness Probe](IceThicknessProbe.md)                                                                                                                                | 1        | Custom Design                                                            | [$350](IceThicknessProbe.md#L18)                                                                                                                            | [$350](IceThicknessProbe.md#L18)                                                                                                                             |
| [Temperature Sensor](https://www.adafruit.com/product/381?gad_source=1&gclid=Cj0KCQiAh8OtBhCQARIsAIkWb6_lTUc8ztyeZamatZAXVRI20XArqzOcbzk4sCRzwDLYhH72p3-LqV8aAjV1EALw_wcB) | 15       | WaterProof Temperature Sensor to calculate signal propagation underwater | [$10](https://www.adafruit.com/product/381?gad_source=1&gclid=Cj0KCQiAh8OtBhCQARIsAIkWb6_lTUc8ztyeZamatZAXVRI20XArqzOcbzk4sCRzwDLYhH72p3-LqV8aAjV1EALw_wcB) | [$150](https://www.adafruit.com/product/381?gad_source=1&gclid=Cj0KCQiAh8OtBhCQARIsAIkWb6_lTUc8ztyeZamatZAXVRI20XArqzOcbzk4sCRzwDLYhH72p3-LqV8aAjV1EALw_wcB) |



### 2. Real-time Data Transfer Unit

To enable real-time data transfer, a communication module is integrated into the system. This includes:

| Component Name                                 | Quantity | Description                                                        | Unit Price (USD) | Total Cost (USD) |
|------------------------------------------------|----------|--------------------------------------------------------------------|------------------|------------------|
| [Communication Module](communicationModule.md) | 1        | Enables real-time data transmission                                | $40              | $40              |
| [Power Supply](powerSupply.md)                 | 1        | Provides power to sensors and data logger and communication module | $70              | $70              |

### 3. Additional Components

| Component Name                                                                                                                                                                                                                                                                               | Quantity | Description                                                 | Unit Price (USD) | Total Cost (USD) |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|-------------------------------------------------------------|------------------|------------------|
| [Enclosure/Protection]                                                                                                                                                                                                                                                                       | 2        | Waterproof housing for sensors and logger (stainless steel) | $25              | $50              |
| [Mounting Hardware]                                                                                                                                                                                                                                                                          | 1        | Hardware to secure sensors in place                         | $40              | $40              |
| [Cables and Connectors](https://www.wireandcableyourway.com/submersible-pump-cable)                                                                                                                                                                                                          | 1        | Connects sensors to data logger                             | $30              | $30              |
| [Calibration Equipment](https://catalog.marquestscientific.com/item/solators-mini-tuff-guard-2-economy-gauge-installed/mini-tuff-gauge-isolator-2-economy-gauge-installed/mtg-22200s-pvc?gclid=Cj0KCQiA2KitBhCIARIsAPPMEhKZ0o6HKaEeIxSrRTRwFAI5jHU1AIoItZRNbcVqwtJxx7sKXvmgxLMaArjzEALw_wcB) | 1        | Instruments for sensor calibration                          | $50              | $50              |
| Software                                                                                                                                                                                                                                                                                     | 1        | Software for configuration and data analysis                | Included         | Included         |

## Estimated Total Cost 

 ### Total cost estimated between 

| Total Estimated Rough Cost                        | Cost per Instrument             |
|---------------------------------------------------|---------------------------------|
| [Instrument #1 (Ice Thickness)](README.md#L16)    | <strong>$500  </strong>         |
| [Instrument #2 (Water Level)](README.md#L16)      | <strong> $800 - $2000 </strong> |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   
| [Instrument #1 and Instrument #2)](README.md#L16) | <strong>$1300 - $2500</strong>  |
## Comments: (TO_DO igul)
- The submersible pressure sensor is crucial for accurately measuring water pressure at various depths.
- Consider selecting a temperature sensor with suitable precision for accurate water temperature measurements.
- The data logger plays a key role in recording and storing data; ensure compatibility with the selected sensors.
- In Spyros Beltaos' paper, the RBR TD-1050 or RBR TD-2050 sensors mentioned are no longer in production. Instead, it is possible to use RBR's new sensors. However, I have not yet been able to obtain the exact prices of these sensors. I will attempt to contact the company to obtain a price. There are also several alternative sensors available that can be used in place of RBR, ready for use. I have tried to list their features and prices, and you can find this list above.
- Certainly, the cost for a measurement system is not only the sensor itself but also includes other equipment that might be needed to set up a system. I have tried to compile a list of the equipment I think may be required for a setup, along with their approximate costs. You can find this list above.

## Sample Studies

- https://doi.org/10.1016/j.coldregions.2011.03.005 
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8706819/
- https://journals.ametsoc.org/view/journals/atot/36/4/jtech-d-18-0214.1.xml
- https://iopscience.iop.org/article/10.1088/0964-1726/17/4/045023
- https://conservancy.umn.edu/bitstream/handle/11299/108651/pr322.pdf?sequence=1
- https://www.mdpi.com/2073-4441/13/21/3139

