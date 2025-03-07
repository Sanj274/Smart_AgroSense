# Smart_AgroSense

The purpose of Smart AgroSense is to revolutionize agriculture by providing farmers with real-time data on crucial soil parameters through the integration of soil moisture sensor with the powerful 8051 microcontroller. By offering accurate and timely information on soil conditions, the system aims to empower farmers and agriculturalists with actionable insights for informed decision-making, ultimately optimizing water management, fertilizer application, and crop yield while promoting sustainability and resilience in agricultural practices

**COMPONENTS USED** <br>
•	8051 microcontroller kit <br>
•	Soil Moisture sensor <br>
•	LCD display 16x2 <br>
•	ADC0808 <br>
•	Relay (1 channel) <br>
•	Mini Water pump (3 - 6v DC) <br>


**Work Flow**

![image](https://github.com/user-attachments/assets/9011976c-7701-4a2b-85c3-e415c9fef383)

**Block Diagram**

![image](https://github.com/user-attachments/assets/6e4445bc-7cd9-4929-b1f8-d4f62655224e)


**WORKING** <br>

There are 2 working cases:- <br>

- Soil Mositure < 60%  => Low  <br>
Under this condition, the relay which is an electromechanical switch and is also used to control high voltage devices like motors, activates the mini water pump, which conclusively improves the existing natural condition of the soil. <br>

- Soil Mositure > 60%  => High <br>
Under this condition, the measured values are displayed on the LCD interfaced with the 8051 microcontroller. <br>

**SOFTWARE SIMULATION USING PROTEUS**

![image](https://github.com/user-attachments/assets/95b1e6c9-0a23-4784-b209-cdb75d88ca04)

**HARDWARE MODEL**

![image](https://github.com/user-attachments/assets/cf979495-98ae-4dcb-a859-6eeb2ccab4e5)






