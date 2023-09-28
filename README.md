# Lab1-SpinningUpReactNativeApp

Lab Assignment 1: Spinning Up React Native App

System Requirements
CPU: 2.0 GHz dual-core processor or better
RAM: 4 GB or higher
Operating System: Windows 7 or newer (64-bit)
Disk Space: 2 GB of free space

Installation Instructions:
Install the following tools and dependencies for React Native development:

Node.js: React Native requires Node.js. Download and install it from https://nodejs.org/. Recommended to use the LTS version.

Java Development Kit (JDK): Install JDK 8 or newer from https://www.oracle.com/java/technologies/javase-downloads.html.

Android Studio: Download and install Android Studio from https://developer.android.com/studio. 

React Native CLI: Install the React Native CLI globally by running the following command in your terminal: npm install -g react-native-cli

Configuration Steps
Environment Variables:
Open System Properties > Advanced > Environment Variables.
Add a new system variable named ANDROID_HOME and set it to the path of your Android SDK installation (e.g., C:\Users\<your-username>\AppData\Local\Android\Sdk).

Project Creation
Open the terminal and navigate to the directory where you want to create your project.
Run the following command to create a new React Native project (replace <project-name> with your desired project name): npx react-native init <project-name>


Running the Project
To run your React Native project on an Android Device Simulator:
Open a terminal in your project directory.
Start the Metro development server by running the following command: 
npx react-native start

It should give the option to run android simulator by pressing ‘a’

This will build your React Native app and launch it in the Android Device Simulator.
Troubleshooting
Debugging: To debug your React Native app, you can use tools like React Native Debugger or enable debugging in your emulator. You can also use the console.log() function to log messages for debugging purposes.
Common Issues: If you encounter common issues or error messages during development, refer to the React Native Troubleshooting guide.

