# Usb_hub

This project was funded by Hackclub's Macondo program. Hack Club is a registered, US-based non-profit. Without their support, this project would not have been possible.

My project is a custom 4-port USB Hub, all designed in EasyEDA.

---

## 3D Views

### Top:

<img width="1310" height="656" alt="image" src="https://github.com/user-attachments/assets/6e18e439-559e-4973-ab78-29143b4d7437" />

### Bottom:

<img width="1188" height="640" alt="image" src="https://github.com/user-attachments/assets/88a98c06-051d-4b2c-9a78-52ca3ad1d73c" />

## Main features

The goal of a USB Hub is to expand USB connections, and this does the job while also:

- being portable
- having an integrated keychain slot for portable, everyday carry
- a rounded corner design so the board feels smooth

## PCB

The PCB has a 2-layer layout, with the top layer being for the signal traces and power, and the bottom being copper-filled and connected to GND.

### Top layer: 

<img width="1124" height="605" alt="image" src="https://github.com/user-attachments/assets/deefbee0-b7c4-43ee-ba03-e3ad5516bfe8" />

### Bottom layer:

<img width="1113" height="607" alt="image" src="https://github.com/user-attachments/assets/8b830bbb-36f1-4fbf-a1d7-f5642b3e7b65" />

There is also a silkscreen, which was used to display the cool graphics!

## Inspiration

Because this was my first custom PCB project, I followed the guide that was provided by Macondo and tailored it to me. For instance, I do not use many peripherals that require a usb-c port, so I reduced the number of usb-c ports and added more usb-a ports. 

I specifically chose to make a USB Hub because it would be VERY useful in my day-to-day life. I use a lot of peripherals and having a USB Hub would centralize all the connections so I can locate them easily. And also, making something on your own is SO MUCH MORE FUN than just buying something!

## BOM

|No.|Quantity|Comment              |Designator              |Footprint                       |Value|Manufacturer Part    |Manufacturer   |Supplier Part|Supplier|JLCPCB Price|LCSC Price|
|---|--------|---------------------|------------------------|--------------------------------|-----|---------------------|---------------|-------------|--------|------------|----------|
|1  |8       |1uF                  |C1,C2,C3,C4,C5,C6,C8,C10|C0603                           |1uF  |                     |               |             |        |            |0.1088    |
|2  |3       |100nF                |C7,C9,C11               |C0603                           |100nF|                     |               |             |        |            |0.1088    |
|3  |4       |5.1K                 |R1,R2,R3,R4             |R0603                           |5.1K |                     |               |             |        |            |0.1088    |
|4  |1       |SL2.1s               |U1                      |SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL|     |SL2.1s               |CoreChips(和芯润德)|C2684433     |LCSC    |0.0375      |          |
|5  |2       |TYPE-C 16PIN 2MD(073)|USB1,USB5               |USB-C-SMD_TYPE-C-16PIN-2MD-073  |     |TYPE-C 16PIN 2MD(073)|SHOU HAN(首韩)   |C2765186     |LCSC    |0.011       |          |
|6  |3       |10.0 QHHTZB6.3       |USB2,USB3,USB4          |USB-A-TH_10.0QHHTZB6.3          |     |10.0 QHHTZB6.3       |SHOU HAN(首韩)   |C668591      |LCSC    |0.0099      |          |
