# LiFi-Communication-using-Arduino
## Table of Contents

  - Theory of Li-Fi Technology
  - Components 
  - Description
  - Circuit diagram
  - Working
  - Layout
  - Post-Layout Simulation

--- 
### Theory of Li-Fi Technology 
- LiFi (Light Fidelity) is a wireless communication technology that uses visible light communication (VLC) to transmit data. VLC is a type of optical wireless communication (OWC) that uses light as the medium for transmitting data. LiFi works by rapidly switching the on/off state of an LED light source. This creates a series of light pulses that can be used to encode data. A photodetector on the receiving end of the transmission can then detect these light pulses and decode the data.

### Components
  - Arduino uno
  - 1Kohm Resister
  - LDR Sensor Module
  - 16*2 LCD Display
  - Half Breadboard
  - M-M Jumper Wire

### Description
- Description of the working of project based on Li-Fi technology using an Arduino Uno, LDR module, LCD display, and a mobile application.
1. Li-Fi Technology: Li-Fi, or Light Fidelity, is a wireless communication technology that uses visible light to transmit data. In this project using a mobile torch to transmit data through light signals, and an LDR (Light Dependent Resistor) module to receive and interpret these light signals.
2. Arduino Uno: The Arduino Uno is a microcontroller board that will serve as the central control unit for your project. It will receive the light signals from the LDR module, process the data, and display it on the LCD display.
3. LDR Module: The LDR module consists of an LDR sensor that detects changes in light intensity. It converts the received light signals into electrical signals that can be processed by the Arduino Uno.
4. LCD Display: The LCD display is used to visually represent the data received through Li-Fi communication can connect the LCD display to the Arduino Uno to show the transmitted messages or any other relevant information.
5. Mobile Application: we will use a mobile application that utilizes the mobile torch functionality. The application will have a feature to input messages, which will be converted into light signals through the torch. By manipulating the torch's light intensity, it will encode binary data or use other modulation techniques to transmit the messages.

### Circuit Diagram
<img width="800" alt="pll_pfd" src="https://github.com/Mrnidhi/LiFi-Communication-using-Arduino/blob/main/Circuit%20diagram.png">

### Working
The working of our project involves the following steps:
- Mobile Application: By Using the mobile application to input a message that we want to transmit. The application will convert the message into light signals using the mobile torch.
- Light Transmission: Point the mobile torch towards the LDR module connected to the Arduino Uno. The varying intensity of the torch's light will correspond to the encoded message.
- LDR Detection: The LDR module will detect the changes in light intensity caused by the torch and convert them into electrical signals.
- Arduino Processing: The Arduino Uno will receive the electrical signals from the LDR module and process them using appropriate algorithms to decode the transmitted data.
- LCD Display: The Arduino Uno will display the decoded message on the connected LCD display, making it visible for users to read.


By following these steps, Li-FI allows for unidirectional communication from the mobile application to the Arduino Uno . The mobile application encodes messages into light signals, while the Arduino Uno receives and decodes these signals, displaying the messages on the LCD display.


