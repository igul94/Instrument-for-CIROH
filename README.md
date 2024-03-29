"# Instruments-for-CIROH"

# Submersible Water Level and Ice Thickness Monitoring Sensor Prototype

<div style="text-align:center;">
  <img src="./CIROH logo.png" alt="CIROH Logo" width="300" />
</div>

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

- [Skimmer](https://www.lowrance.com/lowrance/type/sonar-transducers/hst-wsbl/)

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

| Total Estimated Rough Cost                       | Cost per Instrument             |
|--------------------------------------------------|---------------------------------|
| [Instrument #1 (Ice Thickness)](README.md#L16)   | <strong>$500  </strong>         |
| [Instrument #2 (Water Level)](README.md#L16)     | <strong> $800 - $2000 </strong> |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   
| [Instrument #1 and Instrument #2](README.md#L16) | <strong>$1300 - $2500</strong>  |
## Comments:
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




# Camera Installation to flood inundation sensors
<div style="text-align:center;">
  <img src="./NOAA Print.png" alt="NOAA Logo" width="300" />
</div>

Camera Installation to flood inundation sensors with NOAA
 
[Camera Selection Guide](objectives.md)
## Comments
    - Hellium network is not suitable for video stream but still considerable if the FPS will be so low
    
## Type of Camera
    - FPS ???
    - Resolution
    - Night Vision ???
    - Stream method
#### Low cost - Low Power - Arduino Compatible dev boards with camera

| Camera                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Cost | Features |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|----------|
| [ESP32 Camera WiFi+Bluetooth Module](https://www.makerfocus.com/products/esp32-camera-wifi-bluetooth-module)                                                                                                                                                                                                                                                                                                                                                                                                                            | $15  |          |
| [Sipeed Maix Bit K210 64bit](https://www.digikey.com/en/products/detail/seeed-technology-co.,-ltd/110991190/9975976?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Low%20ROAS%20Categories&utm_term=&utm_content=&utm_id=go_cmp-20243063506_adg-_ad-__dev-c_ext-_prd-9975976_sig-Cj0KCQiAh8OtBhCQARIsAIkWb6-6A74-XL5f48BvZ69eASE90AnRtV8Io-eN3n46N71rqQogtW-q2NoaAkAvEALw_wcB&gad_source=1&gclid=Cj0KCQiAh8OtBhCQARIsAIkWb6-6A74-XL5f48BvZ69eASE90AnRtV8Io-eN3n46N71rqQogtW-q2NoaAkAvEALw_wcB)      | $36  |          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 
| [M5 sticky V AI camera](https://www.digikey.com/en/products/detail/m5stack-technology-co.,-ltd./U078-V-M12/21286982?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Low%20ROAS%20Categories&utm_term=&utm_content=&utm_id=go_cmp-20243063506_adg-_ad-__dev-c_ext-_prd-21286982_sig-Cj0KCQiAh8OtBhCQARIsAIkWb69EGfe28wLLSk8QPSt7fifGp6WywfPRRScBMqqclcjL1fXXzUd40dUaAtRdEALw_wcB&gad_source=1&gclid=Cj0KCQiAh8OtBhCQARIsAIkWb69EGfe28wLLSk8QPSt7fifGp6WywfPRRScBMqqclcjL1fXXzUd40dUaAtRdEALw_wcB)     | $40  |          |
| [openmv cam H7](https://www.adafruit.com/product/4478?gad_source=1&gclid=Cj0KCQiAh8OtBhCQARIsAIkWb6-XlQuPVTSEuBsd_kampCI1g9QpBg4FmhK_fLXMr88H4xOVy018KLUaArGcEALw_wcB)                                                                                                                                                                                                                                                                                                                                                                  | $85  |          |
| [Grove - Vision AI Module](https://www.seeedstudio.com/Grove-Vision-AI-Module-p-5457.html)                                                                                                                                                                                                                                                                                                                                                                                                                                              | $16  |          |
| [Seeed Studio XIAO ESP32S3 Sense](https://www.digikey.com/en/products/detail/seeed-technology-co.,-ltd/110991190/9975976?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Low%20ROAS%20Categories&utm_term=&utm_content=&utm_id=go_cmp-20243063506_adg-_ad-__dev-c_ext-_prd-9975976_sig-Cj0KCQiAh8OtBhCQARIsAIkWb6-6A74-XL5f48BvZ69eASE90AnRtV8Io-eN3n46N71rqQogtW-q2NoaAkAvEALw_wcB&gad_source=1&gclid=Cj0KCQiAh8OtBhCQARIsAIkWb6-6A74-XL5f48BvZ69eASE90AnRtV8Io-eN3n46N71rqQogtW-q2NoaAkAvEALw_wcB) | $14  |          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 
| [RASPBERRY-PI RPI4-MODBP-4GB](https://www.newark.com/raspberry-pi/rpi4-modbp-4gb/raspberry-pi-4-model-b-4gb/dp/02AH3164?COM=ref_hackster&CMP=Hackster-NA-project-998505-Jan-24)                                                                                                                                                                                                                                                                                                                                                         | $55  |          |
| [Nicla Vision](https://store-usa.arduino.cc/products/nicla-vision)                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | $115 |          |
| [Arducam Pico4ML TinyML Dev](https://www.uctronics.com/-rp2040-based-arducam-pico4ml-dev-board-for-machine-vision.html)                                                                                                                                                                                                                                                                                                                                                                                                                 | $26  |          |
| [Realtek AMB82-Mini IoT AI Camera Arduino Dev. board](https://www.seeedstudio.com/AMB82-MINI-RTL8735B-IoT-AI-Camera-Dev-Board-p-5584.html?gad_source=1&gclid=Cj0KCQiAh8OtBhCQARIsAIkWb6_6i0mhDJ9fjYh9ZBPlKYJ89R_7X5feoizvbGQkdMcf3Louhpfuur8aAhnZEALw_wcB)                                                                                                                                                                                                                                                                              | $25  |          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | $115 |          |


#### Security Cameras

| Camera                                                                                                                                                                                                                                                                                                                                                                   | Cost | Features                                                                                                                       |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|--------------------------------------------------------------------------------------------------------------------------------|
| [Wyze Cam Outdoor](https://www.wyze.com/products/wyze-cam-outdoor)                                                                                                                                                                                                                                                                                                       | $74  | Weather-resistant, 1080p HD video, Night vision, Motion detection, Two-way audio                                               |
| [Blink Outdoor](https://www.amazon.com/All-New-Blink-Outdoor-Floodlight-Camera/dp/B0BBX45V5B?maas=maas_adg_E6DD927B58F595A4E32792B58DF8ED2A_afap_abs&ref_=aa_maas&tag=maas)                                                                                                                                                                                              | $130 | Weather-resistant, HD video, Motion detection, Wire-free                                                                       |
| [Reolink Argus 2](https://reolink.com/product/argus-2e/)                                                                                                                                                                                                                                                                                                                 | $77  | Weatherproof, 1080p HD video, Night vision, Motion detection, Two-way audio                                                    |
| [Zmodo Outdoor](https://www.zmodo.com/1080p-outdoor-wifi-camera)                                                                                                                                                                                                                                                                                                         | $32  | Weather-resistant, 720p HD video, Motion detection, Night vision                                                               |
| [Xiaomi Mi Home](https://www.amazon.com/Xiaomi-Weatherproof-Detection-Time-Lapse-Photography/dp/B0CCR98C8F/ref=asc_df_B0CCR98C8F/?tag=hyprod-20&linkCode=df0&hvadid=673653936678&hvpos=&hvnetw=g&hvrand=17055244995071933241&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9003488&hvtargid=pla-2205244239275&psc=1&mcid=247f7c329bcc30d893b45bc24e23516e) | $50  | Indoor camera (suitable for outdoor use with proper protection), 1080p HD video, Motion detection, Night vision, Two-way audio |

## IoT Video Streaming Architecture

![IoT Architecture](./iot_architecture.png)

1. **IoT Devices:**
   - These are the devices equipped with cameras or sensors to capture video data. Examples include surveillance cameras, smart cameras, or sensors with video capabilities.

2. **Edge Devices:**
   - Intermediate devices located closer to the IoT devices for initial processing of video data. This can involve preprocessing, filtering, or compression to reduce the data size before transmission.

3. **Gateway:**
   - The gateway aggregates data from multiple edge devices and sends it to the central server. It may perform additional processing and act as a bridge between edge devices and the central server.

4. **Central Server or Cloud:**
   - This is where the main processing and storage of video data occur. Cloud-based services are commonly used for scalability and accessibility. Advanced analytics, storage, and management take place here.

5. **User Interface:**
   - Applications or interfaces that allow users to view, control, and interact with the video streams. This could be a web interface, mobile app, or other visualization tools.

## Streaming Protocols
    - HTTP (HLS)
    - WebRTC
    - RTSP

1. **Real-Time Streaming Protocol (RTSP):**
   - A standard protocol used for establishing and controlling media sessions between endpoints. It's commonly used for live streaming and supports various video and audio formats.

2. **Hypertext Transfer Protocol (HTTP):**
   - HTTP-based streaming protocols, like HTTP Live Streaming (HLS) and Dynamic Adaptive Streaming over HTTP (DASH), are widely used for adaptive bitrate streaming. They allow adjusting the quality based on network conditions.

3. **WebRTC (Web Real-Time Communication):**
   - A free, open-source project that enables real-time communication between web browsers, mobile applications, and IoT devices via simple application programming interfaces (APIs). It is suitable for low-latency applications.

4. **MQTT (Message Queuing Telemetry Transport):**
   - A lightweight messaging protocol suitable for IoT applications. While not specifically designed for video streaming, it can be used for transmitting video-related data and commands between devices.

5. **CoAP (Constrained Application Protocol):**
   - Designed for resource-constrained devices and networks. It's suitable for IoT scenarios where devices may have limited resources.

Choosing the right protocol depends on factors like latency requirements, bandwidth constraints, and the nature of the IoT application.

    - https://developer.tuya.com/en/iot-video-live-stream?_source=27a82e932e7eef2e999cd6f7c925541d&bd_vid=8634295905315177986
    - https://www.mdpi.com/2624-831X/4/4/21

## Offered Selection

   - ESP32 Camera
   - Heltec Lora AB01 Board 
   - HTTP (HLS) Protocol
   - Crowdsourcing (optional): A mobile app pr web page could be designed to upload images of flood.

   ### Comments on this selection
Best Streaming Protocol for Heltec AB01 Board to Stream Video over Helium Network

For streaming video over the Helium network using a Heltec LoRa AB01 board, it's essential to consider the constraints of the LoRa network, such as low bandwidth and intermittent connectivity. Given these constraints, the best streaming protocol would be one that is optimized for low bandwidth and can adapt to varying network conditions. In this context, HTTP Live Streaming (HLS) would likely be the most suitable choice. Here's why:

1. **Bandwidth Efficiency**: HLS segments video into smaller chunks, allowing for efficient use of bandwidth. This segmentation is particularly advantageous for low-bandwidth networks like LoRa.

2. **Adaptive Streaming**: HLS supports adaptive bitrate streaming, meaning it can adjust the video quality based on the available network bandwidth. This adaptability is crucial for maintaining a consistent streaming experience over the fluctuating connectivity of the Helium network.

3. **Resilience to Packet Loss**: HLS is designed to handle packet loss gracefully. Each segment of the video stream is independent, so the loss of a single segment does not affect the playback of subsequent segments. This resilience is beneficial for maintaining video quality over the Helium network, which may experience packet loss due to its long-range and low-power nature.

4. **Widely Supported**: HLS is a widely supported streaming protocol, with support across various platforms and devices. This compatibility makes it easier to integrate with different client applications for viewing the streamed video.

5. **Ease of Implementation**: Implementing HLS streaming on the Heltec LoRa AB01 board should be feasible, as it primarily involves segmenting the video stream into chunks and serving them over HTTP. The Heltec LoRa AB01 board can handle HTTP communication, and HLS libraries are available for encoding and decoding video streams.

Overall, HTTP Live Streaming (HLS) is the best streaming protocol for streaming video over the Helium network using a Heltec LoRa AB01 board, as it offers bandwidth efficiency, adaptive streaming, resilience to packet loss, wide support, and ease of implementation.

## Crowdsourcing Platforms
   - [USGS Flood Event Viewer](https://stn.wim.usgs.gov/FEV/) 
   - [NOAA's National Water Center (NWC) Flood Inundation Mapping](https://water.weather.gov/ahps/inundation.php)
   - [CrowdHydrology](http://www.crowdhydrology.com/)
   - [FloodCrowd](https://crowdandcloud.org/floodcrowd) (UK)

### USGS Flood Event Viewer

In the United States, one example of a flood inundation crowdsourcing platform is **USGS Flood Event Viewer**.

- **Purpose**: The USGS Flood Event Viewer is a platform developed by the United States Geological Survey (USGS) to provide real-time flood inundation mapping and crowd-sourced flood observations.
- **User Interface**: It offers a user-friendly web interface where users can access flood maps, submit flood reports, and view flood-related data.
- **Flood Mapping**: The platform displays real-time flood inundation maps based on data from USGS streamgages, weather forecasts, and user-contributed observations.
- **Crowdsourcing**: Users can report flood events by providing location information, photos, videos, and descriptions of flood impacts. These reports are integrated into the flood mapping system to enhance situational awareness.
- **Data Visualization**: The USGS Flood Event Viewer presents flood data through interactive maps, graphs, and charts, allowing users to explore flood extents, water levels, and historical flood events.
- **Alerting System**: The platform provides alerts and notifications to users in flood-prone areas, including flood warnings, evacuation notices, and updates on flood conditions.
- **Integration**: It integrates with other federal, state, and local agencies involved in flood monitoring and emergency response, facilitating data sharing and coordination efforts.
- **Data Quality Control**: The USGS implements quality control measures to ensure the accuracy and reliability of flood data, including validation of user-contributed reports and calibration of hydrological models.
- **Public Engagement**: The platform encourages public engagement in flood monitoring and resilience planning by providing educational resources, outreach materials, and opportunities for community participation.
- **Accessibility**: The USGS Flood Event Viewer is accessible to users across the United States and is compatible with desktop computers, mobile devices, and GIS software.

The USGS Flood Event Viewer serves as a valuable resource for flood monitoring, risk assessment, and emergency management in the United States, leveraging both scientific data and citizen observations to improve flood preparedness and response efforts.

## Sample Studies and Related Works
#### Studies
- https://doi.org/10.1016/j.measurement.2018.05.100
- https://doi.org/10.1145/3495243.3558264
- https://doi.org/10.3389/frwa.2021.766918
- https://doi.org/10.3390/iot4040021
- https://doi.org/10.1080/02626667.2022.2079415
- https://doi.org/10.3390/rs13142661
- https://doi.org/10.3390/s19225012
- https://doi.org/10.3390/s23146314
- https://doi.org/10.1029/2008WR006950
- https://doi.org/10.3390/w15183233
#### Url's
- https://bigbadcrad.shinyapps.io/SHARKS/
- https://www.cnx-software.com/2024/01/19/16-grove-vision-ai-v2-module-features-wiseeye2-hx6538-arm-cortex-m55-ethos-u55-ai-microcontroller/
- https://www.cnx-software.com/2022/10/31/tinyml-cam-pipeline-esp32-fast-image-recognition/
- https://www.hackster.io/limengdu0117/2024-mcu-ai-vision-boards-performance-comparison-998505
- https://www.arducam.com/product/rp2040-based-arducam-pico4ml-dev-board-for-machine-vision/
- https://github.com/bharathsudharsan/TinyML-CAM
- https://www.tenevia.com/en/sensor/cam-level-water-level-measurement-by-camera/#:~:text=CamLevel%20operates%20with%20a%20conventional,in%20the%20near%20infrared%20spectrum
- https://www.abc4.com/news/wasatch-front/mobile-cameras-installed-along-utah-rivers-and-streams-to-monitor-water-levels/
- https://www.arducam.com/product/hm01b0-qvga-monochrome-dvp-camera-module-for-arduino-giga-r1-wifi-board/
- https://www.youtube.com/watch?v=fWxw7mcvguo
- https://www.youtube.com/watch?v=MKiITEsOwRA
- https://ciroh.ua.edu/research-projects/leveraging-usgs-hydrologic-imagery-visualization-and-information-system-hivis-for-an-operational-monitoring-of-streamflow-using-computer-vision/
- https://www.stevens.edu/news/temimi-and-liu-awarded-usd870-614-united-states-geological-survey-grant-to
- https://www.smartlagoon.eu/2023/11/20/bodoque-an-energy-efficient-flow-monitoring-system-for-ephemeral-streams/
- https://webcoos.org/
- https://collaboratory.unc.edu/wp-content/uploads/sites/476/2021/04/flood-resiliency-data-collection-and-data-analytic-in-support-of-flood-management.pdf
- https://sunnydayflood.apps.cloudapps.unc.edu/
- https://lbfoster.com/rail/total-track-monitoring/flood-monitoring
- https://www.cbs17.com/news/north-carolina-news/ncdot-early-flood-warning-system-up-for-national-award/

# Flood Sensor Robust Solution Cost Estimate

| Item                                                                                                                                                                                                                                                                                                                      | Qty per sensor | Cost of each unit | Cost per sensor |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|-------------------|-----------------| 
| [ToughSonic 50 Ultrasonic Sensor](https://primebuy.com/product/senix-tspc-21srm-232-toughsonic-50-ultrasonic-sensor-rs-232?format=v&p=eb&msrc=gglds&source=ads&gclid=Cj0KCQiAwvKtBhDrARIsAJj-kTi-XLn1jKG8T_e4j_16Ho6Rw143z7zOMU_HTaKFGYosGWT2omC1NXcaAgVlEALw_wcB)                                                        | 1              | $1,404            | $1,404          |
| [Industrial-Grade Optical Rain Gauge RG-15 Rain Sensor](https://www.seeedstudio.com/Rain-Gauge-RG-15-p-4648.html?gad_source=1&gclid=Cj0KCQiAwvKtBhDrARIsAJj-kThdWk1sABTx0GbzoXt2Bon21ZJ2vs-PGOii1uwpiXR4nQDrg26HnaIaAgluEALw_wcB)                                                                                         | 1              | $99.00            | $99.00          |
| [RockBLOCK 9603N - Iridium SatComm Module](https://www.sparkfun.com/products/14498)                                                                                                                                                                                                                                       | 1              | $267.50           | $267.50         |
| [Nicla Vision Camera](https://store-usa.arduino.cc/products/nicla-vision)                                                                                                                                                                                                                                                 | 1              | $115.00           | $115.00         |
| [0.6W solar panel](https://voltaicsystems.com/0-6-watt-6-volt-solar-panel-etfe/)                                                                                                                                                                                                                                          | 8              | $9.00             | $72.00          | 
| [0.6W panel gasket](https://voltaicsystems.com/gasket-0-6w/)                                                                                                                                                                                                                                                              | 8              | $1.50             | $12.00          |                                                                                                                      
| [SatCom Antenna](https://osat.com/products/scan-antenna-iridium-go-kit-5m?variant=41884023521432&currency=usd&utm-medium=product-sync&utm-source=google&utm-content=sag-organic&utm-campaign=sag-organic&gad-source=1&gclid=cj0kcqiawvktbhdrarisajj-ktgeqkfdvhv-euvsx2jw95kvdvjyrw3rc8mrkqnplc3ygwkfo1c30y4aah0dealw-wcb) | 1              | $159.66           | $159.66         |
| [Battery (400mAh)](https://www.mouser.com/ProductDetail/Adafruit/3898?qs=byeeYqUIh0NUfilp6w7tLA%3D%3D)                                                                                                                                                                                                                    | 8              | $6.95             | $55.60          |
| [Housing](https://www.polycase.com/ml-22f)                                                                                                                                                                                                                                                                                | 1              | $10.64            | $10.64          |
| [Heltec AB02](https://heltec.org/project/htcc-ab02/)                                                                                                                                                                                                                                                                      | 1              | $14.40            | $14.40          |                                                                                                                      
| [uFl to SMA female](https://www.amazon.com/onelinkmore-Connector-Pigtail-Bulkhead-Extension/dp/B01AJQ33Y4/)                                                                                                                                                                                                               | 1              | $6.28             | $6.28           |
| [Lora Antenna](https://www.digikey.com/en/products/detail/linx-technologies-inc/ANT-916-CW-HWR-SMA/1139580)                                                                                                                                                                                                               | 1              | $12.85            | $12.85          |
| TOTAL                                                                                                                                                                                                                                                                                                                     |                |                   | $2,228.93       |  

## Features of Offered Selection

   - Robust ultrasonic sensor for water measurement (precise measurement of water level)
   - RockBLOCK + Heltec telecommunication board (SatCom + Lora) 
   - Camera (integrated motion sensor, integrated microphone and integrated distance sensor)
   - Rain Gauge Sensor(triggers starting video stream or capture frame when rain starts)

<!--| [VEGAPULS C 23 Radar Water Level Sensor](https://www.vega.com/en-us/products/product-catalog/level/radar/vegapuls-c-23)                                                                                                                                                                                            | 1              | $1.385            | $1.385          |-->