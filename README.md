# Resolution-Hardware-Week-Four

<img width="3000" height="750" alt="Counterboard" src="https://github.com/user-attachments/assets/d4bca9f7-6ce5-444d-8ac0-051cbebd592d" />



This week I made a counter using a 4017. There's 10 LED's and 2 buttons. When you press one button the next LED in the row lights up, the other button turns them all off. I made this project because the CD4017B really interests me and I wanted to learn all about it. Although the project is quite simple I did a ton of research on the IC and would confidently say I could make something similar without even using the datasheet. The schematic took me quite a while as I was playing around with ideas while also making sure it was clean enough for someone else to understand. Not untill after kicad crashed twice and I lost all my progress I was finally ready to move onto my PCB. The PCB is just a rectangle to keep the PCB kit vibe that I really enjoy when making them and a benefit of the rectangle was that there's no thinner areas to run out of room for routing.

Here's my schematic!

<img width="1045" height="721" alt="WeekFourSCHSS" src="https://github.com/user-attachments/assets/247c9a17-d7d0-4ecb-ab83-693011269dfe" />


Here's a 2D render of my PCB!

<img width="737" height="719" alt="weekFourPCBSS" src="https://github.com/user-attachments/assets/f8b3917a-b110-4b15-a8bd-534e3f6a7670" />


Here's a 3D render of my PCB!

<img width="488" height="470" alt="WeekFOurPCB3DSS" src="https://github.com/user-attachments/assets/b9cfcb3d-655e-49f3-ab78-a40020875440" />


Here's a video of me making it!

https://lapse.hackclub.com/timelapse/hCRQ5qOuCu0Q


## Cool features!
- Only one LED stays on at a time
- when you get to 10 it resets back to 1
- Reset button turns it all off
- USB A power!

## BOM!
 Reference | Qty | Value | Footprint | Datasheet |
|-----------|-----|-------|-----------|-----------|
| C1, C2 | 2 | 0.1µF | Capacitor_THT:C_Disc_D8.0mm_W5.0mm_P5.00mm | — |
| D1–D10 | 10 | LED | LED_THT:LED_D5.0mm | — |
| J1 | 1 | USB_A | Connector_USB:USB_A_Molex_67643_Horizontal | — |
| R1–R10 | 10 | 470Ω | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | — |
| R11 | 1 | 1kΩ | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | — |
| R12 | 1 | 10kΩ | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | — |
| SW1, SW2 | 2 | SW_Push | Button_Switch_THT:SW_PUSH-12mm | — |
| U1 | 1 | 4017 | Package_DIP:DIP-16_W7.62mm | [Datasheet](http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf) |


To see all my resolution hardware projects head over to https://github.com/PL00T00/Resolution-hardware-projects
