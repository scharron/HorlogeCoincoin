## Board

- Arduino nano
- DS3231 to keep track of the time (with button cell to keep time when powered off)
- TBC.

[Insert schematics over there]


### DS3231

According to [this](https://forum.arduino.cc/t/zs-042-ds3231-rtc-module/268862/56), the board often comes with some badly designed circuit to charge a lithium button cell.
This should be avoided, but also is bad for non-rechargeable batteries. On the top right of the board, there is a diode and a resistor, any one of these tow can be desoldered.

To understand more about this board (low-power mainly) read [that](https://thecavepearlproject.org/2014/05/21/using-a-cheap-3-ds3231-rtc-at24c32-eeprom-from-ebay/)
