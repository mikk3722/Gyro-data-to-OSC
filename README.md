# Gyro-data-to-OSC
Transmits Yaw, Roll, Pitch and buttonpin state via WIFI for wireless headtracking

Hardware setup:
 MPU9250 Breakout --------- ESP8266 board (Wemos D1 Mini)
 VDD ---------------------- 3.3V
 VDDI --------------------- 3.3V
 SDA ----------------------- A4
 SCL ----------------------- A5
 GND ---------------------- GND
 BUTTONPIN ---------------- D5
 
 Remember to change your wifi SSID and password in line 48 and 49
 Change the ip adress to the OSC receiver in line 56
 Change the port in line 57 
 
 If problems with MPU9250 connection, try to change "WHO AM I" adress in line 367 from 73 to 71
 
 
