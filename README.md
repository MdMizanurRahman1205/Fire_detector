# Fire_detector

This simple yet powerful Arduino sketch reads analog input data (e.g., from a sensor like an LDR, potentiometer, or flex sensor) and triggers an LED based on a threshold.

💡 Features:
Reads analog input from pin A0
Displays real-time sensor values on the Serial Monitor
Turns on the onboard LED (pin 13) when input drops below 1000
Holds the LED ON for 2 seconds, then rechecks

⚙️ How it Works:
The analog signal is continuously monitored.
If the input value is less than 1000, it considers the condition as "triggered".
The LED lights up for visual feedback.
If the condition is not met, the LED remains OFF.

🧪 Use Cases:
Light detection (LDR)
Pressure detection (Flex sensor)
DIY motion or proximity triggers
Threshold-based alerts

📦 Components Required:
Arduino Board (UNO, Nano, etc.)
Analog sensor (LDR, flex sensor, etc.)
Jumper wires

Design & develop by MD MIZANUR RAHMAN
