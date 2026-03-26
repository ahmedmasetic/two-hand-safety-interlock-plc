# two-hand-safety-interlock-plc
This project simulates a two-hand safety interlock system implemented on an Arduino Opta PLC, inspired by industrial safety control logic.

The system requires two push buttons to be pressed simultaneously to activate a green indicator lamp (safe operation). A yellow indicator represents standby mode, while a red indicator signals a fault condition.

A limit switch triggers the fault state, disabling all inputs to prevent operation. The system can be reset to standby mode using a programmable button on the PLC.

This type of control logic is commonly used in industrial machinery to ensure operator safety.
