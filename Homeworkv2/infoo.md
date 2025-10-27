1. **Arduino Uno board — ບອດ Arduino Uno**  
    ອະທິບາຍ: ບອດ MCU ທົ່ວໄປ (ATmega328P).  
    ໜ້າທີ່: ຄວບຄຸມ ແລະ ປະມວນຜົນ.  
    ຕົວຢ່າງໂຄດ: ການຄວບ LED ໄວ້ໃນ pin 13
    
    `pinMode(13, OUTPUT); digitalWrite(13, HIGH); delay(500); digitalWrite(13, LOW);`
    
2. **Breadboard — ແຜ່ນ Breadboard**  
    ອະທິບາຍ: ຕອນທົດລອງວົງຈອນບໍ່ຕ້ອງບັດ.  
    ໜ້າທີ່: ຕໍ່ສາຍແລະຕວງງານໄວ້ເພື່ອທົດລອງ.  
    ຕົວຢ່າງ: ຕໍ່ LED + resistor ເຂົ້າ Arduino (ບໍ່ຈໍາເປັນໂຄດ).
    
3. **USB Cable — ສາຍ USB**  
    ອະທິບາຍ: ສາຍເຊື່ອມບອດ ກັບຄອມ.  
    ໜ້າທີ່: ອັບໂຫລດໂຄດ ແລະ ຈ່າຍໄຟ.  
    ຕົວຢ່າງ: ຊ່ວຍໃຫ້ upload sketch.
    
4. **Jumper wires (male-to-male) — ສາຍ Jumper (M-M)**  
    ອະທິບາຍ: ສາຍເຊື່ອມລະຫວ່າງ pins.  
    ໜ້າທີ່: ເຊື່ອມ Breadboard ແລະ Arduino.
    
5. **Jumper wires (male-to-female) — ສາຍ Jumper (M-F)**  
    ອະທິບາຍ: ມີຂອບຊາຍແບບລຳດັບຕ່າງ.  
    ໜ້າທີ່: ເຊື່ອມ Module ກັບ Arduino.
    
6. **Jumper wires (female-to-female) — ສາຍ Jumper (F-F)**  
    ອະທິບາຍ: ສາຍເຊື່ອມລະຫວ່າງ module.  
    ໜ້າທີ່: ເຊື່ອມ Module ກັນ.
    
7. **9V Battery Connector — ຕໍ່ແຫຼ່ງ 9V**  
    ອະທິບາຍ: ການເຊື່ອມແຫຼ່ງພະລັງ.  
    ໜ້າທີ່: ຈ່າຍໄຟເມື່ອບໍ່ມີ USB.
    
8. **LEDs (Red, Yellow, Blue, RGB) — ໄຟ LED ສີຕ່າງໆ**  
    ອະທິບາຍ: ດ້ວຍຫຼາຍສີ.  
    ໜ້າທີ່: ສະແດງສະຫວ່າງ.
    
    `digitalWrite(9, HIGH); // ຕັ້ງຕົວຢ່າງ PWM analogWrite(9, 128);`
    
9. **RGB module — ໂມດູນ RGB**  
    ອະທິບາຍ: ມີ LED 3 ສີ (R,G,B).  
    ໜ້າທີ່: ປະສົມສີໄດ້.
    
    `analogWrite(Rpin, 255); analogWrite(Gpin, 0); analogWrite(Bpin, 128);`
    
10. **Resistors (220Ω, 1kΩ, 10kΩ) — ຕໍ່ຕ้าน**  
    ອະທິບາຍ: ຈຳແກ່ກະແສຟ້າ.  
    ໜ້າທີ່: ປ້ອງກັນ LED ຫຼື ອຸປະກອນ.
    
11. **Push Buttons (x4 with Lids) — ປຸ່ມກົດ**  
    ອະທິບາຍ: ຄຸມການປ່ຽນສະຖານະ.  
    ໜ້າທີ່: ປ່ຽນ Input.
    
    `if (digitalRead(buttonPin)==HIGH) { digitalWrite(13, HIGH); }`
    
12. **Potentiometer (5kΩ) — ຕົວປັບ Pot (5kΩ)**  
    ອະທິບາຍ: ຕົວເລືອກຄ່າໄຟຟ້າ (analog).  
    ໜ້າທີ່: ກວດແລະປັບຄ່າ.
    
    `int val = analogRead(A0);`
    
13. **Active Buzzer — ບິຊເຊີ (Active)**  
    ອະທິບາຍ: ຫຼັງມີວົງຈອນສ້າງສຽງ.  
    ໜ້າທີ່: ສະແດງການແຈ້ງ.
    
    `digitalWrite(buzzPin, HIGH);`
    
14. **Passive Buzzer — ບິຊເຊີ (Passive)**  
    ອະທິບາຍ: ຕ້ອງໃຊ້ PWM ສັນຍານ.
    
    `tone(buzzPin, 1000); // 1 kHz noTone(buzzPin);`
    
15. **16x2 LCD display — ຈໍ LCD 16x2**  
    ອະທິບາຍ: ສະແດງຂໍ້ຄວາມ.  
    ໜ້າທີ່: ສະແດງ Text.
    
    `lcd.print("Hello World!");`
    
16. **I2C Serial Adapter board module — ອັດເຕີ I2C**  
    ອະທິບາຍ: ລົດຈໍາເປັນຂອງ pin ສຳລັບ LCD.  
    ໜ້າທີ່: ຊ່ວຍເຊື່ອມໄດ້ໂດຍ SDA/SCL.
    
17. **7-segment display (Common Cathode +) — ຈໍ 7-seg**  
    ອະທິບາຍ: ສະແດງໂຕເລກ.  
    ໜ້າທີ່: ສະແດງ 0–9.
    
    `// shift out or direct pin write per segment`
    
18. **4-Digit 7-Segment Display — 4-digit 7-seg**  
    ອະທິບາຍ: ສະແດງຕົວເລກ 4 ຕົວ.  
    ໜ້າທີ່: ວັນເວລາ/ນີ້ມີດີເທິງ.
    
19. **8x8 Dot Matrix display — ຈໍ Matrix 8x8**  
    ອະທິບາຍ: ສະແດງຕົວອັກສອນ/ໄກຟອນດ້ວຍ pixel.  
    ໜ້າທີ່: ສະແດງສັນຍານຫຼືຂໍ້ຄວາມຍ່ອຍ.
    
20. **Temperature and humidity sensor (DHT11) — DHT11**  
    ອະທິບາຍ: ອ່ານອຸນຫະພູມ ແລະ ຄວາມຊື້ນ.  
    ໜ້າທີ່: ຕິດຕາມສະພາບສະເພາະສິ່ງລ່ວງ.
    
    `DHT.read(); float t = DHT.readTemperature(); float h = DHT.readHumidity();`
    
21. **LM35 Temperature Sensor — LM35**  
    ອະທິບາຍ: ອ່ານຄ່າອຸນຫະພູມແບບ analog.
    
    `int v = analogRead(A1); float tempC = v * (5.0 / 1023.0) * 100.0;`
    
22. **Tilt sensor (x2) — ເຊີເນອຣ Tilt**  
    ອະທິບາຍ: ກວດການເຄື່ອນໄຫວ/ການ倾斜.
    
    `if (digitalRead(tiltPin)==LOW) { /* tilt detected */ }`
    
23. **Photoresistor (LDRs x3) — LDR (Photoresistor)**  
    ອະທິບາຍ: ປ່ຽນຄ່າລະດັບຕາມແສງ.
    
    `int lux = analogRead(A2);`
    
24. **PIR sensor — PIR (motion)**  
    ອະທິບາຍ: ກວດການເຄື່ອນໄຫວຂອງມະນຸດ.
    
    `if (digitalRead(pirPin)==HIGH) { /* motion */ }`
    
25. **Ultrasonic module — HC-SR04 (Ultrasonic)**  
    ອະທິບາຍ: ວັດລະດັບຫ່າງດ້ວຍໄວ້ສຽງ.
    
    `// send pulse, measure echo duration -> distance`
    
26. **Sound sensor — Sound detector**  
    ອະທິບາຍ: ກວດສຽງ/ດັດແປງເປັນ signal.
    
    `if (analogRead(soundPin) > threshold) { /* loud */ }`
    
27. **Water sensor — Water level/conductivity**  
    ອະທິບາຍ: ກວດການມີນ້ຳ.
    
    `if (digitalRead(waterPin)==HIGH) { /* water detected */ }`
    
28. **Flame sensor — Flame detector**  
    ອະທິບາຍ: ກວດແສງໄຟ/ເພີ່ງ.
    
    `if (analogRead(flamePin) < flameThreshold) { /* flame */ }`
    
29. **RFID module — RFID reader**  
    ອະທິບາຍ: ອ່ານບັດ RFID ເພື່ອຈັດການແຕ່ງ.
    
    `if (RFID.read()) { Serial.println(RFID.uid); }`
    
30. **RFID tag — RFID card/tag**  
    ອະທິບາຍ: ບັດ/ແທກເພື່ອຖືກອ່ານໂດຍ RFID module.
    
31. **Infrared receiver — IR receiver**  
    ອະທິບາຍ: ຮັບຄ່າຈາກ remote control.
    
    `if (irReceived()) { /* parse code */ }`
    
32. **Infrared remote control — IR remote**  
    ອະທິບາຍ: ສົ່ງຄ່າຄຳສັ່ງດ້ວຍ IR.
    
33. **Joystick module — Joystick**  
    ອະທິບາຍ: ຄວບຄຸມ 2 แกน (X,Y) + button.
    
    `int x = analogRead(A0); int y = analogRead(A1);`
    
34. **4x4 Matrix Keyboard Module — 4x4 keypad**  
    ອະທິບາຍ: ຮັບ input ຈາກປຸ່ມຫຼາຍ.
    
    `char key = keypad.getKey();`
    
35. **Relay module — Relay**  
    ອະທິບາຍ: ຄວບຄຸມການເປີດ-ປິດໄຟຟ້າພັກໃຫ້ສູງ.
    
    `digitalWrite(relayPin, HIGH); // on`
    
36. **Servo motor — Servo**  
    ອະທິບາຍ: ມີການຄຸມມຸມ 0–180°.
    
    `servo.write(90); // center`
    
37. **Stepper motor — Stepper**  
    ອະທິບາຍ: ຄວບຄຸມການຍ້າຍຢ່າງລະອຽດ (step).
    
    `stepper.step(100);`
    
38. **Stepper motor driver board — Driver for stepper (e.g., A4988)**  
    ອະທິບາຍ: ຈັດການກຳລັງແລະຊັ້ນສັນຍານສໍາລັບ stepper.
    
39. **Real-time Clock Module DS1302 — RTC DS1302**  
    ອະທິບາຍ: ຈັດການເວລາ/ວັນທີ (backup battery).
    
    `rtc.read(); // get current time`
    
40. **74HC595 Chip — Shift register 74HC595**  
    ອະທິບາຍ: ເພີ່ມຈຳນວນ output pins ດ້ວຍ SPI-like shift out.
    
    `shiftOut(dataPin, clockPin, MSBFIRST, 0b10101010);`