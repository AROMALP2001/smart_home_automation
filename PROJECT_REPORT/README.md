This is our home automation project, featuring offline voice-based control. This guide provides instructions to make same project or similar project.

Required components:

3 relays
1 ESP8266 NodeMCU
AI Thinker VC-02 Module
2 Lamps,Fan,Door Lock
Instructions:

Install PlatformIO in VS Code and create a new project within PlatformIO, selecting NodeMCU 1.0.
Paste the provided main.cpp code into the src/main.cpp file.
Paste the platformio.ini code.
Upload the code to your component.
Download the APK and input your ESP IP address. Two functions will work: offline web control and offline voice control.
The SDK file for the Ai-Thinker VC-02 module is created by downloading the VC-02 SDK from the official Ai-Thinker website and installing the required tools mentioned in the documentation. Using the SDK, custom voice commands are defined and trained according to the project requirements. The SDK then generates the corresponding firmware files based on the trained commands. These generated files are finally flashed onto the VC-02 module using the recommended programming tool.
The cloud-based version is solely for our internal use. If you would like to build this project and require assistance, please contact us at aromalpsj2001@gmail.com.
