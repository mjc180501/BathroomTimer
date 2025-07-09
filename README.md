# BathroomTimer

This is a bathroom timer that attaches to the bathroom door via sticky velcro pieces that uses a MPU-6050 to test acceleration and determine if the door has been opened or closed and recognizes whether or not somebody is inside. When somebody enters the bathroom, they can choose 5, 15, 30, 45 minutes. The LED blinks to signal when their time is up. 

I made this because my sister always spends an ungodly amount of time in the bathroom even though she is supposed to be limited to 45 minutes. Hopefully with this device she will be able to regulate her bathroom time. 

Schematic:

<img width="451" alt="Screenshot 2025-07-08 at 9 16 59 PM" src="https://github.com/user-attachments/assets/bbe58f99-a35f-40da-8c90-46f2d6a416d6" />


Pictures:

<img width="513" alt="Screenshot 2025-07-08 at 8 36 07 PM" src="https://github.com/user-attachments/assets/6c45e756-880e-48ba-975e-64e007ac46d2" />

BOM:

| Name               | Description                                    | Link                                                                                                                  | Cost   |
| ------------------ | ---------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ------ |
| **Arduino Nano**   | Microcontroller for logic and control          | [Alibaba](https://www.alibaba.com/pla/good-quality-Arduino-Nano-V30-CH340G_1600942840347.html)                        | \$2.20 |
| **LCD - 016N002L** | Display for timer countdown                    | [Alibaba](https://www.alibaba.com/product-detail/p_62532698703.html)                                                  | \$0.78 |
| **MPU-6050**       | Accelerometer that reports movement            | [Alibaba](https://www.alibaba.com/product-detail/GY-521-MPU-6050-MPU6050-Module_1600307178499.html)                   | \$1.08 |
| **9V Battery**     | Powers the entire board                        | [DigiKey](https://www.digikey.com/en/products/detail/duracell-industrial-operations-inc/9V/21259959)                  | \$4.46 |
| **LED**            | Blinks to indicate when time is up             | Already have                                                                                                          | N/A    |
| **Potentiometer**  | Used to regulate contrast of the LCD           | [Alibaba](https://www.alibaba.com/product-detail/High-Quality-16mm-WH148-Rotary-Mono_1601201209855.html)              | \$0.11 |
| **4× Buttons**     | Indicate how many minutes to set the timer for | [DigiKey](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices-/TS02-66-60-BK-160-LCR-D/15634268) | \$0.40 |
