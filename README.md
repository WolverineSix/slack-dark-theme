# slack-dark-theme
Javascript file with embedded css to create a dark theme for Slack desktop app.

On the MAC:

Go to Applications, right click on slack.app and click show contents…
 
Contents -> Resources -> app.asar.unpacked -> src -> static -> 
Save the existing ssb-interop.js somewhere else, or rename the file

Replace that file with the one enclosed here.
 
Close and restart Slack.app


On the PC:
Navigate to Windows C:\Users\<USERNAME>\AppData\Local\slack\app-<VERSION>\resources\app.asar.unpacked\src\static
 
Save the existing ssb-interop.js somewhere else, or rename the file

Replace that file with the one enclosed here.
 
Close and restart Slack.app


-------------------
In addition, for consistency of the look and feel across the application, you need to change your sidebar preferences.
Click on your workspace -> preferences -> sidebar
Scroll to the bottom and choose "Custom Theme" and copy and paste these values into the text box:
#1d1d1d,#000000,#0ba8ca,#FFFFFF,#075566,#FFFFFF,#0ba8ca,#EB4D5C
