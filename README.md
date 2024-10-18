# ESP32Reefcontroller
Aquarium controller based on esp32


Features:

* Auto-top off based on three float switches (low switch, high switch and reservoir switch) and timer functions 

Monitoring:
* 3 Dallas ds18b20 probes for temperature monitoring (Sump, Display tank and room temperature)
* 1 analog pH sensor module (ph-4502c), with calibration option

Control:
* 12 relay control

Webserver:
* Simple webpage displaying sensor readings, relay control buttons and pH calibration option
![image](https://github.com/user-attachments/assets/e1090eb7-587f-4ef8-bafc-cf3fec694de0)

E-mail allert:
* Automatic e-mail alert when ATO reservoir is low
