# Automatic-Plant-Watering-System

## I. Introduction to the Problem and the Solution
The Automatic Plant Watering System is an Arduino-based automated system designed to monitor and maintain the health of your plants. By integrating sensors and automated controls, this system ensures your plants receive the right amount of water at the right time, reducing the need for manual intervention and enhancing plant care.

The system monitors critical environmental factors such as soil moisture and humidity. When the soil moisture level falls below a certain threshold, the system automatically activates a water pump DC to hydrate the plants. This automation helps create a stable and optimal growing environment, promoting healthier and more robust plant growth.

The problem that necessitates the existence of the Automatic Plant Watering System is the challenge of effectively managing plant care. Traditional methods require constant vigilance and manual effort to ensure plants receive adequate water and live in a suitable environment. Inconsistent watering and fluctuating environmental conditions can lead to plant stress, poor growth, or even death.

The Automatic Plant Watering System addresses these issues by providing an automated and precise solution for plant care. The system uses sensors to continuously measure soil moisture levels and environmental conditions. By collecting and analyzing this data, it can automatically adjust the watering schedule, ensuring plants are always in an optimal state for growth. This not only saves time and effort for gardeners but also significantly improves the chances of plant survival and productivity.

## II. Hardware Design and Implementation Details

### Moisture Sensor (YL-39)
<img src="https://github.com/XVORD/Automatic-Plant-Watering-System/assets/119683308/94af199a-b479-4f31-9556-8b296f3a98c9" alt="fOTO 1" width="200"/>
**Purpose**: To measure the moisture level in the soil or growing medium.
**Connection**: The YL-39 moisture sensor is connected to the Arduino board via digital input pins. It helps determine whether the soil is too dry or has adequate moisture, ensuring your plants get the right amount of water.

### Temperature and Humidity Sensor (DHT 11)
<img src="https://github.com/XVORD/Automatic-Plant-Watering-System/assets/119683308/477a43ec-5058-471d-86f2-ca67ca8bf060" alt="DHT11" width="200"/>
**Purpose**: To measure ambient temperature and humidity.
**Connection**: The DHT series 11 is connected to the Arduino board through digital input/output pins. This sensor provides essential data about the surrounding environment, allowing you to adjust conditions to suit your plants' needs.

### Water Pump DC
<img src="https://github.com/XVORD/Automatic-Plant-Watering-System/assets/119683308/8a131a69-626f-4d23-8bb7-b9dd4261d8a5" alt="water" width="200"/>
**Purpose**: To automatically water the plants when the soil moisture level is low.
**Connection**: The water pump is controlled by the Arduino through a relay module, which acts as a switch to turn the pump on and off.

### LED
<img src="https://github.com/XVORD/Automatic-Plant-Watering-System/assets/119683308/f7e6485a-b7a8-4003-b107-b1b5414c6bc9" alt="Led" width="200"/>
**Purpose**: To act as indicators of environmental quality humid or not.
**Connection**: Connected to digital output pins on the Arduino through resistors.

### Resistors
<img src="https://github.com/XVORD/Automatic-Plant-Watering-System/assets/119683308/1b9fa229-41fc-4fad-a325-f6e8371bed8f" alt="Ressitor" width="200"/>
**Purpose**: To limit the current passing through the LEDs, protecting them from damage.
**Connection**: Placed in series with each LED to ensure safe operation.

### Relay Module
<img src="https://github.com/XVORD/Automatic-Plant-Watering-System/assets/119683308/34817a2b-6eff-4e4f-b461-924f61b291cb" alt="Relay" width="200"/>
**Purpose**: To control the water pump by acting as a switch.
**Connection**: Connected to the Arduino and the water pump. The Arduino sends a signal to the relay module to turn the pump on or off.

## III. Software Implementation Details

## IV. Test Results and Performance Evaluation

## V. Conclusion and Future Work

## VI. How to use

## VII. Contributors
- Christopher Satya Fredella Balakosa
- 
