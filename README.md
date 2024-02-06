# JiggleJiggle
Mouse Jiggler
Overview
Mouse Jiggler is a simple Java program designed to keep your computer awake by intermittently moving the mouse pointer. This prevents the screen from entering sleep or screensaver mode. The program provides a user interface with "Start" and "Stop" buttons to control the mouse jiggling.

Table of Contents
Features
Prerequisites
Installation
Usage
Customization
Troubleshooting
Contributing
License
Features
Start and stop mouse jiggling with the click of a button.
Barely perceptible mouse movement to keep the screen awake.
User-friendly graphical interface using Java Swing.
Prerequisites
Java Development Kit (JDK) installed on your system.
A Java-compatible operating system (Windows, Linux, or macOS).
Installation
Download the Source Code:

Clone this repository or download the source code ZIP file.
Compile the Java Code:

Open a terminal or command prompt.
Navigate to the directory containing the jiggleJiggle.java file.
Compile the Java code using the following command:
sh
Copy code
javac jiggleJiggle.java
Usage
Run the Program:

After compilation, run the program with the following command:
sh
Copy code
java jiggleJiggle
User Interface:

The program will launch a graphical user interface (GUI) with "Start" and "Stop" buttons.
Start Mouse Jiggling:

Click the "Start" button to initiate the mouse jiggling.
Stop Mouse Jiggling:

Click the "Stop" button to halt the mouse jiggling.
Customization
Adjusting Jiggle Frequency:
Open the jiggleJiggle.java file in a text editor.
Locate the timer = new Timer(500, ...) line and adjust the value (in milliseconds) to change the jiggle frequency.
Troubleshooting
If you encounter any issues, check the Troubleshooting section in the project repository or create a new issue.
Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.
License
This project is licensed under the MIT License.

