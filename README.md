# Travel-Booking-System

Console App

DESCRIPTION
-----------
Academic Project from Spring Quarter 2018, CSCD 349 - Design Patterns
Collaborative app with Tony Kolstee. Designed to read a trip manifest text file formatted in a specific way (parser designed around this format), then display trip data, allow the user to add new data to trip manifest and build trips off this data. Ability to export newly created trips in console appened back into the original text file or to a new one. Able to deliver prices for trips based on certain seating conditions user selects.

HOW TO RUN
----------
Project created in IntelliJ. 
* App can be launched from path, "Travel Booking System - Console App/src/UserInterface/UI.java".
* Main entry point at "UI.java". 
* During program launch, select menu option, "1: Work with Airline System".
* In AIR System Menu; if you want to load a premade trip manifest, select option, "1: Read input file" and when prompted to "Enter File Name", use, "AMSin.txt" or "altAMSin.txt" to load data.
* App can be run from "Tester.java". Standard conditional tester.

KNOWN BUGS
----------
No known bugs

NON-FUNCTIONING FEATURES
------------------------

* Rail and Cruise Ship system not fully implemented
* Not all Admin features enabled

PLANNED DESIGN UPDATES
----------------------
* If file, "AMSin.txt" is read in and then a duplicate airline or port entered causes intended error messages to display. I need to make it so that duplicated entries are just ignored. Error messages look too negative for user experience.
* Would love to convert this to a GUI app, might do in a future course or on free time as a challenge.
