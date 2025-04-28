# FPGA-Powered-Intervehicle-Rover
My capstone project was an FPGA-Powered Intervehicle Rover System, designed to establish reliable, low-latency communication between multiple autonomous vehicles. 
The aim was to explore scalable, decentralized rover coordination for potential applications in swarm robotics and autonomous navigation. 
We used an FPGA (Basys 3) as the master controller, communicating with ESP32-based slave rovers over Wi-Fi using the ESP-NOW protocol.
My core responsibility was establishing and testing reliable bidirectional communication between two ESP32s using the ESP-NOW protocol. I ensured real-time data transfer with a throughput of 2 Mbps, while maintaining signal stability even under Wi-Fi interference. Alongside, I contributed to Verilog modules for basic FPGA operations
This project gave me hands-on experience in embedded communication protocols, real-time control, and interfacing FPGA with wireless microcontrollers

Key takeaways:
Used esp_now_send() to transmit messages.

Used esp_now_register_recv_cb() to receive messages.

Configured both ESP32s in WIFI_STA mode.

Built a loop that sent data periodically (say every 100 ms).

Set up receivers to instantly react on incoming data (example: control motors).

Real-World Application Use-Cases
✅ Search and Rescue in disaster-hit areas.
✅ Agricultural monitoring over large fields.
✅ Remote military reconnaissance.
✅ Space exploration (Mars rovers concept).
✅ Industrial warehouse automation.


