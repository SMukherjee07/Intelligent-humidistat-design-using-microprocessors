# Intelligent-humidistat-design-using-microprocessors
This project involves the design and development of an intelligent humidistat using an Intel microprocessor. The humidistat is capable of monitoring both temperature and humidity levels in the environment.

## Intelligent Humidistat Project

### Description

This project involves the design and implementation of an intelligent humidistat using an Intel 8086 microprocessor. The system monitors and controls humidity and temperature levels, displaying real-time data on an LCD screen and triggering alerts when predefined limits are exceeded.

### Components

1. **Microprocessor and Memory:**
   - Intel 8086 Microprocessor
   - Memory is divided into two banks: Even and Odd banks of RAM and ROM

2. **Latches and Buffers:**
   - 3 x 74LS373 Latches
   - 2 x 74LS245 Buffers

3. **Peripheral Interface:**
   - 2 x 8255A Programmable Peripheral Interface

4. **Sensors:**
   - LM35 Temperature Sensor
   - DHT22 Humidity Sensor

5. **Display:**
   - LMD2DL LCD Display

6. **Additional Components:**
   - Power supply
   - Interconnecting wires and connectors

### Circuit Description

1. **Microprocessor and Memory Configuration:**
   - The 8086 microprocessor is interfaced with RAM and ROM divided into even and odd banks.
   - Two 74LS245 buffers are used for bus interfacing.

2. **Peripheral Interfacing:**
   - Two 8255A PPI chips are used to interface with sensors and display.
   - Three 74LS373 latches are used for data latching from the microprocessor to the 8255A.

3. **Sensors and Display:**
   - The LM35 temperature sensor and DHT22 humidity sensor provide real-time data to the system.
   - The LMD2DL LCD display shows temperature and humidity levels, with alerts for exceeding limits.

### Features

- **Real-time Monitoring:** Continuous monitoring of temperature and humidity levels.
- **Alerts:** Visual alerts on the LCD display when temperature or humidity exceeds predefined limits.
- **User-Friendly Display:** Clear and concise display of data on the LCD.


### Installation and Usage

1. **Component Assembly:**
   - Assemble the components as per the schematic diagram.
   - Connect the sensors to the input ports of the 8255A.
   - Connect the LCD display to the output port of the 8255A.

2. **Programming:**
   - Load the control program onto the 8086 microprocessor to handle data from sensors and display outputs using assembly language.

3. **Power Up:**
   - Power up the system and observe the real-time data displayed on the LCD.

### Troubleshooting

- **No Display:** Check connections to the LCD and ensure the 8255A is properly interfaced.
- **Incorrect Readings:** Verify sensor connections and calibration.
- **No Alerts:** Ensure alert thresholds are correctly set in the control program.

### Conclusion

This intelligent humidistat system provides a robust solution for monitoring and controlling environmental conditions, with clear data display and alerts for effective management.

---

