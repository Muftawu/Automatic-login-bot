# Automatic-login-bot


INTRODUCTION 
Hello guys, welcome to another video. 
Today we are going to unlock our computers with a unique hand gesture without having to type our password directly. 
Stay tuned and enjoy.

HOW IT WORKS
The main project idea is centered around the PyAutoGUI library.
Using the pyautogui package from python, we can print or type sentences onto the screen so far as we tell the program what to print. 
Integrating this package with openCV, CVZONE and mediapipe libraries, 
we can track our hand movement or patterns and execute a specific command based on our preference. 

So basically, we track our hand gestures through our webcam with the help of the Hand Tracking Module from cvzone. 
When the tracker detects our preferred hand gesture, the pyautogui is immediately alerted to print out a sentence.( in this scenario, our password). 
This will be achieved by initially running the program and logging out while the webcam is still active. 
This prints or types the password in and afterward the program automatically hits the enter key to log us in. 
