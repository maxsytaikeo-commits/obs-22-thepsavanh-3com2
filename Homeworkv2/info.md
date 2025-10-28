###  Arduino Uno board (Arduino Uno)

- **ອະທິບາຍ:** ບອດຫຼັກ Microcontroller (ATmega328P) ສໍາລັບເຮັດວຽກວົງຈອນ, 14 digital I/O, 6 analog inputs, UART/SPI/I2C, USB-B/USB-C (ຂຶ້ນຢູ່ກັບຮຸ່ນ).
    
- **ວຽກ:** ຮັບ-ສົ່ງຂໍ້ມູນ, ປະມວນຜົນ, ຄວບຄຸມ peripherals.
    
- **ສະເພາະ:** ທີ່ຈໍາເປັນ: Vcc 5V, GND, VIN (7–12V), AREF; bootloader ສະໜອງ Arduino IDE.
    
- **ຕົວຢ່າງ:** ກະທຳ LED ຕົວຢ່າງ (pin 13):
    
    `void setup(){ pinMode(13, OUTPUT); } void loop(){ digitalWrite(13, HIGH); delay(500); digitalWrite(13, LOW); delay(500); }`
    
- **ແນະນໍາ:** ໃຫ້ເຊັກແຜ່ນການຈ່າຍໄຟ, ຢ້ຽມດູສອງຄ່າGround; ຢ້າງໃຊ້ VIN ເມື່ອຕ້ອງໄຟຈາກແຫຼ່ງພາກນອກ.
![m](https://www.theengineeringprojects.com/wp-content/uploads/2018/06/Introduction-to-Arduino-UNO.png)
    

---

### 2. Breadboard (Breadboard)

- **ອະທິບາຍ:** ທົດລອງວົງຈອນໂດຍບໍ່ຕ້ອງບັດ; ມີສະຖານທີ່ເຊື່ອມແຖວ (power rails + rows).
    
- **ວຽກ:** ຕໍ່ອຸປະກອນແລະສັນຍານການທົດລອງ.
    
- **ສະເພາະ:** ບໍ່ເຮັດວຽກກັບໄຟຟ້າສູງ; ຮັບ/ສົ່ງສາຍ jumper.
    
- **ແນະນໍາ:** ກວດສອບການເຊື່ອມຕໍ່ກ່ອນເຮັດພະຍາດ; ໃຊ້ຕົວສອບວົງຈອນກ່ອນບັດຈິງ.
    ![a](https://tse2.mm.bing.net/th/id/OIP.FF6099-at5QaGVSTyRmr2gHaJF?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 3. USB Cable (USB Cable)

- **ອະທິບາຍ:** ສາຍເຊື່ອມສວນ USB ລະຫວ່າງ Arduino ແລະ PC.
    
- **ວຽກ:** ອັບໂຫຼດ Sketch, Serial communication, ຈ່າຍໄຟ 5V.
    
- **ແນະນໍາ:** ໃຊ້ສາຍທີ່ສະຫວັດແລະປອດໄພ; ຖ້າບໍ່ລະຫວ່າງວ່າ USB ເຄື່ອງມັນ ລອງປ່ຽນພໍດ/ສາຍ.
    ![s](https://th.bing.com/th/id/R.5451d9d82576c8b8e0640ab10e107b38?rik=%2fJAdVg6pECtRJg&pid=ImgRaw&r=0)

---

### 4. Jumper wires (Male-to-Male)

- **ອະທິບາຍ:** ສາຍຕໍ່ສັນຍານສັ້ນລະຫວ່າງ pins.
    
- **ວຽກ:** ເຊື່ອມ Breadboard ↔ Breadboard ຫຼື Breadboard ↔ Arduino.
    
- **ແນະນໍາ:** ຮັກສາຄວາມສະອາດຂອງຂາຕໍ່; ເລືອກຄຸນຄ່າສາມາດຮັບກະແສໄດ້.
    ![d](https://genzyug.com/wp-content/uploads/2023/08/Male-to-Male-Jumper-Wires.jpg)

---

### 5. Jumper wires (Male-to-Female)

- **ອະທິບາຍ:** ສາຍໜຶ່ງຂໍ້ມີຂາຊາຍ ແລະ ອີກຂໍ້ມີຂາຍິງ.
    
- **ວຽກ:** ເຊື່ອມ Arduino pins ↔ Module pins (female).
    
- **ແນະນໍາ:** ເຊັກການຕົງຂາກ່ອນເຊື່ອມ.
    ![e](https://tse4.mm.bing.net/th/id/OIP.he3TPR9cJNh28OwbJyPVOQHaHa?rs=1&pid=ImgDetMain&o=7&rm=3)



### 6. Jumper wires (Female-to-Female)

- **ອະທິບາຍ:** ສາຍຕໍ່ module ↔ module.
    
- **ວຽກ:** ເຊື່ອມຕໍ່ຮູບແບບພາຍໃນ Module.
    
- **ແນະນໍາ:** ໃຊ້ສະເພາະເມື່ອມີພວກ sensor/module ທີ່ມີ header.
    ![q](https://tse3.mm.bing.net/th/id/OIP.fn07hqP0VlibYa7YPygF3wHaE7?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 7. 9V Battery Connector (9V Connector)

- **ອະທິບາຍ:** Snap connector ເຊື່ອມຫົວແບັດ 9V.
    
- **ວຽກ:** ຈ່າຍໄຟເມື່ອບໍ່ມີ USB.
    
- **ແນະນໍາ:** ຢ້ຽມໃຊ້ຄວາມລະມັດລະວັງ ແລະກວດຫົວແບັດໃຫ້ຖືກພາຍ.
    ![e](https://www.stewmac.com/globalassets/product-images/m002000/m002600/m002656-9-volt-battery-connector/variant/1222-1-2000.jpg?hash=637704183930000000)

---

### 8. LEDs (Red / Yellow / Blue)

- **ອະທິບາຍ:** Diode ເປັນໄຟສ່ອງ; ຕ່າງສີແຕ່ລະເຄື່ອງມີ Vf ຕ່າງກັນ.
    
- **ວຽກ:** ສະແດງສະຖານະ, ສະແດງ debug.
    
- **ໂຄດຕົວຢ່າງ (LED blink):**
    
    `pinMode(8, OUTPUT); digitalWrite(8, HIGH); delay(200); digitalWrite(8, LOW); delay(200);`
    
- **ແນະນໍາ:** ໃຊ້ Resistor 220Ω ຕໍ່ກັບ LED; ຢ້ຽມຫາ polarity (long leg = Anode).
    ![r](https://cf.shopee.ph/file/9ea702831f6ccfcceafa9fe6bd13b022)

---

### 9. RGB module (RGB LED)

- **ອະທິບາຍ:** RGB LED ມີ 3 channels (R,G,B) ຄຸນສົມບັດ PWM.
    
- **ວຽກ:** ສ້າງສີຕ່າງໆ ຜ່ານການປັບ PWM.
    
- **ໂຄດຕົວຢ່າງ (PWM):**
    
    `analogWrite(Rpin, 255); analogWrite(Gpin, 128); analogWrite(Bpin, 0);`
    
- **ແນະນໍາ:** ກວດດູ common cathode/anode ກ່ອນເຊື່ອມ.
    ![t](https://th.bing.com/th/id/OIP.1yKSnRUoLzgW7mbDIwmTQQHaGW?w=206&h=180&c=7&r=0&o=7&pid=1.7&rm=3)

---

### 10. Resistors (220Ω / 1kΩ / 10kΩ)

- **ອະທິບາຍ:** ຕົວຕ້ານກະແທມກະແສ; ຄ່າທີ່ໃຊ້ພົວພາບຕ່າງກັນ.
    
- **ວຽກ:** ຈໍາກັດກະແສ LED, pull-up/pull-down, voltage divider.
    
- **ແນະນໍາ:** ເລືອກຄ່າໃຫ້ຖືກກັບວຽກການ; ກວດດູຮັບກັນຂະໜາດ power dissipation.
    ![t](https://th.bing.com/th/id/OIP._b2w96o9pj-EQ1kf8Los1gHaHa?w=186&h=185&c=7&r=0&o=7&pid=1.7&rm=3)
  ![o](https://tse2.mm.bing.net/th/id/OIP.1JmlonqLikECPm9eDZCEUQHaHa?rs=1&pid=ImgDetMain&o=7&rm=3)

### 11. Push Buttons (x4 with Lids)

- **ອະທິບາຍ:** ປຸ່ມກົດສຳລັບ Input ທົ່ວໄປ.
    
- **ວຽກ:** ສົ່ງ Signal HIGH/LOW ເມື່ອກົດ.
    
- **ໂຄດຕົວຢ່າງ:**
    
    `pinMode(btn, INPUT_PULLUP); if (digitalRead(btn)==LOW) { /* pressed */ }`
    
- **ແນະນໍາ:** ໃຊ້ INPUT_PULLUP ເພື່ອຫຼຸ້ນ bounce; ໃຊ້ debounce code.
    ![p](https://tse3.mm.bing.net/th/id/OIP.9JB3e2odOppz3AULii4ergHaHa?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 12. Potentiometer 5kΩ 

- **ອະທິບາຍ:** ຕົວປັບຄ່າດ້ວຍการหมุน; ອອກຄ່າ analog.
    
- **ວຽກ:** ປັບความสว่าง, volume, threshold, servo angle mapping.
    
- **ໂຄດຕົວຢ່າງ:**
    
    `int v = analogRead(A0); float pct = v/1023.0;`
    
- **ແນະນໍາ:** ເຊື່ອມกลาง→GND, ขาเผื่อ→5V, ขากลาง→Analog.
    ![i](https://3.bp.blogspot.com/-7pcmbMVljr8/XNV3lTwW0NI/AAAAAAAAB2A/3j9EWjEKIhkM-EN5eRJvIN2s6xnrr3bvACLcBGAs/s1600/Potentiometer%2Bterminals.png)

---

### 13. Active Buzzer

- **ອະທິບາຍ:** ມີຕອນໄຟຟ້າໃນໂຕ; ພຽງຕໍ່ไฟແລ້ວສຽງ.
    
- **ວຽກ:** alarm/beep simple.
    
- **ໂຄດຕົວຢ່າງ:** `digitalWrite(buzz, HIGH); delay(200); digitalWrite(buzz, LOW);`
    
- **ແນະນໍາ:** ບໍ່ຕ້ອງ tone(); ໃຊ້ແຊ່ນຄວາມຕ້ອງການ current.
![y](https://circuitdigest.com/sites/default/files/inlineimages/u5/active-buzzer-and-passive-buzzer-parts.jpg)

---

### 14. Passive Buzzer

- **ອະທິບາຍ:** ຕ້ອງໃຊ້ PWM/Tone ເພື່ອສ້າງຕົນຖະຫນົນສຽງ.
    
- **ວຽກ:** ດັ່ງສຽງ melody ຫຼື tone.
    
- **ໂຄດຕົວຢ່າງ:** `tone(pin, 1000, 500);`
    
- **ແນະນໍາ:** ບໍ່ໃຫ້ບອດໄດ້ຮັບກະແສເກີນ.
    ![yu](https://circuitdigest.com/sites/default/files/inlineimages/u5/active-buzzer-and-passive-buzzer-parts.jpg)

---

### 15. 16x2 LCD display (16x2 LCD)

- **ອະທິບາຍ:** Character LCD 2 lines × 16 chars (HD44780 compatible).
    
- **ວຽກ:** ສະແດງຂໍ້ຄວາມ textual, menu.
    
- **ສະເພາະ:** ຕ້ອງ 6-8 data pins ຫຼື I2C backpack ສໍາລັບ SDA/SCL.
    
- **ໂຄດຕົວຢ່າງ (LiquidCrystal):**
    
    `lcd.begin(16,2); lcd.print("Hello World!");`
    
- **ແນະນໍາ:** ໃຊ້ contrast pot; ຖ້າຫາກໃຊ້ I2C ຈຳນ່ອຍ pin.
    ![hu](https://www.theengineeringprojects.com/wp-content/uploads/2019/11/Introduction-to-16x2-LCD-Module.jpg)

---

### 16. I2C Serial Adapter board module (I2C Adapter)

- **ອະທິບາຍ:** Backpack ສໍາລັບ HD44780 LCD ເພີ່ມ SDA/SCL.
    
- **ວຽກ:** ຫຼຸດ pin usage (only SDA/SCL + Vcc + GND).
    
- **ແນະນໍາ:** ຕັ້ງສີສະເພາະ address (เช่น 0x27) ເມື່ອใช้ library.
    ![po](https://www.techtonions.com/wp-content/uploads/2021/09/I2C-LCD-Module-Pinout-1.webp)

---

### 17. 7-segment display (Common Cathode)

- **ອະທິບາຍ:** 7 segments + DP; common cathode ຫຼື anode.
    
- **ວຽກ:** ສະແດງຕົວເລກ 0–9; ຄວບຄຸມດ້ວຍ segments (a-g).
    
- **ແນະນໍາ:** ໃຊ້ resistors per segment; ພິຈາລະນາ multiplex ສຳລັບ multiple digits.
    ![uo](https://3.bp.blogspot.com/-3WaxW8Blf6M/WxBtNPdItDI/AAAAAAAACzI/FU_8AqUpJnwL-f5zeBXqOEeXv5M5Nr8JQCLcBGAs/s640/7_segment_display_pin_outs.png)

---

### 18. 4-Digit 7-Segment Display

- **ອະທິບາຍ:** 4 digits, ມັກມາພ່ອມ colon.
    
- **ວຽກ:** ສະແດງເວລາ/ເນື້ອຫາ 4-digit.
    
- **ແນະນໍາ:** ມັກຈໍາເປັນການ multiplex ຫຼື driver (TM1637).
    ![pp](https://th.bing.com/th/id/R.164b12e6fdf2d65e8b631da26cd22a19?rik=eTu2CwLOn84P4w&pid=ImgRaw&r=0)

---

### 19. 8×8 Dot Matrix display

- **ອະທິບາຍ:** Matrix of 64 LEDs; ສາມາດແສດສັນຍານ/character.
    
- **ວຽກ:** ສະແດງ icon, text (with driver MAX7219).
    
- **ແນະນໍາ:** ໃຊ້ driver ເພື່ອງ່າຍ; ການ multiplexing ພິສູດ.
![oo](https://tse1.mm.bing.net/th/id/OIP.jBl6niqr12Hp4XC9-C6ePgHaFR?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 20. Temperature & Humidity Sensor (DHT11)

- **ອະທິບາຍ:** ອ່ານອຸນ/ຄວາມຊື້ນ (accuracy low, cheap).
    
- **ວຽກ:** ຕິດຕາມອາກາດ, HVAC projects.
    
- **ໂຄດຕົວຢ່າງ (DHT library):**
    
    `DHT dht(pin, DHT11); float t = dht.readTemperature(); float h = dht.readHumidity();`
    
- **ແນະນໍາ:** ບໍ່ມີ sampling ຫຼາຍ (1Hz); ຖ້າເຫຼືອ error ລອງໄຟ້ pull-up.
    ![qq](https://adiy.in/wp-content/uploads/2022/04/A133736_Humidity-and-Temperature-Sensor-DHT11_Pin-diagram-1024x1024.jpg)

---

### 21. LM35 Temperature Sensor (LM35)

- **ອະທິບາຍ:** Analog temperature sensor (10mV/°C).
    
- **ວຽກ:** ເປັນ analog input ປະມານໃຊ້ວັດ temp.
    
- **ໂຄດຕົວຢ່າງ:**
    
    `int v = analogRead(A1); float tempC = v * (5.0/1023.0) * 100.0;`
    
- **ແນະນໍາ:** ຕ້ອງໃຊ້ power stable; ສົມດຸນອ່ານ.
    ![mm](https://tse4.mm.bing.net/th/id/OIP._GmmzjXrUJBcw7XyIZovYgAAAA?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 22. Tilt sensor (x2)

- **ອະທິບາຍ:** Mechanical tilt switch (digital).
    
- **ວຽກ:** ກວດເຄື່ອນໄຫວ/tilt detection.
    
- **ໂຄດຕົວຢ່າງ:** `if (digitalRead(tiltPin)==LOW) { /* tilted */ }`
    
- **ແນະນໍາ:** ວຽກຢ່າງ contact bounce → debounce.
    ![ww](https://1.bp.blogspot.com/-i4zcBs0iehg/YCz89NnOIAI/AAAAAAAAAug/yzTEnymZb9QW-rBcBWUGqgF8gHnbFISNACLcBGAsYHQ/w1200-h630-p-k-no-nu/20210217_162431.png)

---

### 23. Photoresistor (LDR x3)

- **ອະທິບາຍ:** ຄ່າຄວາມຕ້ອງການແສງປ່ຽນຕາມສຸດ.
    
- **ວຽກ:** ວັດແສງແລະຄວບຄຸມແສງອາດຕ້ອງ.
    
- **ໂຄດຕົວຢ່າງ:** `int lux = analogRead(A2);`
    
- **ແນະນໍາ:** ຈັດ voltage divider ຕ້ອງຖືກ.
    ![pop](https://engineeringlearn.com/wp-content/uploads/2021/12/LDR.jpg)

---

### 24. PIR sensor (PIR Motion)

- **ອະທິບາຍ:** Passive Infrared sensor ສຳລັບເຝົ້າການເຄື່ອນໄຫວ.
    
- **ວຽກ:** ມີ sensor Pyroelectric ທີ່ຈັບການປ່ຽນແປງອິນຟາເຣດ ແລ້ວສົ່ງສັນຍານ HIGH ໃຫ້ Arduino.
    
- **ໂຄດຕົວຢ່າງ:** `if (digitalRead(pirPin)) { /* motion */ }`
    
- **ແນະນໍາ:** ມີ warm-up time ≈ 30s; ຈັກຄ່າ sensitivity.
    ![er](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEja_meqpFw0_tZ8jTWsSLqwJBQ7V-q2pcrPM0IzZ-xzh19HeFm7FobMzroKrmOLQM5jSSob_rp020YGe7CksAe_QpgbFoCMILpLaedlDXolHFvnSHsDAKOECTEx7eMOTYyjUj6JyLiiFLDn9tO_WqdK_kAWVobGHdlxogDhY1iZcn9n7HpaFW0_XBjxqQ3B/s826/401.jpg)

---

### 25. Ultrasonic module (HC-SR04)

- **ອະທິບາຍ:** ສົ່ງແລະຮັບພູມສຽງເພື່ອຄຳນວນລະດັບ.
    
- **ວຽກ:** distance measurement (cm).
    
- **ໂຄດຕົວຢ່າງ:** send pulse on TRIG, measure ECHO duration → distance.
    
- **ແນະນໍາ:** ມີ blind range ≈ 2cm; ຄ່າ speed of sound ຂຶ້ນຢູ່ກັບອາກາດ.
    ![wer](https://tse1.mm.bing.net/th/id/OIP.38O8k_eaB_-IEBDNM-AkogHaHa?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 26. Sound sensor

- **ອະທິບາຍ:** Microphone module ທີ່ແປໄຟ້ analog/digital based on amplitude.
    
- **ວຽກ:** ກວດສຽງ/level detection.
    
- **ໂຄດຕົວຢ່າງ:** `if (analogRead(soundPin)>threshold) { /* loud */ }`
    
- **ແນະນໍາ:** ເລືອກ threshold ພໍດີ; ອາດມີ noise.
    ![fg](https://circuitdigest.com/sites/default/files/inlineimages/u4/Sound-Sensor-Module-Parts.jpg)

---

### 27. Water sensor

- **ອະທິບາຍ:** Probe ຫรือ module ກວດການນ້ຳ/conductivity.
    
- **ວຽກ:** leak detection, level detection.
    
- **ແນະນໍາ:** ຢຸດການອອກລະບົບໄຟຟ້າ; ປ້ອງກັນການກັກຂອງນ້ຳ.
    ![ppp](https://circuitdigest.com/sites/default/files/inlineimages/u4/Water-Level-Sensor-Pinout.jpg)

---

### 28. Flame sensor

- **ອະທິບາຍ:** IR-sensitive sensor ທີ່ຈຶ່ງຮັບແສງພະລາ (flame).
    
- **ວຽກ:** fire detection, safety alarm.
    
- **ແນະນໍາ:** ຕ້ອງເສັ້ນແສງຄອງ; ລອງທົດໃນເງົາ.
    ![io](https://circuitdigest.com/sites/default/files/inlineimages/u4/Flame-Sensor-Module-Parts.jpg)

---

### 29. RFID module (RFID Reader)

- **ອະທິບາຍ:** Module (e.g., RC522) ອ່ານบัตร/แท็ก 13.56MHz.
    
- **ວຽກ:** access control, ID reading.
    
- **ໂຄດຕົວຢ່າງ:** ใช้ MFRC522 library → read uid.
    
- **ແນະນໍາ:** ກວດ SPI wiring; ກວດ supply 3.3V (not 5V).
    ![ppp](https://circuitdigest.com/sites/default/files/inlineimages/u4/RFID-Reader-Module-Parts.jpg)

---

### 30. RFID tag (RFID Card)

- **ອະທິບາຍ:** บัตรหรือแท็กที่มี chip.
    
- **ວຽກ:** ถูกอ่านโดย RFID module เพื่อตรวจสอบสิทธิ์.
    
- **ແນະນໍາ:** ຢ່າງຫຼາຍຮຸ່ນ ກວດວ່າກັບ reader ໄດ້.
    ![uio](https://tritonstore.co.nz/wp-content/uploads/components-of-an-rfid-tag.jpg)

---

### 31. Infrared receiver (IR Receiver)

- **ອະທິບາຍ:** ຮັບສັນຍານ IR (TSOP1738 etc.).
    
- **ວຽກ:** ຮັບເຄື່ອນຄ່າຈາກ remote.
    
- **ໂຄດຕົວຢ່າງ:** ใช้ IRremote library → decode.
    
- **ແນະນໍາ:** ວາງແນວກາງ ແລະຫຼຸດ noise.
    ![qwo](https://th.bing.com/th/id/R.c7b0ecae4ea1566f8abef52254cf9d7e?rik=Okh1OIzraf0oYw&riu=http%3a%2f%2fwww.sunfounder.com%2fcdn%2fshop%2fproducts%2fInfrared-ReceiverModule02.jpg%3fv%3d1609237663&ehk=F6Nr8xsBJo3Uaw7HAC3IvTS0ykCl1Ij%2bbzTShwLuZmU%3d&risl=&pid=ImgRaw&r=0)

---

### 32. Infrared remote control (IR Remote)

- **ອະທິບາຍ:** รีโมตส่งสัญญาณ IR (RC5/NEC).
    
- **ວຽກ:** ควบคุมระยะไกลของโครงการ.
    
- **ແນະນໍາ:** ກວດຮູບແບບ protocol ຂອງ remote.
    ![mko](https://th.bing.com/th/id/OIP.TeO8xs_mAXEgnI0oPkwMyQHaHa?o=7rm=3&rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 33. Joystick module

- **ອະທິບາຍ:** Analog joystick (X/Y) + button.
    
- **ວຽກ:** input control, robot steering, menu navigation.
    
- **ໂຄດຕົວຢ່າງ:** `int x=analogRead(A0); int y=analogRead(A1);`
    
- **ແນະນໍາ:** ມາດເລີກ center calibration.
    ![mkk](https://tse3.mm.bing.net/th/id/OIP.UxXkZnhC7aClDeoJ09qKxgHaFC?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 34. 4×4 Matrix Keyboard Module (4×4 Keypad)

- **ອະທິບາຍ:** 16 keys arranged rows×cols.
    
- **ວຽກ:** input multiple keys, password entry.
    
- **ໂຄດຕົວຢ່າງ:** ใช้ Keypad library → `char key = keypad.getKey();`
    
- **ແນະນໍາ:** ການ wiring ຕ້ອງຖືກ.
    ![weq](https://tse4.mm.bing.net/th/id/OIP.VfY5gf4bjWq-ahBZF15bSQHaHa?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 35. Relay module

- **ອະທິບາຍ:** Electromechanical (or solid-state) relay to switch high voltage/current loads.
    
- **ວຽກ:** control mains appliances, motors.
    
- **ແນະນໍາ:** ຢ້ຽມລະມັດລະວັງການເຊື່ອມຫົວມາຍ້ອນ; ໃຊ້ flyback diode ເມື່ອສັດ.
    ![zz](https://tse2.mm.bing.net/th/id/OIP.Tfj4aXCNB-WuAWWmhPs9DAHaEE?rs=1&pid=ImgDetMain&o=7&rm=3)
---

### 36. Servo motor

- **ອະທິບາຍ:** Motor with position control (0–180°).
    
- **ວຽກ:** robotics, pan/tilt.
    
- **ໂຄດຕົວຢ່າງ:** `servo.write(90);`
    
- **ແນະນໍາ:** ໃຊ້ external power ຖ້າເລັກເກີນ; ມີ current peaks.
    ![pppp](https://i.pinimg.com/736x/d8/87/f1/d887f169ff0a2af2cc8e525867d113f7.jpg)

---

### 37. Stepper motor

- **ອະທິບາຍ:** Motor that moves in discrete steps.
    
- **ວຽກ:** precise positioning, CNC, camera slider.
    
- **ແນະນໍາ:** ໃຊ້ driver (A4988, DRV8825) ແທນ.
    ![zzer](https://th.bing.com/th/id/R.3c0818a8f18b470332afb6f9932147ee?rik=AhsEXqJ24HKefQ&riu=http%3a%2f%2flearnmech.com%2fwp-content%2fuploads%2f2018%2f11%2fStepper-Motor-Construction.jpg&ehk=5A5t2JkNbvwZ5rFjNgPiZ1MVtWuL8v18vk%2b24FZfy6M%3d&risl=&pid=ImgRaw&r=0)

---

### 38. Stepper motor driver board (A4988 / DRV8825)

- **ອະທິບາຍ:** Driver to control stepper current, microstepping.
    
- **ວຽກ:** ຈັດການ step pulses & direction.
    
- **ແນະນໍາ:** ຕັ້ງ current limit ເກັບຄ່າ; ໃຊ້ heatsink.
  ![qqa](https://tse2.mm.bing.net/th/id/OIP.GzWZOjGx_fYcsml4UOYoaAHaHa?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 39. Real-time Clock Module DS1302 (RTC DS1302)

- **ອະທິບາຍ:** RTC module with backup battery.
    
- **ວຽກ:** ຕິດຕາມເວລາ/ວັນທີໂດຍບໍ່ສູນ.
    
- **ໂຄດຕົວຢ່າງ:** ใช้ RTClib → `rtc.now()`
    
- **ແນະນໍາ:** ກວດ battery backup.
    ![bu](https://tse3.mm.bing.net/th/id/OIP.3Je1AiFhh2R3dhHKOTzD6QHaHb?rs=1&pid=ImgDetMain&o=7&rm=3)

---

### 40. 74HC595 Chip (Shift Register)

- **ອະທິບາຍ:** Serial-in Parallel-out shift register (8-bit) to expand outputs.
    
- **ວຽກ:** ຄວບຄຸມ LEDs, 7-segments ຈໍນອກກວ່າ pins.
    
- **ໂຄດຕົວຢ່າງ:** `shiftOut(dataPin, clockPin, MSBFIRST, byteVal);`
    
- **ແນະນໍາ:** Daisy-chain ໄດ້ຫຼາຍຕົວ
   ![mued](https://tse2.mm.bing.net/th/id/OIP.Nm7yin7JvkvOtsmAVy5rZQHaHa?rs=1&pid=ImgDetMain&o=7&rm=3)
