# ESP32 LCD 16X2 4bits

Functional way to connect ESP32 to 16x2 LCD without I2C module, using 4-bit communication.

Here is where the [code](https://github.com/silvajhb/ESP32LCD16X24b/blob/master/SOFTWARE/VSCode/ESP32LCD16X24b/src/main.cpp) stretch you should pay attention to as well as make the [correct connections](https://github.com/silvajhb/ESP32LCD16X24b/blob/master/HARDWARE/DOCUMENTS/sheet.png) in board.

```cpp
const int rs = 23, rw = 4, en = 22, d4 = 5, d5 = 18, d6 = 19, d7 = 21;
LiquidCrystal lcd(rs, rw, en, d4, d5, d6, d7);

```

![ESP32LCD16X44b_3D](https://github.com/silvajhb/ESP32LCD16X24b/blob/master/HARDWARE/DOCUMENTS/3D.png)

![ESP32LCD16X44bPCB-CAD](https://github.com/silvajhb/ESP32LCD16X24b/blob/master/HARDWARE/DOCUMENTS/PCB.png)

![ESP32LCD16X44b_SCHEMATIC](https://github.com/silvajhb/ESP32LCD16X24b/blob/master/HARDWARE/DOCUMENTS/sheet.png)
