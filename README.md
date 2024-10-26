## Title of the Project
"Real-Time Weather Monitoring Using IoT" focuses on leveraging Internet of Things technology to gather, analyze, and display weather data instantly. This project aims to provide accurate, up-to-date weather information, enhancing decision-making for various applications such as agriculture, disaster management, and urban planning.

## About
<!--Detailed Description about the project-->
—Using IoT technology along with a DHT1 humidity
 sensor and an element LED display, the system proposes a
 novel way of approaching the weather forecasting system with
 real-time weather data provided based on low-cost and easy
 deployable methods given the increasingly important nature of
 climate change and the rising demand for precise, location-based
 weather information. The NodeMCU microcontroller is able to
 transmit and access the internet, empowering the system to which
 it is connected. The DHT11 humidity sensor is used because it has
 a high accuracy of measurement of humidity and temperature.
 Data scans are continuously being monitored through sensor
 readings. Those data collected are transmitted through these
 sensor readings to a cloud server for proper analysis. In addition
 to such cloud-based.DIt features a prediction of whether it is
 going to rain or not by using NodeMCU, DHT1 humidity sensor,
 Internet of Things technology, and component LED display. The
 system will present real-time weather data in the form of an easily
 deployable and low-cost solution, considering that the impacts
 from climate change continue growing in effects, and thus there is
 the need for more precise and place-specific weather information.
 The system utilizes a NodeMCU microcontroller, which is Wi-Fi
 enabled, meaning that data transfer is through the internet. This
 acquires environmental data using the DHT11 humidity sensor,
 which is recognized for excellent sensing accuracy in humidity
 and temperature. Sensor data are sampled at specific intervals of
 time and forwarded to the cloud server for analysis and storage.
 Apart from the cloud accessibility, this system also contains an
 LED display component.For various purposes including outdoor
 recreation, transportation, and agriculture, it can give forecasts
 related to the weather. This system of Internet of Things based on
 weather forecasting enables it to take a choice based on current
 meteorological data. The benefits of this system include low
cost hardware, simple scalability, and the potential to collect
 crowdsourced weather data. Gathering data from numerous
 nodes positioned in different locations enhances the precision of
 the system while developing more local and accurate forecasting
 capabilities.
## Features
<!--List the features of the project as shown below-->
- Real-time weather data collection at a low cost, scalable, and energy-efficient.
- The system gathers weather data from sensors and a weather API, displaying it on an LED screen.
- Data is pushed to an IoT platform, where a machine learning model predicts upcoming weather conditions.
- Real-Time Weather Display
- Regular Data updates

## Requirements
<!--List the requirements of the project as shown below-->
* Determining the weather data that has to be collected.
* Setting up the hardware requirements 
  NodeMCU(ESP8266)
  DHT11 Sensor
  Rain Sensor
  LED Display
Connecting wires
* Programing the NodeMCU using Arduino IDE which will be able to collect the data from the sensor and weather api.
* Connecting to a weather API.
*  Pushing the data to a IOT platform such as BLYNK or THINGS SPEAK
 

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2024-10-24 103744](https://github.com/user-attachments/assets/49d88de9-be78-4f6f-95d5-1528d0343d77)



## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Blynk

![blynk](https://github.com/user-attachments/assets/06380036-8eaa-4fd1-b24c-f18473397aa7)

![blynk2](https://github.com/user-attachments/assets/80f0448b-866c-48c2-a46f-04edfb42154d)

#### Output2 - Thingspeak

![thingspeak](https://github.com/user-attachments/assets/67dfaf23-0b4b-419a-a601-28d7e3a7fb43)

![thingspeak 2](https://github.com/user-attachments/assets/6364b8d3-979a-4867-a554-c1c914f10083)




## Results and Impact
<!--Give the results and impact as shown below-->

The project showcases IoT technology in weather monitoring using NodeMCU and DHT11 sensors.
Key takeaways emphasize the fusion of technology with real-world applications in the IoT landscape.
Affordability
Environmental awareness
Empowering Decision-Making

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References
[1]        Dhanalakshmi, B., & Naidu, G. A. (2017, February). A survey on design and analysis of robust IoT architecture. In 2017 International Conference on Innovative Mechanisms for Industry Applications (ICIMIA) (pp. 375-378). IEEE.

 [2]    Krishnamurthi, K., Thapa, S., Kothari, L., & Prakash, A. (2015). Arduino based weather monitoring system. International Journal of Engineering Research and General Science, 3(2), 452-458.

 [3]      Sabharwal, N., Kumar, R., Thakur, A., & Sharma, J. (2014). A Low-Cost Zigbee Based automatic Wireless Weather Station With Gui And Web Hosting Facility. International Journal of Electrical and Electronics Engineering, 1. 

[4]      Mahmood, S. N., & Hasan, F. F. (2017). Design of weather monitoring system using Arduino based database implementation. Journal of Multidisciplinary Engineering Science and Technology (JMEST), 4(4), 7109.

 [5]     Yacchirema, D. C., Palau, C. E., & Esteve, M. (2017, January). Enable IoT interoperability in ambient assisted living: Active and healthy ageing scenarios. In 2017 14th IEEE Annual Consumer Communications & Networking Conference (CCNC) (pp. 53-58). IEEE.



