# ArduinoMediaController  
![Capture](https://user-images.githubusercontent.com/55280978/137301444-8ed637ee-f7ff-42fc-adc5-d74d866ff1f7.PNG)
<br/><br/>
<b>an arduino project in cpp and python for media control.  
project done by shai ely and uri koren from sapir academic college.</b>  


<h2>what you need for this project:</h2>  
* arduino uno   
* 2 ultrasonic sensors   
* 1 light dependent resistor  
* some cables  
* matrix  
* some tape  



<h2>project gestures:</h2>
1-10 cm from the ultrasonic: right sensor run media forward, left backward.  
<br/>
10-25 from the ultrasonic: right sensor turn volume up, left sensor turn volume down.  
<br/>
both hands together 30-50 cm from both ultrasonics: pause or start a media.  
<br/>
both hands together 5-20 cm from both ultrasonics for 3 seconds: exit the media.  
<br/>
changes screen brightness based on the light in the room - lowlight = low brightness, highlight = high brightness.  
<br/>
   

<h2>Libraries in used:</h2>
serial  
<br/>
pyautogui  
<br/>
screen_brightness_control  
  
