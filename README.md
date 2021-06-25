# watermeterkit
- LJ18A3-8-Z/BX-5V (https://nl.aliexpress.com/item/32844213899.html)
  - 5v Bruin
  - gnd blauw
  - data zwart (D5)
- WemosD1 (https://nl.aliexpress.com/item/32651747570.html)
  - Alternative ESP32 (https://nl.aliexpress.com/item/1005002571158111.html)
- RGB Led (?)
- HDC1080 (temperature humidity) Component in ESPhome
- Buzzer (Restant van Tagreader (https://github.com/adonno/tagreader) D7?

Mounts
- Sensus 620 https://www.thingiverse.com/thing:4489072
- 

PCB via watermeterkit.nl (NB Closed Source!)

|   |   | Wemos  |   |   |
|---|---|---|---|---|
|   |RST|   |TX |   |
|   |A0|   |RX |   |
|   |D0|   |D1 |HDC1080|
|Pulsemeter|D5|   |D2 |HDC1080|
|   |D6|   |D3 |Led G|
|   |D7|   |D4 |Led R|
|   |D8|   |GND|   |
|   |3v3|   |5V|   |
  

Braindump
- https://www.jbswebcom.nl/knutselen/index.php/watermeter-uitlezen-met-npn-sensor
- https://community.home-assistant.io/t/inductive-npn-sensor-and-raspberry-pi/132487
- https://community.home-assistant.io/t/inductive-water-meter/144990/15
- https://esphome.io/components/sensor/pulse_counter.html
- https://gathering.tweakers.net/forum/list_messages/1596066/16
- https://www.huizebruin.nl/home-assistant/esphome/watermeter-uitlezen-in-home-assistant-met-esphome/
- https://github.com/frenck/home-assistant-config
