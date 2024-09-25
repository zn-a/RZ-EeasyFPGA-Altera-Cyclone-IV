# RZ EeasyFPGA Altera Cyclone IV
Altera Cyclone IV FPGA (EP4CE6E22C8N)

## Notes
- **DIG1** is the **rightmost digit**, and **DIG4** is the **leftmost digit** on the 7-segment display.
- All **pushbuttons**, **LEDs**, and **7-segment display** segments are **active-low**.
  
## Pin Assignments
### Clock and Reset
| **Signal** | **Pin** | **Description** |
|------------|---------|-----------------|
| CLK        | 23      | Clock Input (50 MHz)     |
| RST        | 25      | Reset Button    |

### LEDs
| LED   | Pin  |
|-------|------|
| LED1  | 87  |
| LED2  | 86  |
| LED3  | 85  |
| LED4  | 84  |

### Pushbuttons/DIP Switch
| Pushbutton | Pin  |
|------------|------|
| KEY1       | 88  |
| KEY2       | 89  |
| KEY3       | 90  |
| KEY4       | 91  |

### 7-Segment Display (Digit Selection)
| Digit | Pin  |
|-------|------|
| DIG1  | 133  |
| DIG2  | 135  |
| DIG3  | 136  |
| DIG4  | 137  |

### 7-Segment Display (Segment Selection)
| Segment | Pin  | Segment Part |
|---------|------|--------------|
| SEG0    | 128  | a            |
| SEG1    | 121  | b            |
| SEG2    | 125  | c            |
| SEG3    | 129  | d            |
| SEG4    | 132  | e            |
| SEG5    | 126  | f            |
| SEG6    | 124  | g            |
| SEG7    | 127  | dp (decimal point) |
