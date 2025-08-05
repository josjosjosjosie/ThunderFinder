So this is ThunderFinder

I think this program could be very useful for things like survival situation
Here is what the program does:

First the program starts.

Then the user will be able to enter a microphone sensitivity (the microphone threshold)

Following, the program will launch the camera and microphone (permissions are most likely needed)
I DO NOT STORE ANY DATA THIS PROGRAM IS COMPLETELY LOCAL, SO NO DATA IS SAVED ANYWHERE OUTSIDE YOUR DEVICE!

When the camera detects a sudden bright brightness change *lol*

A timer will start (almost) Instantly

The microphone will start detecting sound: when the mic volume hits the threshold. (Mic volume displayed on the screen)

When the microphone hits that threshold, then the timer will stop and the elapsed_ms will be used to calculate

The calculating process is the same as how you calculate the distance of thunder here is an example in meters: 343 x 1000 / 1000 = 343 meters away

Then the user will be prompted to press (q) to quit or press (r) to restart the program.
That's (almost) all it does if you wanna see or change what it all does check the source code: It's free and open source!



How to install and execute:
Go to command prompt.

In the terminal type "python3 --version" If you don't see "Python x.xx.x" (Python + version number) or something like that then go ahead and install python. Visit https://python.org/ for more information

If python is installed, type in the command prompt: "pip install --upgrade pip" to install the latest version of pip
After pip has installed the latest version, enter: "pip install opencv-python" after that is done type: "pip install sounddevice"
Download or go to the py file, once your in the folder where the py file is located (with Windows Explorer) right click and click on open in terminal. and type the following: "python3 ThunderFinder.py" and press enter. The program has executed! Now it may ask for your camera access so allow that (don't worry it isn't stored) and before starting first use something like a flashlight to activate the microphone so you can allow that. This is one time only. Now you can reopen the program and start using it! 

Linux users will figure it out :( sorry i don't know linux that good ):

Mac users i'm also sorry.