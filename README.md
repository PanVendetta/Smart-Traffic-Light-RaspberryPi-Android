# Smart-Traffic-Light-RaspberryPi-Android
An android app to control led lights imitating a traffic signal connected to a raspberry pi over Wifi. The app sends the status of the light to firebase from where it is read by the raspberry pi and the lights are turned on or off accordingly. 
Steps to be followed:
Create a firebase account.
Create a realtime database and edit the rules to "true". 
Configure your RaspberryPi.
Load the python code into the Pi.
Change the URL in the code to the URL of your database accordingly.
Run the code. (terminal command - python LED.py)
Open the android code in android studio and connect the app to your firebase account.
Run the code.
You can now change the leds using your phone/emulator.
