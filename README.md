# HCHL Week 1
My project for Week 1 of Hack Club Half Life is to create a Game Boy-style console using a Xiao RP2040 Plus.

**Goal**

The end goal is to have at least 4 games on it: Pong, Atari Breakout, and two custom games. I would also like to make it interactive; it teaches you about itself and its hardware.

**Plan**

I plan to make the PCB in EasyEDA and buy the parts and board from LCSC and JLCPCB. I am going to pick parts that I already have on hand, most of which are through-hole, making soldering easier. I have some knowledge of using EasyEDA, but this will definitely be a learning experience.

For firmware, I plan to start with Arduino IDE and C++, but I will eventually migrate to Visual Studio Code and MicroPython.

**PCB Design**

I had to edit the default footprint for the Xiao RP2040 to account for the extra pins on the Plus, but otherwise it wasn't much of a struggle.

Schematic:
<img width="2362" height="1672" alt="Schematic" src="https://github.com/user-attachments/assets/1aa4f947-e018-4609-a399-9d904dadbef5" />

PCB:

Front
<img width="457" height="630" alt="Screenshot 2026-10-10 214856" src="https://github.com/user-attachments/assets/25218efe-3820-4acc-8cdb-1ac36dbbecdb" />

Back
<img width="462" height="672" alt="Screenshot 2026-10-10 230817" src="https://github.com/user-attachments/assets/2806a810-eb29-4dd2-a4a3-a397f4480b6f" />

**Components:**
- Xiao RP2040 Plus: Controller Board + LiPo Charging
- SSD1306 OLED: Screen
- GY-91: Gyro + Accelerometer + BMP280
- 12x12mm Tactile Push Buttons: 6 Button Inputs
- Piezo buzzer: 8-bit Sound Output
- LEDs: 3 User LEDs
- LiPo Battery: Portability
- Power Switch: Power Saving

<img width="547" height="652" alt="image" src="https://github.com/user-attachments/assets/48471c78-648f-4532-b20b-2109c81f1997" />

_The original plan was to have a joystick, but I changed it because it was too big._


