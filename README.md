# STM32 / ESP32 Interactive Simulators

แบบจำลองวงจรและโค้ด Arduino ที่เปิดเล่นได้จากเว็บเบราว์เซอร์ โดยไม่ต้องติดตั้งโปรแกรมเพิ่มเติม

## ทดลองเล่น

เปิดหน้าเมนูรวมเพื่อเลือกเล่นทั้ง 4 แบบจำลอง:

**[เปิดแบบจำลองทั้งหมดบนเว็บ](https://kayminxlokilinus.github.io/STM32-ESP32-Simulators/simulators.html)**

หรือเลือกโดยตรง:

- [STM32 RGB LED: R / G / B / ALL / RUN](https://kayminxlokilinus.github.io/STM32-ESP32-Simulators/index.html)
- [STM32 RGB LED: Mode 1-3](https://kayminxlokilinus.github.io/STM32-ESP32-Simulators/mode_1_3_simulator.html)
- [STM32 Logic Gate: AND / OR / NAND / NOR / XOR / XNOR](https://kayminxlokilinus.github.io/STM32-ESP32-Simulators/logic_gate_simulator.html)
- [ESP32 Telegram IoT](https://kayminxlokilinus.github.io/STM32-ESP32-Simulators/esp32_telegram_simulator.html)

ถ้าลิงก์ยังเปิดไม่ได้ ให้เปิดที่ repository **Settings → Pages** แล้วตั้ง `main` และ `/ (root)` จากนั้นรอการ deploy สักครู่

## การควบคุม

- แบบจำลอง RGB เมนู: ใช้ปุ่ม SW1 และ SW2
- แบบจำลอง Mode 1-3: ใช้ SW1 หรือแป้น `N`
- แบบจำลอง Logic Gate: ใช้ SW1, SW3, SW4 หรือแป้น `N`, `1`, `2`
- แบบจำลอง ESP32: ใช้ SW1, SW2 หรือแป้น `1`, `2`

แบบจำลอง ESP32 ทำงานแบบออฟไลน์และไม่ส่งข้อมูลไป Telegram จริง
