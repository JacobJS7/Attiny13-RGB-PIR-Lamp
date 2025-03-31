💡 A simple motion-activated RGB lamp using ATtiny13, WS2812B LEDs, and a PIR sensor, with a custom 3D-printed enclosure.  

🎯 Features  
✅ Motion detection via HC-SR501 PIR sensor module
✅ RGB LED control with WS2812B strip  
✅ Cool LED lighting animation 
✅ Button-controlled color selection (12 colors)  
✅ Custom designed 3D-printed enclosure  

🛠️ Required Components  
- 🔹 Microcontroller: ATtiny13
- 🔹 LEDs: WS2812B (Neopixel) – min. 8 LEDs  
- 🔹 PIR Sensor: HC-SR501 (or similar)  
- 🔹 Button: 6mm Push button for color change
- 🔹 ON/OFF Switch: ON/OFF switch (dimensions 13mm x 9mm)
- 🔹 Capacitor: 100µF (for LED stability)  
- 🔹 Power supply: TP4056 Li-Po charging module with USB-C port
- 🔹 Step-Up converter: MT3608 adjustable DC-DC Step-Up voltage converter
- 🔹 Step-Up converter: MT3608 adjustable DC-DC Step-Up voltage converter

🛠️ Circuit Diagram  
(available soon) 

🔧 Installation & Usage  

1️⃣ Flashing the Code to ATtiny13  
Use Arduino as ISP programmer:  
1. Select ATtiny13 in Arduino IDE  
2. Set 9,6MHz internal clock  
3. Upload the code using "Burn Bootloader"  

2️⃣ Wiring Instructions  
-  PIR Sensor OUT → ATtiny13 Pin PB2  
- WS2812B Data IN → ATtiny13 Pin PB0  
- Button → ATtiny13 Pin PB1  

🎨 Color Selection  
Press the button to cycle through 12 predefined colors:  
🔴 Red | 🟢 Green | 🔵 Blue | 🟡 Yellow | 🟣 Purple | 🟦 Cyan  
🟠 Orange | ⚪ White | 💖 Pink | 🟩 Lime | 💛 Gold | 💜 Magenta  

🖨️ 3D-Printed Enclosure  
A custom 3D-printed case is available! STL files can be found in:  
(Soon.)  
