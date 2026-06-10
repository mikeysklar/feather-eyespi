# feather-eyespi

A plus-size FeatherWing base board that accepts an Adafruit Feather and breaks out an EYESPI connector for eInk and TFT displays.

Working with a lot of eInk and TFT displays means constantly re-wiring the EYESPI cable. This adapter cuts out that step — plug the Feather in, plug the display in, done. Single-sided board with minimal routing to keep assembly straightforward.

### BOM

| Part | Package | 
|------|---------|
| EYESPI | 18-pin FPC connector 
| headers | Female 2.54mm vertical SMT 
| Resistor, 0Ω | 0805 

### EYESPI Connected to eInk

![asm1](pics/asm1.jpeg)

---

### Assembled

![asm2](pics/asm2.jpeg)

---

### 18-pin FPC 

![asm3](pics/asm3.jpeg)

---

### Metal Business Card Stencil

![asm4](pics/asm4.jpeg)

---

### Finish PCB Silk / Mask Etched

![asm5](pics/asm5.jpeg)

---

### Wiring

| Feather Pin | Net | EYESPI Pin | Function |
|-------------|-----|-----------|----------|
| SCK | sck | 15 | SPI clock |
| MOSI | mosi | 14 | SPI data out |
| MISO | miso | 13 | SPI data in |
| D11 | rst | 11 | Reset |
| D10 | dc | 12 | Data / Command |
| D12 | busy | 3 | Busy / Ready |
| D9 | tcs | 10 | TCS chip select |
| 3V3 | 3v3 | 18 | 3.3V power |
| GND | gnd | 16 | Ground |

---

### Fiber Laser Etched PCB 

![asm6](pics/asm6.jpeg)

---

### Backside board ID

![asm7](pics/asm7.jpeg)

---

### KiCAD PCB

![asm8](pics/asm8.png)

---

## License

This project is licensed under the GNU General Public License v3.0 — see the [LICENSE](LICENSE) file for details.
