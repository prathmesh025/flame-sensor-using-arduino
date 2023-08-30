# flame-sensor-using-arduino
![image](https://github.com/prathmesh025/flame-sensor-using-arduino/assets/110836616/f1039cf1-46c9-4c1b-b94e-79e80613a557)


Flame detector Using Arduino
FIRE is a small world but causes many disasters every year in many parts of the world. Like forest fires in amazon are very common we couldn’t stop them completely but take some preventive measures to control them so today we are going to make a fire alarm that will detect even small fires within an acceptable range of sensors. for that, we are making a flame detector using Arduino. Most of the buildings are now built with a fitted flame sensor along with an automatic water pump sprinkler which turns on whenever the sensor detects a fire, also many advanced cars also now come with the inbuilt flame sensor in case the car catches fire.

The sensor we are using today to demonstrate the flame sensor working is very simple and easy to available in the market but there are many more advanced sensors available in the market which can be used in professional projects as it may yield better results.

how does a Flame detector using Arduino works?

The components we use are always basic ones like Arduino UNO, LED’s, buzzer, and of course a flame sensor which is the most important thing in today’s DIY section. So, let’s discuss the sensor, as always, this sensor is built out of LM393 IC which is most common in various sensors available in the market due to its voltage comparator and amplifier. The working of this flame detector Arduino is almost similar to that of IR sensor interface but there is a difference instead of IR light emitted by IR emitter led it detects the IR light coming out the fire which is then amplified and digital and analog signal id then send to the microcontroller to do further processing.

The sensor also has an onboard power led and also an onboard Status led which will blink whenever the sensor detects fire in its nearby environment


The sensor gives both digital and analog output. The difference between the two is explained by me in many articles previously uploaded it you haven’t read them just go for it. The amount of amplification can be adjusted with the help of potentiometers given on the sensor PCB



*NOTE: – THE SENSOR VALUES DEPEND ON THE DISTANCE OF THE SOURCE TO THE SENSORS AND MAY VARY ON DISTINCT SOURCE FROM FIRE.
FEATURES AND APPLICATIONS: –

Sense of fire is very accurate and fast
Small body and easy to fix
Adjustable value
Low price
Used in almost every fire-related project to avoid disasters
