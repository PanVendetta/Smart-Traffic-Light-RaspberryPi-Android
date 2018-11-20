# Smart-Traffic-Light-RaspberryPi-Android
An android app to control led lights imitating a traffic signal connected to a raspberry pi over Wifi. This app sends the status of the light to firebase from where it is read by the raspberry pi and the lights are turned on or off accordingly. 
Steps to be followed:<br>
Create a firebase account.<br>
Create a realtime database and edit the rules to "true".<br>
Configure your RaspberryPi.<br>
Set up wifi on your Raspberrypi.<br>
https://www.raspberrypi.org/documentation/configuration/wireless/wireless-cli.md <br>
Load the python code into the Pi.<br>
Change the URL in the code to the URL of your database accordingly.<br>
Run the code. (terminal command - python LED.py)<br>
Open the android code in android studio and connect the app to your firebase account.<br>
Run the code.<br>
You can now change the leds using your phone/emulator.
