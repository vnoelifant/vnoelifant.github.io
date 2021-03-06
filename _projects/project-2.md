---
layout: project
title: Real-Time Multimodal Signal Processing
date: May 2019
image: /public/images/ssi.jpeg
---

## Overview
In this project, I developed a Python application to process multimodal signals (physiological with audiovisual), into [SSI](https://github.com/hcmlab/ssi) (Social Signal Interpretation) pipeline. In addition, a set of tools called [emovoice](https://github.com/hcmlab/emovoice) was used in conjunction with the multimodal signals which built a real-time emotion recognizer based on acoustic properties of speech (not using word information). Sensors include the following:

  * **GSR (Galvanic Skin Response)**
    * Refers to changes in sweat gland activity that are reflective of the intensity of our emotional state, otherwise known as emotional arousal.
  * **PPG (Photoplethysmography LED Pulse Sensor)**
    * Uses a light-based technology to sense the rate of blood flow as controlled by the heart’s pumping action
  * **ECG (Electrocardiography)**
    * Measures  the bio-potential generated by electrical signals that control the expansion and contraction of heart chambers
  * **EEG (Electroencephalography)**
    * An electrophysiological monitoring method to record electrical activity of the brain.
  * **EEG with PPG**
  * **EEG with GSR**
  * **EEG with ECG**
  * **EEG with PPG, GSR**
  * **EEG with ECG, GSR**
  * **EEG with PPG, GSR**
  * **EEG with PPG, GSR, and Audio-visual**


## Motivation
My Career goal in Robotics is to improve the lives of people, and a large part of that is figuring out how computers can reliably detect emotion. Many studies have been done on facial emotion recognition, yet more modalities should be explored, considering we, as humans express emotion in various ways. I believe one of those ways of vast importance is by means of physioligical signals, such as EEG (brain wave signals), ECG, and PPG (heart rate signals), in addition to combining these modalities with audiovisual cues and voice emotion detection. This project explores the initial phase of processing such signals real-time into a social signal processing pipipline (as part of the SSI social signal framework) to support future steps in fusing the signals to eventually detect one's emotional state real-time. The fact that the signals are sent real-time has the potential to solve challenges in prior emotion detection algorithms which rely only on past data, and hence, lower reliability. Thus, I have hope for a future whereby robots can be capable of receiving these multimodal real-time signals and have the potential to save lives.


## Demo videos:

EEG with PPG, GSR AND AUDIOVISUAL, PLUS VOICE EMOTION DETECTION!
Detecting "disgust, sadness and boredom" in voice
[![IMAGE ALT TEXT](http://img.youtube.com/vi/Dq9SbwqZvRY/0.jpg)](http://www.youtube.com/watch?v=Dq9SbwqZvRY "Using Emovoice (detecting disgust, sadness, and boredom)")

EEG with PPG, GSR AND AUDIOVISUAL, PLUS VOICE EMOTION DETECTION!
Detecting "happiness" in voice
[![IMAGE ALT TEXT](http://img.youtube.com/vi/3vu2Bpd8vng/0.jpg)](http://www.youtube.com/watch?v=3vu2Bpd8vng "Using Emovoice (detecting happiness)")

EEG with PPG, GSR AND AUDIOVISUAL:          
[![IMAGE ALT TEXT](http://img.youtube.com/vi/DqONgXAobW8/0.jpg)](http://www.youtube.com/watch?v=DqONgXAobW8 "EEG,ECG,GSR Signals on SSI")

EEG with PPG, GSR:
[![IMAGE ALT TEXT](http://img.youtube.com/vi/vY3h6-k4f7I/0.jpg)](http://www.youtube.com/watch?v=vY3h6-k4f7I "EEG,PPG,GSR Signals on SSI")

EEG with ECG, GSR:
           
[![IMAGE ALT TEXT](http://img.youtube.com/vi/tBMmrahfTf8/0.jpg)](http://www.youtube.com/watch?v=tBMmrahfTf8 "EEG,PPG,GSR, VIDEO Signals on SSI") 

 [View project details on github here.](https://github.com/vnoelifant/Custom_SSI_Sensors/tree/master/heart_skin_brain)
