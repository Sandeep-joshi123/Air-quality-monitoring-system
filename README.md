# Air-quality-monitoring-system

Indoor Air Quality Monitoring System 🌬️💨
As part of our IoT (Internet of Things) course project, we were tasked with building an air quality monitoring system. After going through several research papers on the topic, we modified and improved the concept to create an Indoor Air Quality Monitoring System that ensures the safety and well-being of people in their homes. 🏠💡

Research Background 📚
In our research, we discovered several systems focused on monitoring air quality using IoT. These systems often addressed outdoor air quality but lacked focus on indoor environments, where pollutants from cooking, chemicals, and other sources can pose health risks. After studying existing approaches and identifying gaps, we decided to build a more efficient indoor air quality monitoring solution, tailored to help reduce accidents from LPG leaks and toxic gas exposure inside homes. 🌱🏠

Features 🔧
Continuous Monitoring of Toxic Gases: The system reads the concentration of different toxic gases present in the air using sensors like MQ135 (detects gases such as ammonia, benzene, and CO2) and MQ9 (detects gases like CO, methane, and LPG). 🌿💨

Real-Time Data Display: The LCD screen displays the real-time concentration of toxic gases, temperature 🌡️, and humidity 🌦️, giving users immediate feedback about their indoor air quality. 🖥️📊

Cloud Integration (ThingSpeak) ☁️: The system sends data to ThingSpeak, allowing users to visualize data and view the gas concentration levels, temperature, and humidity trends in the cloud. 📈🌐

Ventilator Control 🚪: If the gas concentration exceeds a critical threshold, the system opens the ventilators through servo motors to lower the gas levels and increase fresh air circulation, improving indoor air quality. 🌀💨

Safety Alerts 🚨: If dangerous gas levels are detected, the system activates a buzzer to alert people in the house, prompting them to take action quickly. 🚨🔊

Preventing LPG Leaks 🚒: This system plays a crucial role in reducing the risk of LPG leaks by detecting potential leaks and triggering the safety measures. 🔥💥

Challenges ⚠️
High Cost: Installing this system on a large scale can be expensive due to the cost of the sensors and actuators. 💸

Sensor Maintenance 🔧: Sensors like the MQ135 and MQ9 can degrade over time, which means they need to be replaced periodically to maintain accuracy. Additionally, environmental factors such as temperature and humidity can affect sensor readings, leading to the need for recalibration. 🌡️🌧️

Calibration Issues 🔍: Sensors may give inaccurate results due to fluctuations in temperature and humidity. Regular calibration is essential to ensure the system works reliably over time. 🧰

Components Used 🛠️
MQ135 Gas Sensor – For detecting gases like ammonia, benzene, alcohols, and CO2. 🌬️
MQ9 Gas Sensor – For detecting toxic gases such as CO, methane, and LPG. ⚡
DHT11 Sensor – Measures temperature and humidity. 🌡️💧
LCD Display – To show real-time data. 🖥️
Servo Motor – To control the opening and closing of the ventilators. 🤖
Buzzer – For immediate audio alerts. 🔔
ESP32 Microcontroller – The brain of the system, used for data processing and cloud communication. 💻
ThingSpeak Platform – To store and visualize data on the cloud. ☁️📊
How It Works 🛠️
The MQ135 and MQ9 sensors constantly measure the air quality and detect the concentration of gases. If the levels exceed the defined safe limits, the system takes action.
The DHT11 sensor constantly monitors the temperature and humidity levels in the environment, ensuring the data is accurate and reliable.
The ESP32 microcontroller processes all the data, sends it to ThingSpeak, and controls the servo motors to open the ventilators when necessary.
Ventilator Control: When the gas concentration exceeds a predefined critical threshold, the servo motor triggers the ventilators to open, allowing fresh air to circulate and reducing the concentration of harmful gases. 🌀💨
The ThingSpeak cloud platform allows users to access and monitor their indoor air quality in real-time from anywhere. 📱🌍
Future Enhancements 🔮
Sensor Calibration and Compensation: Develop algorithms for automatic sensor recalibration to account for changes in temperature and humidity. 🧑‍💻
Mobile App Integration 📱: Develop a mobile app for real-time monitoring and receiving alerts. 📲
Additional Sensors 🌱: Integrate more advanced sensors for detecting other harmful gases and improve accuracy.
SMS Alert Integration 📲: Improve the system by sending SMS alerts to the user whenever toxic gas levels exceed the critical threshold. This feature will ensure the user is informed and can take action even when they are not at home. 📱⚠️
Why is this project important? 🤔
Indoor air quality can significantly impact health, especially in confined spaces. Toxic gases such as CO, methane, and LPG can lead to accidents and long-term health issues. By creating an automated system that detects hazardous gas concentrations and responds by opening ventilators and sending alerts, we are enhancing safety and reducing risks associated with poor indoor air quality. 🛡️🌍

Credits 🙏
MQ135 and MQ9 sensor manufacturers for providing reliable air quality sensors.
ThingSpeak for offering a powerful platform for data collection and visualization.
ESP32 for its versatile microcontroller capabilities.
DHT11 for basic environmental monitoring.
Servo Motor and LCD Display for user interaction and control.
