# DIY-NTP-Clock
Are you tired of having to reset your clocks when you lose power? It may not happen often, but still is annoying. This DIY clock with NTP is for you!

# Basic Description
The goal of this project is to have an easy to build clock for kids or just around your house. The clock will have NTP so it auto sets its time if the power goes out. It will also have some extra options to enable additional creative features including:

 - USB Power supply
 - Onboard "fake" battery to enable powering external zigbee sensors
    - Specifically a Sonoff SNZB-02 (why below)
 - WS2812 controllable leds (millions of colors)
 - Maybe Alarm?
 - Maybe

# Parts List
 - 4 x WS2812 LED 5050 RGB 8x8 LED Matrix for Arduino ( < $2 on AliExpress )
 - TBD Microcontroller
    - Raspberry Pi Pico 2W RP2350 - $7
    - Esp8266
    - ESP32
 - A bunch of boards, wires, copper tape, other... TBD
 - A 3d printed case. (see case design)
 - 5V 3A USB power supply
 - (optional) 3d printed battery
    - https://www.printables.com/model/1047443-cr2430-adapter-to-wire-pigtail
    - https://www.printables.com/model/725567-fake-cr2032-battery 
 - (optional) Sonoff SNZB-02 temperature and humidity sensor, zigbee

# 3D print the case

# 3D print the fake battery 
If you are into home automation, you can add this 3d printed battery and sensor to your clock so that your home automation knows the temp and humidity in all of the rooms in which you put a clock.

# Wire up the electronics
1. wire the displays to the controller
2. Wire up the 

# Program the microcontroller
1. write the code
   - https://www.youtube.com/watch?v=sUzdY9qE3Go 
2. build the code
3. set network config
4. flash the board
5. 

