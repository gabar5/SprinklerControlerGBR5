Irrigation controller. Eight-station irrigation system, controlled manually or by schedule with HomeAssistant.
I'm watering my garden, and instead of buying a standard controller, I decided to create my own project. This allows me to control every system parameter, such as rainfall (counted by an external device), sprinkler runtime, interval time between stations, and enter custom schedules. Manual control is also available, using buttons on the housing that activate the relay. An LED indicates whether the output is actually 24V AC, not just the relay itself.

I used an ESP32 module with 8 relays, 1.1kΩ 2W resistors, an LED, 16mm momentary switches, a DC socket, a USB-C socket, and 24AWG wires.

I've attached the code for ESPHome.



Link to YT showing the structure and operation of the controller: 

https://youtu.be/9w1ausG_DVM
