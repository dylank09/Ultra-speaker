# Ultra-speaker
I am currently building a system that detects if a person is walking away or coming back using ultrasound sensors and using this information, when a person goes away from the sensor (i.e. the speaker) the volume of the speaker will decrease and when the person comes back, the volume of the speaker will return to normal. 

******************************************************************************************
To explain the layout - in a room where there is music playing, this 'device' (the raspberry pi and sensors) will be set up facing the door of the room. It is assumed the person is in the room already. When the person crosses in front of the device and walks away from it i.e. out the door, the music will lower. Similarly when the person walks towards the device i.e. in the door, the music will return to normal volume.
******************************************************************************************

Scenario - A person hears someone knocking on the front door of their house. They leave the room where they have music playing. The person does not have to fiddle with a remote or their phone to turn down the volume - simply leave the room. Now the person isnt embarressed by the music as the volume is low and can also have a relaxed conversation with the person at the front door. 
I am using the raspberry pi's GPIO pins to connect the ultrasound sensors. 


The idea is to connect the system to the person's spotify account and control the volume of the spotify account. The reason for this is because it requires no physical connecting to the persons speaker. This makes the idea more portable.

**The python file will incorporate javascript to interact with spotify.
**The code so far is on the raspberry pi and i havent had the chance to upload it here.
