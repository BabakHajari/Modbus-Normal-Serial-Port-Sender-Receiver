# ModbusConver – Serial & Modbus Communication Utility

ModbusConver is a lightweight and practical software utility designed for engineers, PLC programmers, and automation specialists who need to communicate with industrial devices via Serial Port and Modbus RTU protocols.

The software simplifies the configuration of serial communication, Modbus message generation, checksum calculation, and response analysis—making it an effective tool for testing, commissioning, troubleshooting, and simulation of industrial systems.

---

## Key Capabilities

- Configure serial port parameters (COM port, baud rate, parity, stop bits)
- Build and send Modbus RTU or custom serial messages
- Automatically calculate and append Modbus CRC
- Send commands and receive responses with adjustable timing
- Real-time logging of transmitted and received data
- Operate in Send, Receive, or Send-by-Receive (loop simulation) modes

---

## Integrated Engineering Calculators

- Hex ↔ Decimal conversion
- 2-byte Hex to real value conversion (scaled using minimum and maximum values)
- 4-byte IEEE-754 Hex to real value conversion
- Practical tools for validating sensors, transmitters, and data acquisition systems

---

## Configuration & Extensibility

- Message definitions stored in editable `.ini` configuration files
- Support for multiple predefined messages
- Compatible with Modbus and non-checksum proprietary protocols
- Example configurations included for Advantech ADAM modules:
  - ADAM-4017 (Voltage / Current)
  - ADAM-4015 (PT100 Temperature)
  - ADAM-4018 (Thermocouple Temperature)

---

## Typical Applications

- PLC and SCADA development
- Industrial sensor and DAQ system testing
- Modbus device commissioning and diagnostics
- Automation system simulation without physical hardware
- Training and educational environments

---

## Value Proposition

ModbusConver reduces development time, simplifies debugging, and eliminates the need for multiple external tools by combining communication, calculation, and logging into a single, easy-to-use application.
