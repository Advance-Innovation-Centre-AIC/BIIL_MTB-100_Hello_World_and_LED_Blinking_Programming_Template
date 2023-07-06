# Lab100-Hello-World-and-LED-Blinking-Programming

This lab will guide you to started with using the PSOC Infineon board  with the Eclipse IDE for ModusToolbox.

## 🔥 Requirements
| Resources                                  | Links                                                                                                  |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------|
| Computer                                   | 💻                                                                                                    |
| ModusToolbox™ software v3.0 or later       | [Link](https://www.infineon.com/modustoolbox)                                                         |
| CY8CKIT-062S2-43012 Infineon Board         | [Link](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/0215501d-b774-4045-8e64-ef49e28d8404) |



## 🚩 Let start
- 👉  Open Eclipes IDE ModusToolbox               
![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/276b5ee3-7752-488c-baa7-3b55f6615b27)                 

- 👉  Select board    
![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/df637b74-1bee-4c0c-9bdc-4b70d7f0cee8)

- 👉  Select Application         
  ![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/3df6fbb2-eea7-4f1b-b09b-36d88f10ad2f)

- 👉  Build Application      
![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/7c230ae2-b6ec-4acc-9713-9cb6325c834d)

- 👉  Launching Program
  - Before launching the program to the board, make sure that you have already connected the board to the computer through USB cable.        
![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/7a6bb6ef-cb63-4613-98a1-42f9617ad724)
  - Launching Program    
    ![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/e95bb346-1205-4e5f-a6d6-20ee60a2cd1d)

- 👉  Serial Terminal Setup 
  - Download and Install Putty
    
    [Download link](https://www.putty.org/)
    ![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/d199b0a6-034b-4259-9662-5bd264aa5cd9)

  - After Install the Putty now let follow the below
    - Open `Device Manager` and check COM Port
      ![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/5ffc6e53-aa99-4be4-a8f6-b945c4ecc21a)
    - Open Putty and Setup as below:
      - Select `Serial`
      - Serial line `COM_`
      - Speed `115200`
      - Click `Open`      
      ![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/aa8f838a-743b-4b5a-bd4f-ab5c2b951afa)

- 👉  Check the Result
  - You will see `Hello World!!!` on the serial terminal.         
   ![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/2eb45911-1df7-4581-9e73-2e79c28364a5)
  - LED Blinking        
    ![image](https://github.com/Advance-Innovation-Centre-AIC/BIIL_MTB-100_Hello_World_and_LED_Blinking_Programming_Template/assets/88732241/e43ee093-c57b-4d65-81a2-e8326e729b74)

### 🎉  Congratulations! You can now complete Lab100 by creating, building, and launching the application program.


## Supported toolchains (make variable 'TOOLCHAIN')

- GNU Arm&reg; embedded compiler v10.3.1 (`GCC_ARM`) - Default value of `TOOLCHAIN`
- Arm&reg; compiler v6.16 (`ARM`)
- IAR C/C++ compiler v9.30.1 (`IAR`)

## Supported kits (make variable 'TARGET')

- [PSoC&trade; 62S2 Wi-Fi Bluetooth&reg; pioneer kit](https://www.infineon.com/CY8CKIT-062S2-43012) (`CY8CKIT-062S2-43012`)
- [PSoC&trade; 62S1 Wi-Fi Bluetooth&reg; pioneer kit](https://www.infineon.com/CYW9P62S1-43438EVB-01) (`CYW9P62S1-43438EVB-01`)
- [PSoC&trade; 62S1 Wi-Fi Bluetooth&reg; pioneer kit](https://www.infineon.com/CYW9P62S1-43012EVB-01) (`CYW9P62S1-43012EVB-01`)
- [PSoC&trade; 62S3 Wi-Fi Bluetooth&reg; prototyping kit](https://www.infineon.com/CY8CPROTO-062S3-4343W) (`CY8CPROTO-062S3-4343W`)


## Related resources
Resources  | Links
-----------|----------------------------------
BDH Shell for LED Blinking and Capsense Slider  | [Github](https://www.infineon.com/AN228571) – Getting started with PSoC&trade; 6 MCU on ModusToolbox&trade; software 
FREERTOS  | [Github](https://www.infineon.com/AN228571) – FREERTOS 
SensiML  | [Github](https://www.infineon.com/AN228571) – SensiML



## Other resources

Infineon provides a wealth of data at www.infineon.com to help you select the right device, and quickly and effectively integrate it into your design.


## Document history

Document title: *BILL_MTB-100* – *Hello World with LED Blinking Template*

 Version | Description of change
 ------- | ---------------------
 2.0.0   | Major update to support ModusToolbox&trade; software v2.2, added support for new kits<br /> This version is not backward compatible with ModusToolbox&trade; software v2.1
 1.1.0   | Updated to support ModusToolbox&trade; software v2.1, added new kits
 1.0.0   | New code example


## Authors:
- *Assoc. Prof. Wiroon Sriborrirux*
- *Sriengchhun Chheang*
- *Sabol Socare*
<br>

<br>

---------------------------------------------------------

© BDH Corporation, 2022-2023
