Bluetooth Control of Arduino CLI using Android.

Development in Progress.

Current Update :

Added three Button on the TerminalActivity's GUI
Click on any of them to send the message through bluetooth, and hold them to change the message.

Terminal Activity implements View.ONCLICK and View.ONLONGCLICK Listener's.

UPDATE #2
Added message catching from the Arduino such that it will catch the message from Arduino untill it is not active anymore. Basically
Implemented a Timer to see if the Ardino is still sending ( timer is of 1 sec ).
Then Added the response to GUI Buttons.
