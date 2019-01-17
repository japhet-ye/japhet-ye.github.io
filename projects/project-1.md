---
layout: project
type: project
image: images/micromouse.jpg
title: peeH
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2016-07-01
labels:
  - Hardware Development
  - Arduino
  - MITApp Inventor
summary: My team developed a pH sensor that will output to a tablet over Bluetooth information regarding the pH of their urine.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

In my sophomore year we were tasked in creating a product using an Ardiuno microcontroller and the MITApp Inventor development kit for Android. The product could be anything and it was our responsibility to try and market it to the instructor. My group came up with peeH, a pH sensor that could be attached to a toilet or urninal in a permanent care facility so that nurses can easily check if a patient is staying hydrated.

For this project, I was the unit tester and debugger. I started by sketching a circuit diagram to connect the Arduino to the required sensors. From there, I tested the code that was given to me by the programmer to see if the desired signals were being made and proccessed correctly. The Arduino would proccess the data being sent from the sensor and update the display of the tablet to show the correct information. If anything was not working correctly I would skim through the code and try to help debug the program. After a couple weeks of testing, debugging, and redesigning our group finished the project. For the project we received and 'A' for the course.

After the initial development, I took the idea further and pitched it to Booz Allen Hamilton in their annual Pitch Night. This event helps students develop the neccessary business skills needed to sell a product or idea to more non-technical and business oriented employers (similar to the television show Shark Tank). The representatives loved the idea and helped me build some of my current presentation skills along the way. 

# Here is some code that illustrates how we read values from the line sensors:

#```js
#byte ADCRead(byte ch)
#{
#    word value;
#    ADC1SC1 = ch;
#    while (ADC1SC1_COCO != 1)
#    {   // wait until ADC conversion is completed   
#    }
#    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
#}
#```




