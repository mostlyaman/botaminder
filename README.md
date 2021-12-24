# Botaminder
## A arduino bot to remind you of stuff

#### Always forgetting events while working in online classes? 

Build a arduino bot to throw reminders in your face so you dont join your meeting 5 mins late.
Still not convinced? It also reminds you of regular breaks, staying hydrated and taking your eyes off screen.

![Circuit Diagram](https://github.com/mostlyaman/botaminder/blob/master/images/circuitdiagram.PNG)


## Important Information

This is an submittion to Build-a-Bot contest in IIT Mandi by Team FreshBOTS. This is free to use by anyone but the Google Calendar integration may not work for you
as OAuth Authentication is set up under the IIT Mandi Organisation and only google accounts registered under the IIT Mandi organisation are able to allow this app to 
access their Calendar Events. You can, however, still use the manual mode to enter your event details and save them into a profile for rapid use.

## Components List and Overview

The project uses  two 16x2 LCDS, Arduino board of some sort (Arduino Sketch in this project is prototyped for Arduino Uno), a push button for input, a mute slide switch and
2 buzzers. 

1. **Arduino Uno** - To drive the displays and handle alarms for all the events.
2. **2 LCDS(16x2)** - To display output. LCD 1 shows current time and mode in which the arduino is programmed (see [Modes](#modes)) and LCD 2 shows the cycles through all the future
one by one with a user defined interval (default 4 seconds).
3. **Mute Slide Switch** - Mutes and Unmutes the bot at the switch of a button.
4. **Push Button Input** - A button to turn off ringing alarms.
5. **2 Buzzers** - To produce sound for the alarms, duh? Why 2, you ask? Because it is better than 1!


