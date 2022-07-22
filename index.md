# Home automation using Particle and Amazon Echo
I worked on creating a new skillset for Amazon Echo and connecting the Particle through exploring AWS lambda and Alexa developer console. I was able to familiarize myself with AWS and Alexa developr console through troubleshooting and researching many problems I encountered. The main purpose of this project is to use voice commands to enable Alexa's skill called Particle, which can turn on red and green LED lights and read the temperature and humidity using the sensor. 

| **Engineer** | **School** | **Area of Interest** | **Grade** | 
|:--:|:--:|:--:|:--:|
| Ruth Liu | Notre Dame San Jose | Computer Science | Rising Senior

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLUh8qhS4NzOG9tUWkbQ9gORu_601OH5UTQKOygAWpTqYn7YNwuNvdT7Fu_-tNHmBTvKDun_m_u1L1MqIQufEedvrbXpiSkXRbMuemDnIVJpjQ2gHirrS0kUFrk6aWoT_zApBhrf5oEc7U4H4FrAbnDz=s1474-no?authuser=0)
  

# Final Milestone
My second milestone was to add a sensor that could read the humiditiy and the temperature to the Alexa skillset Particle. For this milestone, I added the sensor to the breadboard. While adding the sensor, I continously tested the LED lights as well to check the code and wiring at least still worked for my first milestone. While working with the humidity sensor though, I had to make sure Alexa understood the voice command and the sensor, and also check the code worked. When first working with the humidity sensor, it would read "undefined" when asked for the temperature or humidity percent, or it would read "0 percent/degrees fahrenheit". My instructors worked with me to look through the code for errors and also look through past students code. After changing the wiring and editing the code, Alexa was finally able to read the sensor's humidity and temperature correctly. 

[![Second Milestone](https://i3.ytimg.com/vi/6RwTehvNrl4/maxresdefault.jpg "Second Milestone")](https://youtu.be/6RwTehvNrl4){:target="_blank" rel="noopener"}

# First Milestone 
For my first milestone, I worked on setting up the Alexa skillset through AWS Lambda, Alexa developer, and the photon particle device. The goal of this milestone was to have Alexa be able to perform the function of enabling the LED lights, which I wired according to the schematic attached below. After setting up the skill on AWS Lambda, I had to connect that to the Alexa developer skill named Particle. Then I connected the photon particle device by attaching the device ID of the photon to the Lambda code. It took me about four weeks to complete my first milestone due to troubleshooting the Lambda code and function, Alexa sample utterances and code, as well as the photon particle code and setup. At times it was also difficult to work with the photon device because it had difficulty connecting to the wifi, which meant the code could not flash onto the photon. I also was unfamiliar with all these platforms in the project, so while troubleshooting I also learned how to work with the different platforms. Fortunately, in the end I was able to have Alexa enable the LED lights using voice command. I also soldered headers onto the particle device for it to be placed securely on the breadboard.

Wiring Schematic:
![image](https://user-images.githubusercontent.com/107577690/179088286-31ebdc73-07f3-4f33-8303-3e43c799b45c.png)

[![First Milestone](https://i3.ytimg.com/vi/CpklxW3Em7s/maxresdefault.jpg)](https://youtu.be/CpklxW3Em7s){:target="_blank" rel="noopener"}

# Starter project 


My starter project is the Simon says game, in which the game will light up the 4 buttons in a certain order and the user must press the buttons in that order. The project includes parts such as LED lights, battery clips, a resistor, and switches, some being soldered on and screwed on. To play the game, turn the power switch on and press a random button. Then the buttons will light up in different orders one by one. There is also a sound switch that enables a different sound for each button when it is turned on. 

[![Starter project](https://i3.ytimg.com/vi/rwoCWAUw_jQ/maxresdefault.jpg "Starter Project")](https://youtu.be/rwoCWAUw_jQ){:target="_blank" rel="noopener"}
