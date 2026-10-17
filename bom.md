# Bill of materials
This file contains all the parts needed to build the robot.
Apart from the electrical parts, you will need a 3D printer, soldering iron, and two M2 and one M3 screw (M2 holds the IMU, M3 connects the top part to the bottom).

All parts were sourced in Stockholm, Sweden, so prices are in SEK and the links go to Swedish shops. Equivalent parts should be easy to find elsewhere.
## Parts and prices
Prices are approximate.

| Part | Model | Qty | Price per piece (SEK) | Total (SEK) | Links |
|------|-------|----:|----------------------:|------------:|-------|
| Microcontroller | ESP32-S3 | 1 | 120 | 120 | [shop](https://www.amazon.se/-/en/ESP32-S3-WROOM-1-N16R8-ESP32-S3-DevKitC-1-Development-Board/dp/B0FYFF8CB2/ref=sr_1_5?sr=8-5), [documentation](https://docs.espressif.com/projects/esp-dev-kits/en/latest/esp32s3/esp32-s3-devkitc-1/user_guide_v1.1.html#hardware-reference) |
| Motor | N20 12V DC motor | 2 | 150 | 300 | [shop](https://www.electrokit.com/en/dc-motor-with-gearbox-12vdc-1-150-200rpm-with-encoder) |
| Motor controller | TB6612 | 1 | 120 | 120 | [shop](https://www.electrokit.com/en/tbb6612-motordrivare-2-kanal-4.5-13.5v-monterad-pa-kort) |
| IMU | BMI160 | 1 | 91 | 91 | [shop](https://www.amazon.se/dp/B0836MYYQX), [datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bmi160-ds000.pdf), [board documentation](https://xpart.org/product/bmi160-6-axis-rate-gyro-gravity-accelerometer-sensor-module/) |
| Motor battery | LiPo 3S 450 mAh | 1 | 196 | 196 | [shop](https://www.amazon.se/-/en/450mAh-Battery-Connector-Torrent-Flite/dp/B0714GN73V/ref=sr_1_1?sr=8-1) |
| DC voltage converter for the ESP | LM2596s | 1 | 10 | 10 | [datasheet](https://www.ti.com/lit/ds/symlink/lm2596.pdf) |
| Resistor (pull up for I$^2$C)| 6.8 kΩ (R3, R4) | 2 | 1 | 2 | |
| Resistor (battery divider) | 22 kΩ (R2) | 1 | 1 | 1 | |
| Resistor (battery divider)| 100 kΩ (R1) | 1 | 1 | 1 | |
| Capacitor (battery divider)| 100 nF (C1) | 1 | 2 | 2 | |
| **Sum** | | | | **843** | |
