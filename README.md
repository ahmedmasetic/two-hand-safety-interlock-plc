# two-hand-safety-interlock-plc
This project simulates a two-hand safety interlock system implemented on an Arduino Opta PLC, inspired by industrial safety control logic.

The system requires two push buttons to be pressed simultaneously to activate a green indicator lamp (safe operation). A yellow indicator represents standby mode, while a red indicator signals a fault condition.

A limit switch triggers the fault state, disabling all inputs to prevent operation. The system can be reset to standby mode using a programmable button on the PLC.

This type of control logic is commonly used in industrial machinery to ensure operator safety.

<img width="698" height="1323" alt="2-hand-interlock" src="https://github.com/user-attachments/assets/b5ac9594-a977-43ce-aab9-65c9720196c1" />


<h2>Wiring diagram:</h2>
<img width="1044" height="490" alt="2-hand-schematic" src="https://github.com/user-attachments/assets/2bc90916-9da4-4a51-af4d-12764f0c3d64" />


<h2>Demo video:</h2>
https://github.com/user-attachments/assets/7e3a7e17-94ba-4797-bcc9-6bde31e4a5db

