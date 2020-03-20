Basit_Abdul_17093834_MAD_Cwk2_ReadMe
This readme file is created by Abdul Basit, ID No. 17093834, at Manchester Metropolitan University in final year of BSc (Hons) Computer Forensics & Security for coursework 2 of module Mobile Applications Development in year 2019-20.

React Native Installation
React Native Official guide for project setup was followed. This is available on website (https://reactnative.dev/docs/getting-started).

Modules Installed / Needed to Make / Run the App
Following modules were installed to make the app and will be required to run the app.
•	react-navigation
•	react-navigation-stack
•	react-navigation
•	react-navigation-tabs
•	@react-navigation/drawer
•	react-native-geolocation-service
•	react-native-camera
Following commands were used to install the modules on Windows command prompt.
•	npm install react-navigation
•	npm install react-navigation-stack
•	npm install react-navigation
•	npm install react-navigation-tabs
•	npm install @react-navigation/drawer
•	npm install react-native-geolocation-service
•	npm install react-native-camera
•	npm install

Difficulties Installing / Running the Modules
Installing and running ‘react-native-camera’ module was particularly difficult because when after its installation, when the app was run using command ‘npx react-native run-android’, there were many errors that were thrown by system on command prompt. These were fixed by manually installing or deleting the directories specified in the error messages, as the program itself lacked permissions to do so.

You May Need to Downgrade Your Android Studio’s Gradle Build!
I could not run my app after installing ‘react-native-camera’ module. To fix this, I followed instructions on this website (https://github.com/react-native-community/react-native-camera/issues/2150) and downgraded the gradle build of my Android Studio, after which the app worked fine.
I added following statement in ‘build.gradle’ file in Android Studio: 
•	Dependencies: classpath("com.android.tools.build:gradle:3.4.2")
I also added following statement in ‘gradle-wrapper.properties’ file in Android Studio: 
•	distributionUrl=https\://services.gradle.org/distributions/gradle-5.5-all.zip

How to Run the App When All Modules Are Installed and Are Working?
You need following things before running commands to start the app in emulator.
•	Open command prompt window, navigate to Chittr server directory, and run command ‘npm install’.
•	Have project opened in Android Studio and have an Android Emulator running.
•	In a new command prompt, navigate to project directory and run command ‘npx react-native run-android’.
•	Wait for the build and initialization to finish. Run the command again if it does not run the app on the emulator the first time.

Note: 
If you follow the instructions given in the ReadMe file, you should be able to run the app fine. However, if you encounter any errors running the app, please feel free to reach me at abdul.basit5@mmu.ac.uk. 

