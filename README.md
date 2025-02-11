<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>

<h1>Indoor Air Quality Monitoring System 🌬️💨</h1>
<p>As part of our <strong>IoT (Internet of Things)</strong> course project, we were tasked with building an air quality monitoring system. After going through several research papers on the topic, we modified and improved the concept to create an Indoor Air Quality Monitoring System that ensures the safety and well-being of people in their homes. 🏠💡</p>

<h2>Research Background 📚</h2>
<p>In our research, we discovered several systems focused on monitoring air quality using IoT. These systems often addressed outdoor air quality but lacked focus on indoor environments, where pollutants from cooking, chemicals, and other sources can pose health risks. After studying existing approaches and identifying gaps, we decided to build a more efficient indoor air quality monitoring solution, tailored to help reduce accidents from LPG leaks and toxic gas exposure inside homes. 🌱🏠</p>

<h2>Features 🔧</h2>
<ul>
    <li><strong>Continuous Monitoring of Toxic Gases:</strong> The system reads the concentration of different toxic gases present in the air using sensors like MQ135 (detects gases such as ammonia, benzene, and CO2) and MQ9 (detects gases like CO, methane, and LPG). 🌿💨</li>
    <li><strong>Real-Time Data Display:</strong> The LCD screen displays the real-time concentration of toxic gases, temperature 🌡️, and humidity 🌦️, giving users immediate feedback about their indoor air quality. 🖥️📊</li>
    <li><strong>Cloud Integration (ThingSpeak) ☁️:</strong> The system sends data to ThingSpeak, allowing users to visualize data and view the gas concentration levels, temperature, and humidity trends in the cloud. 📈🌐</li>
    <li><strong>Ventilator Control 🚪:</strong> If the gas concentration exceeds a critical threshold, the system opens the ventilators through servo motors to lower the gas levels and increase fresh air circulation, improving indoor air quality. 🌀💨</li>
    <li><strong>Safety Alerts 🚨:</strong> If dangerous gas levels are detected, the system activates a buzzer to alert people in the house, prompting them to take action quickly. 🚨🔊</li>
    <li><strong>Preventing LPG Leaks 🚒:</strong> This system plays a crucial role in reducing the risk of LPG leaks by detecting potential leaks and triggering the safety measures. 🔥💥</li>
</ul>

<h2>Challenges ⚠️</h2>
<ul>
    <li><strong>High Cost:</strong> Installing this system on a large scale can be expensive due to the cost of the sensors and actuators. 💸</li>
    <li><strong>Sensor Maintenance 🔧:</strong> Sensors like the MQ135 and MQ9 can degrade over time, which means they need to be replaced periodically to maintain accuracy. Additionally, environmental factors such as temperature and humidity can affect sensor readings, leading to the need for recalibration. 🌡️🌧️</li>
    <li><strong>Calibration Issues 🔍:</strong> Sensors may give inaccurate results due to fluctuations in temperature and humidity. Regular calibration is essential to ensure the system works reliably over time. 🧰</li>
</ul>

<h2>Components Used 🛠️</h2>
<ul>
    <li><strong>MQ135 Gas Sensor:</strong> For detecting gases like ammonia, benzene, alcohols, and CO2. 🌬️</li>
    <li><strong>MQ9 Gas Sensor:</strong> For detecting toxic gases such as CO, methane, and LPG. ⚡</li>
    <li><strong>DHT11 Sensor:</strong> Measures temperature and humidity. 🌡️💧</li>
    <li><strong>LCD Display:</strong> To show real-time data. 🖥️</li>
    <li><strong>Servo Motor:</strong> To control the opening and closing of the ventilators. 🤖</li>
    <li><strong>Buzzer:</strong> For immediate audio alerts. 🔔</li>
    <li><strong>ESP32 Microcontroller:</strong> The brain of the system, used for data processing and cloud communication. 💻</li>
    <li><strong>ThingSpeak Platform:</strong> To store and visualize data on the cloud. ☁️📊</li>
</ul>

<h2>How It Works 🛠️</h2>
<ul>
    <li>The MQ135 and MQ9 sensors constantly measure the air quality and detect the concentration of gases. If the levels exceed the defined safe limits, the system takes action.</li>
    <li>The DHT11 sensor constantly monitors the temperature and humidity levels in the environment, ensuring the data is accurate and reliable.</li>
    <li>The ESP32 microcontroller processes all the data, sends it to ThingSpeak, and controls the servo motors to open the ventilators when necessary.</li>
    <li><strong>Ventilator Control:</strong> When the gas concentration exceeds a predefined critical threshold, the servo motor triggers the ventilators to open, allowing fresh air to circulate and reducing the concentration of harmful gases. 🌀💨</li>
    <li>The ThingSpeak cloud platform allows users to access and monitor their indoor air quality in real-time from anywhere. 📱🌍</li>
</ul>

<h2>Future Enhancements 🔮</h2>
<ul>
    <li><strong>Sensor Calibration and Compensation:</strong> Develop algorithms for automatic sensor recalibration to account for changes in temperature and humidity. 🧑‍💻</li>
    <li><strong>Mobile App Integration 📱:</strong> Develop a mobile app for real-time monitoring and receiving alerts. 📲</li>
    <li><strong>Additional Sensors 🌱:</strong> Integrate more advanced sensors for detecting other harmful gases and improve accuracy.</li>
    <li><strong>SMS Alert Integration 📲:</strong> Improve the system by sending SMS alerts to the user whenever toxic gas levels exceed the critical threshold. This feature will ensure the user is informed and can take action even when they are not at home. 📱⚠️</li>
</ul>

<h2>Why is this project important? 🤔</h2>
<p>Indoor air quality can significantly impact health, especially in confined spaces. Toxic gases such as CO, methane, and LPG can lead to accidents and long-term health issues. By creating an automated system that detects hazardous gas concentrations and responds by opening ventilators and sending alerts, we are enhancing safety and reducing risks associated with poor indoor air quality. 🛡️🌍</p>

<h2>Credits 🙏</h2>
<ul>
    <li><strong>MQ135 and MQ9 sensor manufacturers</strong> for providing reliable air quality sensors.</li>
    <li><strong>ThingSpeak</strong> for offering a powerful platform for data collection and visualization.</li>
    <li><strong>ESP32</strong> for its versatile microcontroller capabilities.</li>
    <li><strong>DHT11</strong> for basic environmental monitoring.</li>
    <li><strong>Servo Motor and LCD Display</strong> for user interaction and control.</li>
</ul>

</body>
</html>
