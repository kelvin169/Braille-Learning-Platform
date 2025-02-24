*Braille Learning Platform*
This project is a Braille learning platform that simulates a 2x3 dot matrix to display Braille characters.
The system uses off-the-shelf hardware components, such as an ESP8266 NodeMCU for connectivity, and servo motors to raise or lower the dots in the matrix. A web interface, built with React.js (frontend) and Node.js (backend), allows users to interact with the platform to send and receive Braille characters.
The login Page has been added as shown below
![img_alt](https://github.com/kelvin169/Braille-Learning-Platform/blob/main/LogIn_Page.png)

![img_alt](https://github.com/kelvin169/Braille-Learning-Platform/blob/main/Braille_Learning.png
)
Features
2x3 Dot Matrix Display: Simulates Braille characters using servo motors.
ESP8266 NodeMCU Connectivity: Connects the hardware to the online platform using WebSockets.
Web Interface: Built with React.js for user interaction and Braille input/output.
Node.js Backend: Manages communication between the frontend, hardware, and database.
Real-time Braille Interaction: Users can input text, which is converted to Braille on the 2x3 matrix and vice versa.
Tutor-Assisted Mode: Includes a learning mode where a tutor can assign tasks or communicate via Braille.
Hardware Components
ESP8266 NodeMCU: Microcontroller for connecting the hardware to the web interface.
2x3 Matrix of Servo Motors: Each servo simulates one Braille dot, raised or lowered based on input.
Tactile Buttons: For Braille character writing input.
Speaker: Outputs sound feedback during learning sessions.
Power Supply: To power the NodeMCU and servo motors.
Software Components
React.js (Frontend): User-friendly interface for learners and tutors.
Node.js (Backend): Handles API requests, WebSockets, and database connections.
ESP8266 Firmware: Arduino-compatible code to control the hardware.
Database: Stores user accounts, learning progress, and Braille input/output.
