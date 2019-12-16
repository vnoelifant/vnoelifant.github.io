---
layout: project
title: Nao and Cozmo-Friendly Robots that Infer your Feelings
date: Sep 2019
image: /public/images/nao_ronnie_cozmo.jpg
---

## Overview

The goal of this project is to be able to have Nao detect your feelings without having to ask. 
In order to accomplish this goal, the following steps are performed:
  
  * Utilize the microphone on Nao to extract audio data which contains the "speech" of the user
  * Transfer the .wav file to Watson Speech to Text to 
  * Send the text to Watson Assistant to analyze the user's speech utterance for intents and entities based on dialogue subject of daily activities.The intents used are work, friends, and reading. 
  * Nao responds to user according to detected intent, entity, or tone and begins brief dialogue sessions with different users based on a varying order of intents. Note that Watson Assistant dialogue GUI is not used, and rather coded manually. 
  * Special effects added include Nao changing eye color based on either/both tone and transition to new user dialogue session. 

## Motivation
My Career goal is to improve the lives of people using Social Robotics. I believe this project is a good learning tool to investigate how Social Robotics research can benefit a broad audience and improve the well-being of people in versatile ways, as social robots advance further in inferring human emotions. Last quarter I conducted a similar project using Watson's TJBot. I decided to challenge myself further by taking what I learned in that project over here while also learning more advanced dialogue system algorithms and speech detection technologies. I intend to build off this project and try to implement more natural and empathetic, conversational language in the technology to humanize the experience, make users more comfortable, and develop more of a rapport with machines.  

## FINAL DEMO VIDEOS

### Case 1: Intent: Work (negative tone), transition to Intent: Friends (positive tone)
[![IMAGE ALT TEXT](http://img.youtube.com/vi/xur_3fSBAt4/0.jpg)](http://www.youtube.com/watch?v=xur_3fSBAt4 "Nao Daily Activities -2")


### Case 2: Intent: Work (positive tone), transition to Intent: Reading (positive tone)
[![IMAGE ALT TEXT](http://img.youtube.com/vi/66jmLR8TOP4/0.jpg)](http://www.youtube.com/watch?v=66jmLR8TOP4 "Nao Daily Activities -4")

### Case 3: Intent: Friends (negative tone), transition to Intent: Work (positive tone)
[![IMAGE ALT TEXT](http://img.youtube.com/vi/H-bDew_o_LY/0.jpg)](http://www.youtube.com/watch?v=H-bDew_o_LY "Nao Daily Activities -1")

### Case 4: Intent: Work (positive tone), transition to Intent: Reading (positive tone), transition to Intent: Friends (positive tone)
[![IMAGE ALT TEXT](http://img.youtube.com/vi/WCAvr4k9p5Q/0.jpg)](http://www.youtube.com/watch?v=WCAvr4k9p5Q "Nao Daily Activities -3")

### Miscelleaneous Case to show longer more complex dialogue and transitions: Using Pyaudio to showcase 1) work (negative tone), friend (positive tone),reading (negative tone) transition and 2) friend (negative tone), work (positive tone),and reading (positive tone) transitions. 

[![IMAGE ALT TEXT](http://img.youtube.com/vi/k_6R5DoCLJY/0.jpg)](http://www.youtube.com/watch?v=k_6R5DoCLJY "Pyaudio version")

[![IMAGE ALT TEXT](http://img.youtube.com/vi/wk5cIakvZYg/0.jpg)](http://www.youtube.com/watch?v=wk5cIakvZYg "Pyaudio version")




## FUTURE WORK
  * Integrate Machine Learning + Deep Learning skills to generate more inteligent responses
  * Improve the speech detection on Nao
  * Integrate multiple modalities (facial recognition/sensor technologies to enhance user experience)


 [View project details including hardware/software requirements, flow designs, entity/intent lists on github here.](https://github.com/vnoelifant/msr-final-nao)

### Find weekly status notes for my project in this [PROGRESS](https://github.com/vnoelifant/msr-final-nao/blob/master/PROGRESS.md) section.

## UPDATES

**NOTE** Following graduation of the MSR Program September 2019, the Cozmo Robot was used to replace Nao, as the Nao robot cannot be rented in the USA. Please refer to the "Cozmo" folder [here](https://github.com/vnoelifant/msr-final-nao/tree/master/cozmo) for up-to date code and enhancements on the Cozmo robot. The Cozmo Robot does not have a microphone, so a recording application was written to utilize PyAudio as the recorder for speech. As a note, the PyAudio recording is shown to be much more accurate than the recorder used from the Nao Robot. 

## COZMO DEMO VIDEOS

Coming Soon






 



