# Smart-Parking-System
An Arduino UNO microcontroller-based hardware simulation

---

## Objective
The objective of the Smart Parking System is to optimize parking management and reduce congestion by using hardware components like an Arduino Uno, IR sensors, LCD display, and a servo motor. The system detects vehicle presence in real time, displays parking availability, and automates gate control, improving efficiency and enhancing the user experience.

---


## Components
* **Arduino Uno**
* **20×4 Character LCD Display**
* **I2C LCD Adapter Module**
* **Male Header**
* **Female Header**
* **Vibration Sensor Module x 6**
* **Mini Servo Motor SG-90**
* **Female DC Power Jack**
* **5v 2Amp Power Adapter**
* **Wires**
  
---

## Methodology

The Smart Parking System is developed using a hardware-integrated approach** centered around the Arduino Uno as the main controller. Multiple vibration sensor modules (x6)are installed at each parking slot to detect the presence or absence of vehicles. These sensors continuously send signals to the Arduino.

A 20×4 LCD display, connected via the I2C LCD adapter module, shows real-time parking status such as available slots or “Parking Full.” The mini servo motor (SG-90) is used to control the entry gate; it opens only when at least one slot is available and remains closed when the parking area is full.

All components are connected using male and female headers and wires, while a 5V 2A power adapter with a DC power jack supplies power to the system. The Arduino processes sensor inputs, updates the display, and controls the gate mechanism, enabling automated and efficient parking management.

---

## Experiment & Analysis

The system was tested by simulating vehicle entry and exit across the six parking slots using the vibration sensors. Each time a sensor detected a vehicle, the Arduino updated the slot status and reduced the available count displayed on the LCD. Similarly, when a vehicle left, the count increased accordingly.

During testing, the system successfully:

* Displayed accurate real-time parking availability
* Automatically opened the gate when slots were available
* Prevented entry and displayed “Parking Full” when all slots were occupied

The response time of sensors and display updates was observed to be fast and reliable under normal conditions. However, minor challenges such as sensor sensitivity issues and connection stability were noted, which could affect accuracy if not properly calibrated.

Overall, the experiment demonstrated that the system effectively improves parking efficiency, reduces manual effort, and provides a practical low-cost solution for smart parking management.

---


## Team and Credits

* Tanjim Subah Alam: Programming & Simulation
* Chadni Mandal: Hardware integration & Repository setup
* Both: Circuit design and integration
