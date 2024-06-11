# ESP32 USB Mouse to BLE

This project is based on esp-idf. It is tested on esp32s3 and an a4tech mouse.

If you are using USB A connector, connect D- to GPIO19 and D+ to GPIO20.

This project is a proof of concept to demonstrate the feasibility of the idea. It is not intended for serious real-world deployments.

Use of esp32s3 (in comparison to esp32) is because of its support for USB host. Use esp-idf 5.3 or later to support macOs.