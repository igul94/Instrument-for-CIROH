"# Instruments-for-CIROH" 

# Submersible Water Level and Ice Thickness Monitoring Sensor Prototype

## Overview

This repository contains the development and testing of a prototype for novel observation sensors designed to continuously measure changes in water level using pressure loggers. The goal is to collect observations in real-time and facilitate the monitoring of water levels.


## Components

### 1. Submersible Sensor Unit

The submersible sensor unit consists of the following components:

| Component Name              | Quantity | Description                                     | Unit Price (USD) | Total Cost (USD) |
|-----------------------------|----------|-------------------------------------------------|-------------------|------------------|
| [Submersible Water Level Sensor](submersiblePressureSensors.md)  | 1        | Measures water pressure at specific depth       | [$650](submersiblePressureSensors.md#L9)| $650 |
| [Ice Thickness Probe]          | 1        | Custom Design                     | [Unit Price]      | [Total Cost]     |
<!-- | Data Logger                | 1        | Records and stores sensor data                   | $350 | $350 |-->

### 2. Real-time Data Transfer Unit

To enable real-time data transfer, a communication module is integrated into the system. This includes:

| Component Name          | Quantity | Description                             | Unit Price (USD) | Total Cost (USD) |
|-------------------------|----------|-----------------------------------------|-------------------|------------------|
| [Communication Module](communicationModule.md) | 1        | Enables real-time data transmission      | $40 | $40 |
| [Power Supply](powerSupply.md) | 1 | Provides power to sensors and data logger and communication module| $70 | $70 |

### 3. Additional Components

| Component Name          | Quantity | Description                                   | Unit Price (USD) | Total Cost (USD) |
|-------------------------|----------|-----------------------------------------------|-------------------|------------------|
| [Enclosure/Protection]   | 2        | Waterproof housing for sensors and logger (stainless steel)     | $25 | $50 |
| [Mounting Hardware]   | 1        | Hardware to secure sensors in place           | $40 | $40 |
| [Cables and Connectors](https://www.wireandcableyourway.com/submersible-pump-cable)    | 1        | Connects sensors to data logger               | $30 | $30 |
| [Calibration Equipment](https://catalog.marquestscientific.com/item/solators-mini-tuff-guard-2-economy-gauge-installed/mini-tuff-gauge-isolator-2-economy-gauge-installed/mtg-22200s-pvc?gclid=Cj0KCQiA2KitBhCIARIsAPPMEhKZ0o6HKaEeIxSrRTRwFAI5jHU1AIoItZRNbcVqwtJxx7sKXvmgxLMaArjzEALw_wcB)  | 1        | Instruments for sensor calibration           |  $50 |  $50 |
| Software                | 1        | Software for configuration and data analysis | Included | Included |

## Comments: (TO_DO igul)
- The submersible pressure sensor is crucial for accurately measuring water pressure at various depths.
- Consider selecting a temperature sensor with suitable precision for accurate water temperature measurements.
- The data logger plays a key role in recording and storing data; ensure compatibility with the selected sensors.

## Sample Studies

- https://doi.org/10.1016/j.coldregions.2011.03.005 
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8706819/

