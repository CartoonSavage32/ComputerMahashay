Sasta Jarvis
============

Sasta Jarvis is a Python program that uses different APIs and libraries to perform various tasks, such as transcribing audio to text, generating text from a screenshot, and executing commands.

Dependencies
------------

The following libraries and APIs are required to run the program:

-   PyAudio
-   Wave
-   OpenAI
-   PyAutoGUI
-   webbrowser
-   time
-   win32com

Usage
-----

To run the program, execute the `app.py` script. The program will prompt the user to speak a command, which will be transcribed and parsed by the program. The program will then execute the appropriate action based on the command.

Currently, the program can perform the following actions:

-   Greet the user
-   Open Twitter in the browser and compose a tweet
-   Stop the program

To stop the program, the user can say "stop" at any time.

Credits
-------

This program was created by [CartoonSavage32](https://github.com/CartoonSavage32). It uses the following APIs and libraries:

-   OpenAI API
-   PyAudio library
-   PyAutoGUI library
-   win32com library
-   Wave library
-   webbrowser library

you can add commands in execute_command function to add functionality, just add the condition in nested if else
