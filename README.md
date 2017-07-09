# PuzzlerVR
**Puzzler VR** is part of the Udacity VR design course, which explains major aspects of the design and usability considerations
which need to be made while creating a VR experience. This documents explains the process followed in building this application.

**Puzzler VR** is a classic Simon says game which can be experienced using the Google Cardboard. 

Any project needs to have a statement of purpose and the target audience of the application, and Puzzler VR was no different. 

The statement of purpose for this project is **"Puzzler is a mobile VR application for the new VR users which challenge them to solve a familiar type of puzzle in a new way"**

Prior to starting the project, the description of my target audience was as follows:
"My main aim would be to design the application so that it is simple enough for a broad audience comprising of different age groups. The target audience will be folks who are interested in game/education applications. It is important not to assume the audience knows the rules of the game, so design considerations should be in place to have a good introduction so that they understand the rules .  Depending on the type of puzzle it is important to have a proper balance of having the game both challenging and provide an option to get hints, so that the user feels safe and in control."

Persona:
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Persona.JPG' title='Persona' width='' alt='Persona' />

Design consideration were also made to figure out the ideal distance where the dungeon needs to be place so that the user is comfortable  and it turns out the 0.5 meters is the general distance where people begin to feel uncomfortable.

In terms of UI design the first step was to design Low-Fi sketches as below:
**Sketch 1**
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Sketch%201.JPG' title='Sketch 1' width='' alt='Sketch' />
**Sketch 2**
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Sketch%202.JPG' title='Sketch 2' width='' alt='Sketch' />
**Sketch 3**
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Sketch%203.JPG' title='Sketch 3' width='' alt='Sketch' />

Once a basic skeleton structure was in place, conducted user test.

Go the feedback from 1 user. Notes below:

Q) How big/small do you feel in the experience ?
A) The user feels like they are of the normal size

Q) What is the mood and setting like?
A) Mood feels like Game of thrones, medieval type setting

Q)Is there anything you like to look but difficult to see?
A) The torches seem to be flickering that feels artificial, other than that it looks good

Q) Can you identify the elements you can interact with?
A) The greens balls seem to be inter-actable for sure. The other objects may or may not be inter-actable, but the green balls for sure

**Conclusion**: It was great to receive the feedback. Got good feedback about the torch flickering, so will have to fix it. Glad to hear that the green balls seem the obvious components to interact with.

***Another user test was conducted with regards to motion***

Q) How do you find the speed ?
A) The speed is normal

Q) Do you feel sick ?
A) No, I don’t

Q) Did you notice anything disorienting?
A) Nothing noticeably wrong. The lighting can be better

**Final Product:**

The video below shows the final version. The game starts of with a panel prompting the user to start the game.
One pressing the start, the user is taken to the dungeon where the game begins. The balls get highlighted in a random sequence and the challenge is to match the sequence.
If the user fails to match the sequence , there will be a fail sound played and a new game begins. Once the user successfully matches the sequence he will be moved from the dungeon to the congrats panel where the user has the option to restart the experience.

**Video**
Click the image below to watch the video
[![Puzzler](https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Screenshot%201.png)](http://www.youtube.com/watch?v=IRdImFMuYW8 "Puzzler")


Screenshots:
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Screenshot%201.png' title='Screenshot 1' width='' alt='Screenshot' />
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Screenshot%202.png' title='Screenshot 2' width='' alt='Screenshot' />
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Screenshot%203.png' title='Screenshot 3' width='' alt='Screenshot' />
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Screenshot%204.png' title='Screenshot 4' width='' alt='Screenshot' />
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Screenshot%205.png' title='Screenshot 5' width='' alt='Screenshot' />
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Screenshot%206.png' title='Screenshot 6' width='' alt='Screenshot' />
<img src='https://github.com/nirvanalab/PuzzlerVR/blob/master/Documentation/Puzzler%20Screenshot%207.png' title='Screenshot 7' width='' alt='Screenshot' />



**Next steps:**

Improve the game logic with stats of the number of attempts made. 
Need to improve the lighting and visual appearance of the game

