Touch-Controlled LED Blink with OpenCV & ESP32

This project combines computer vision (OpenCV) with ESP32 microcontroller to create a virtual touch interface that controls an LED. By interacting with three on-screen buttons, users can trigger different LED states in real time!

🔥 Features

🖥 Virtual Buttons: Three on-screen buttons to control the LED.

👆 Touch-Free Interaction: Use finger tracking to “press” buttons.

💡 ESP32 LED Control: Sends signals to an ESP32 board to blink an LED.

⚡ Real-Time Processing: Instant feedback with OpenCV for seamless interaction.

🛠 Technologies Used

🐍 Python

📷 OpenCV (for hand tracking & button detection)

🎛 ESP32 (for hardware LED control)

🔌 Serial Communication (to send commands from Python to ESP32)

🚀 Installation & Setup

Install dependencies:

pip install opencv-python pyserial mediapipe numpy

Flash ESP32 with the provided Arduino code (included in the repository).

Connect the ESP32 to your system via USB.

🎮 How It Works

Virtual Button Setup: Three buttons appear on the screen.

Hand Tracking: OpenCV detects hand movement and fingertip position.

Button Press Simulation: When your fingertip touches a button, it triggers a command.

ESP32 LED Control: The command is sent via serial communication to the ESP32, which blinks the LED accordingly.
