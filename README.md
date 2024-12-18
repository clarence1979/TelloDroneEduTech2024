<h1># TelloDroneEduTech2024 / DigiCon 2024 </h1>
Introduction:
This repository contains the code to control the Tello Drone using voice and Google Gemini. Run this in in any Python editor in Windows with all dependencies installed.

<h2>Program 1:</h2>
File(s): yesno.py <br><br>
Description: This program gets a verbnal question from the user. It passes on to Gemini AI and gets a response of either "yes" or "no". The drone will "nod" if "yes" and will shake its "head" when saying no.

<h2>Program 2:</h2>
File(s): config.json
mainfile.py
tellobasic.txt <br><br>

This program runs an action on the drone based on what is spoken. The list of available actions are stored in the tellobasic.txt. More actions can be added from this website: https://djitellopy.readthedocs.io/en/latest/tello/. 
The purpose of this file is to restrict the number of actions that can be selected by the AI-generated code so that there are no errors. 
Remember to also set your Gemini API Key in config.json prior to use.You can get an API Key from this link: https://ai.google.dev/gemini-api/docs/api-key
Speak what you want, and the drone will obey your command.

<h2>Program 3:</h2>
File(s): samplestudentcode_image_recognition.py <br><br>
This program is an example student code and which uses the Tello drone and takes a picture of objects. The name oif the object is passed to the AI, which then recognises the object. The description of the object is displayed on the screen. 

<h2>Notes:</h2>
Feel free to use my code in your projects. Email me at (https://clarence.guru) if you have any questions or need help.
Currently working on multiple / simultanous object Image Recognition using Gemini AI. Contact me if you would like a copy of the code.

<br><br>

Update 29/11/2024: New version of codes available - runs using Jupyter in VSCode under Windows or Linux. Contains code to close ports for drones when not in use. All code integrated into 1 file with no need for seperate files. Updated GUI that will work even if the if the drone is not detected. Contact me for updated code. Also made a seperate module for number plate detection and object using Drones and AI. Outputs to a CSV.
<br><br>

Working on: Automated language detection with AI and drones - ability to recognise any commands in any language. Web interface will be available soon - and will run from a web browser.
