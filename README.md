# TASK 1 3D PRINTING:
**Objective :**\
To understand the working of 3D printer, from online sources. To learn about the Bed temperature and other priner settings.\
**Learnings and Outcomes :**\
Optimal PLA Printing Settings\
### ​Nozzle Temperature:
For most PLA filaments, the ideal nozzle temperature is between 190°C and 220°C. Starting at 200°C is a good baseline, but you can adjust based on the specific brand and color for the best results.
### ​Bed Temperature:
 While PLA can be printed on an unheated bed, using a heated bed set between 50°C and 60°C is highly recommended to improve first-layer adhesion and prevent the corners of your print from lifting (warping).
### ​Printing Speed:
A standard printing speed of 40-60 mm/s provides a great balance between print time and quality. For outer walls or highly detailed sections, slowing down to 20-30 mm/s can significantly improve the surface finish.
### ​Cooling Fan:
After the first one or two layers, your part cooling fan should be running at 100%. Proper cooling is essential for PLA to harden quickly, which allows for sharp details, clean bridges, and steep overhangs.
### ​First Layer Settings:
To ensure a successful print, make the first layer slightly slower and thicker than the rest. A common practice is to set the first layer speed to 20 mm/s and the layer height to 0.3 mm for excellent bed adhesion.
### ​Post-Printing Procedures:
Once your print is complete, parts can be finished in several ways. PLA can be easily sanded for a smooth surface, primed and painted with acrylics, or joined together using cyanoacrylate (superglue) or a two-part epoxy.
# TASK 2 API
**Objective :**\
Using any API of your choice, build a user interface (web app, mobile app, etc.) to make calls and display information.\
**Learnings and Outcomes:**\
I got to know about APIs(Application Programming Interface). An API, or Application Programming Interface, is a set of rules that allows different software applications to communicate with each other.It acts as a mediator, basically just like restaurant. I have built a weather app using html.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/357939d86049706683d0f72b3125590dc66adb4f/Screenshot%202025-09-09%20213650.png)\
[click here](C:/Users/Tejashree/Desktop/weather%20app/demo/marvel.html) for the website\
[click here](https://github.com/tejashreehn610-blip/weather-app) for the github repository\
[click here](https://youtu.be/XddakVvYfsY) for the video.

# TASK 3 WORKING WITH GITHUB:
**Objective :**\
Familiarize yourself with GitHub integrated workflows such as GitHub Actions, Issues, and pull requests. Visit the provided git repository and perform the tasks stated in the README file.\
**Learnings and Outcomes :**\
1.I have learnt how to fork the given repository to my repository\
2.I have familirised myself with basic github opreations like: 1.Branches 2.Forking 3. Pull requests\
3.I have learnt how to create and delete repositories\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/c4d78a1f0d2fea739a4d63f6692922fbba202d57/Screenshot%202025-09-09%20232330.png)
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/969aa6010dfc501122155300ff20159edd7e2844/Screenshot%202025-09-09%20232213.png)\
[click here](https://github.com/tejashreehn610-blip/git-task) click here to see the changes i have done.

# TASK 4 COMMAND LINE ON UBUNTU:
**Objective :**\
 Get familiar with Command lines on Ubuntu\
**Procedure:**
1) 'mkdir' to create folders.
2) 'cd' to navigate directories.
3)   'touch' to create blank files.
4)    'ls' to list files.
5)  create multiple folders efficiently using loops.
6)  'cat' to concatenate text files.\
   Using these basic commands, I completed the subtasks.\


**Outcomes :**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/8250987a2399b2b653b4e3e164dd0fefb2c7b21f/Screenshot%20from%202025-09-03%2016-42-24.png)
# TASK 5: LINEAR REGRESSION FROM SCRATCH
**Objective :** Dive into the core of machine learning by implementing Linear Regression from scratch using , and compare its performance with the scikit-learn implementation. Use the California Housing dataset to evaluate your model on real-world data.\
**Learnings and Outcomes :**
Linear Regression is a machine learning algorithm used to predict continuous values based on given input data. It assumes a linear relationship between the dependent variable (output) and independent variables (inputs). The equation for a simple linear regression is:
### y=mx+b
Where ,y is the predicted value,m is the slope(weight in linear regreesion),x is the input values.\
Linear regression is commonly used in predicting house prices, sales forecasting, and risk analysis.\
To measure how well the model is performing, error metrics are used. The Mean Squared Error (MSE) calculates the average of the squared differences between actual and predicted values:\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/b9dcbd6bf5b1199b23f4b1d9cfb03d861c1a0b7a/WhatsApp%20Image%202025-09-15%20at%203.47.40%20PM.jpeg)\
Similarly, the Mean Absolute Error (MAE) calculates the average of the absolute differences:\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/0f63ed6480a615dd27db313daa8f53f25f965480/WhatsApp%20Image%202025-09-15%20at%203.51.14%20PM.jpeg)\
Here yi is the actual value ,other one is predicted value and n is the total number of data points.\
To make the model accurate,gradient descent is used to minimize the error by adjusting the slope(weight) and intercept.formula for gradient descent is,\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/5dbae6b9c5e6b19aba1562ae807e7b5811904159/WhatsApp%20Image%202025-09-15%20at%203.54.42%20PM.jpeg)\
Where,alpha is the learning rate controls the step size. By continuously updating these values, the model finds the line of best fit, which gives the most accurate predictions.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/55543666263be906aa9fdaca197b7b6cb831c0e7/Screenshot%202025-09-15%20140253.png)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/a4354d6457fee3eb4cdaabb4e85e89ede40b58fc/Screenshot%202025-09-15%20140336.png)\
Here is the github link[click here](https://github.com/tejashreehn610-blip/LINEAR)
# TASK 6 THE MATRIX PUZZLE :
**Objective :**\
 Get hands-on with NumPy and Matplotlib by solving a visual puzzle. You’ll be given a scrambled matrix, and your mission is to decode it into a hidden image using NumPy operations and visualization techniques.\
 **Learnings and Outcomes :**\
 I loaded a flattened NumPy array, used reshape() to reconstruct it into a square 2D image, then applied np.fliplr() to horizontally mirror that half and reconstruct the full face, and finally displayed the complete image with matplotlib.pyplot.imshow() in grayscale—leveraging NumPy’s efficient reshape and flip routines to uncover the hidden picture.\
 ![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/fed2b8bdb90ed9fb5799c2a9c56ff9caeac1eecf/WhatsApp%20Image%202025-09-15%20at%204.11.55%20PM.jpeg)\
here is the repository[click here](https://github.com/tejashreehn610-blip/task-6)

# TASK 7 CREATE A PORTFOIO WEBPAGE:
**Objective :**\
Create a website to showcase your portfolio, including information about yourself, interests, projects, and social media profiles. Ensure the site is responsive and pushed to a git repository. Use any CSS framework of your choice.\
**Outcomes :**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/c74d0671bcd426af621ad1a31fe52baf50cb8345/Screenshot%202025-09-03%20000839.png)
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/951a562f3e737181a4060c23ac99578bc9c4c848/Screenshot%202025-09-03%20000905.png)\
[click here](https://github.com/tejashreehn610-blip/Website-Portfoio) to view the files I used for making my webpage.
# TASK 8 WRITING RESOURCE ARTICLE USING MARKDOWN:
**Objective :**\
 Write a technical resource article on a particular use case or application of UAVs.\
 **Learnings and Outcomes :**\
 I wrote a resource article on miami international airport.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/bd61464ab49fbf05b420bf55a2ba2bd847b7cc46/Screenshot%202025-09-10%20214121.png)
[click here]()to see my resourse article.
# TASK 9 TINKERCAD 
**Objective :** \
Create a Tinkercad account and familiarize yourself with the application. Simulate a simple circuit using an ultrasonic sensor to estimate the distance between an obstacle and the sensor, and display the results on the serial monitor. Create a radar system using an ultrasonic sensor and servo motor to detect objects within a certain range.

**Procedure :**\
Components for the task\
![image](https://github.com/tejashreehn610-blip/Level-0-Report-/blob/main/Screenshot%202025-09-08%20220624.png?raw=true)\
 The circuit connections \
 ![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/a78d30d4144f5a0c2a9bf785eb460b14ab51a652/Screenshot%202025-09-10%20144150.png)\
The look after the connection:\
![image](https://github.com/tejashreehn610-blip/Level-0-Report-/blob/main/RADAR%20PROJECT%20(1).png?raw=true)\
**Learnings And Outcomes :**\
1.Working of the Ultrasonic sensor:\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/8b4ac8082fa9b35a2478b576a3dea549f6cf93b4/Screenshot%202025-09-08%20230232.png)\
Ultrasonic sensor works on the prinviple of ECHOLOCATION\
It uses sound waves that are "ultra" sonic, meaning they are at a frequency higher than humans can hear (typically above 20 kHz).
1.Transmission: The transmitter component of the sensor emits a short burst of ultrasonic sound waves. These waves travel outward in a cone-like shape.
2.Reflection: When these sound waves encounter an object in their path, they bounce off its surface.
3.Reception: The reflected waves, or "echoes," travel back towards the sensor and are detected by the receiver component.\
To know the distance between the target and the sensor, the sensor calculates the amount of time required for sound emission to travel from transmitter to receiver. The calculation is done as follows:
D=T*c/2\
where, ‘T’ corresponds to time measured in seconds,
'c' corresponds to speed of sound= 343 m/s\
**2.** About Servo motors and RADAR Technology :\
A servo motor is a motor that provides precise angular control, allowing it to rotate to and hold a specific position using feedback. Radar (RAdio Detection And Ranging) uses radio waves to detect objects by transmitting a signal and analyzing its returning echo.\
[click here](https://www.tinkercad.com/things/48JWag3EfnV-radar-project/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard) to view my Tinkercad circuit.
# TASK 10 SPEED CONTROL OF DC MOTOR:
**Objective :**\
Understand the control DC motors using the L298N motor driver and the Arduino board. Using an UNO and H-Bridge L298N motor driver, control the speed of a 5V motor.\
**Procedure :**\
I basically followed this circuit connections\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/f17f2ffcd424e1cef33dcb2d3c09e7a0c5ae94f2/Screenshot%202025-09-10%20230740.png)\
**Learnings and Outcomes :**\
First i learnt about the output, input and enable and power pins of L298N motor driver .I learnt about which pins control speed and which control direction.I also learnt about the pins of potentiometer.I familiarized myself withe the concept of PWM and duty cycle.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/65517efbfaa9c7f2c868b410c16c8a7386f92e61/WhatsApp%20Image%202025-09-10%20at%2011.33.48%20PM.jpeg)\
[click here](https://youtu.be/yNliG-abd-c) for the video.
# TASK 11 LED TOGGLE USING ESP32:
**Objective :**\
Learn how to use an ESP32 to create a standalone web server that controls an LED connected to the ESP32 GPIOs. Use the Arduino IDE to code and upload the program to the ESP32.\
**Procedure :**\
At the first I made the connections as shown in the below image , the required components are 2 LEDs,ESP32,breadboard, and two 330ohm resistors.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/60561b2f721366044b1b69de4b1666bc09e8afe4/Screenshot%202025-09-10%20221248.png)\
and then i copied the required code to Arduino IDE,and entered the mobile hotspot credentials into the code.And then the IP address will occure later ,from IP address we can controle led,then  i pasted the IP address to the browser and finally togelled the LED's.\
**Learnings and Outcomes :**\
The image of the circuit i did in lab is shown below\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/430c388694be6b4d1d413c31e67c916d87a2e4fe/Screenshot%202025-09-10%20223042.png)\
[click here](https://youtube.com/shorts/ncnqwEzJ6w4) for the video .
# TASK 12 SOLDERING PREREQUISITS:
**Objective :**\
To Learn about the soldering equipment and perform basic soldering on a perf board, for example a LED circuit.\
**Learnings and Outcomes :**\
I have soldered the resistor. I inserted the resistor leads through the holes of the perf board. And then after heating the soldering gun i placed it at the hole where the resistor was inserted and then by feeding solder wire into the joint the soldering was completed .And then checked that a stronger solder is formed or not . \
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/d445d0e2f28ca36ebf3d8e8f78807903883e6ec0/Screenshot%202025-09-10%20154833.png)

# TASK 13 DESIGN A 555 ASTABLE MULTIVIBRATOR:
**Objective :**\
Design a 555 astable multivibrator with a duty cycle of 60%. Assemble the circuit on a breadboard and observe the output on a Digital Storage Oscilloscope (DSO).\
**Procedure :**\
1.One 6kΩ Resistor\
2.One 12kΩ (6+6)kΩ Resistor\
3.One 555 IC timer\
4.Two 10*10^2 nF capacitors\
5.One VRPS- 5V\
connections are made as shown below ![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/9d34f125439df1bf01136cd049cc2435abccd200/WhatsApp%20Image%202025-09-11%20at%2012.07.39%20AM.jpeg)\
**Learnings and Outcomes :**\
I have learnt about the duty cycle,i.e.,r1*r2/r1+2r2*100%\
I have learnt about the 555 timer\
Got the output as 59.74% duty cycle\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/024164c9f9f6f178e60349aa7fc1539ead871b83/WhatsApp%20Image%202025-09-02%20at%205.41.45%20PM.jpeg)
[click here](https://youtu.be/2mI0-PqMqyQ)to check the video porformed in the lab.
# TASK 14 ACTIVE PARTICIPATION:
**Objective :**\
Participate in any technical event, inter-college or intra-college, and submit the issued certificate of participation.\
**Participation :** \
I have participated in the KAGADA 20 poster presentation.The topic was **A PLANET OF PROGRESS...AND TRASH**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/af97d43f887eb1aceb40c1a58599c7d60c87ebb6/WhatsApp%20Image%202025-09-11%20at%2012.31.14%20AM.jpeg)


# TASK 15 INTRODUCTION TO VR:
**Objective :**\
 Familiarize yourself with what Virtual Reality is. Make a detailed study about what's the difference between VR and AR. Mention about the trends in the space and technology stack being developed.\
**Learnings and Outcomes :**\
I experienced the VR for the first time in the MARVEL Lab. It was a marvelous experience. I even played some games in VR.\
[click here](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/37071faaed627e07da4057c737d2c6a00e688d92/WhatsApp%20Image%202025-09-08%20at%204.18.41%20PM.jpeg)to see the VR playing experience of mine.\
Here is the image of the report\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/6a05461207428c632ef01bfbd55d825f60e758cb/Screenshot%202025-09-11%20182626.png)
# DOMAIN SPECIFIC TASKS :
# TASK 1 HISTORY OF AVIATION :
**Objective :**\
To understand the history of aviation and the parts of planes and their technical names and the thought process behind the advancement in the aviation sector.\
**Learnings and Outcomes :**\
**History of Aviation**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/9e37d0febad6076b21cfd4be363c19244438f345/Screenshot%202025-09-11%20090134.png)\
at the first in the history of aviation kite is the thing which flew in the sky.\
1.Leonardo da Vinci: Representing the earliest conceptualizations of flight, with his drawings and notes on flying machines. This acknowledges the theoretical groundwork laid centuries before practical flight.\
2.The Wright Brothers: Depicting their monumental achievement with the first successful sustained and controlled flight of a powered aircraft in 1903, marking the true birth of aviation.\
3.World War I Aviation: Showcasing early military aircraft, highlighting the rapid advancements in aircraft design and usage during the Great War.\
4.The Golden Age & Commercial Flight: Illustrating the era of significant growth in aviation, leading to more reliable and widespread commercial air travel. The Concorde is featured here, symbolizing supersonic passenger flight.\
5.Jet Age & Space Exploration: Representing the modern era of powerful jet aircraft and the ultimate extension of human flight into space, with a rocket launching towards Earth.\
**Parts of a plane** \
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/b42e912b1788d8ed5c113f67ddec495e65318819/Screenshot%202025-09-11%20140855.png)\
# TASK 2 INTRODUCTION TO FLIGHT STIMULATORS:
**Objective :**
To Gain hands-on experience with fundamental drone maneuvers and understand the importance of maintaining line of sight while operating a UAV. Use a simulator to observe drone speed, range, and the rotation of axes, and tackle various flying challenges.\
**Learnings and Outcomes :**\
I have learnt the techniques to use real drone stimulator,learnt about the channels basically their are 4 channels they are:\
1.Throttle- upward and downward movement of drone , during upwards movement all the four motors equally.\
2.Yaw- rotates the aircraft left or right by increasing the speed of the two diagonal motors rotating in one direction and decreasing the speed of the other two diagonal motors.\  
3.​Roll- tilts the aircraft left or right by increasing the speed of the motors on one side and decreasing the speed of the motors on the other.\
4.​Pitch- tilts the aircraft forward or backward by increasing the speed of the rear motors and decreasing the speed of the front motors, or vice versa.\
I have played the game by using rds it was a mindblowing experiance, here are some of the gimplse of it \
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/e0549352ae4902734b62201d72a56acefbf1a49d/WhatsApp%20Image%202025-09-10%20at%206.17.37%20PM.jpeg)\
[click here](https://youtu.be/qyZrHjdZ8qk) for the video. And even i understood about quadcopter and hexacopter.
# TASK 3 FLYING THE AIRBLOCK DRONE:
**Objective :**\
 To learn about and operate the Airblock Drone available in the lab.  \
**Learnings and Outcomes :**\  
### AIRBLOCK 
The Airblock is presented as a revolutionary educational drone from Makeblock, designed to be easily built, programmed, and reconfigured. Its core concept revolves around modularity and accessibility, aiming to make programming and robotics engaging for everyone, especially beginners and children. The drone is constructed from magnetized, modular pieces that can be assembled and disassembled without any tools.\
**The things inside the block**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/c0d39aa57b519c76b3755e536f4a4ad51fafb451/WhatsApp%20Image%202025-09-11%20at%203.11.48%20PM.jpeg)\
 The modular block system allows multiple shapes as shown below:\
 ![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/5813182e0087d11803f95c2d9744b9aa7d549493/WhatsApp%20Image%202025-09-11%20at%203.10.43%20PM.jpeg)\
 Breakdown of the Modes\
1.​Drone Mode: This is the standard hexacopter (six-rotor) configuration for flying.\
2.​Hovercraft Mode: The rotor modules are attached to a base, transforming it into a vehicle that can glide over smooth surfaces like the floor or even water.\
3.​Triangle Mode: A simpler, three-rotor flying configuration.\
4.​Spider Mode: A creative, land-based assembly that demonstrates the system's flexibility.\
The below image shows the full inner structure of the Airblock Drone:\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/183ddc4d077e0b599d70124f425bc2d19f6ae8b4/WhatsApp%20Image%202025-09-11%20at%203.11.15%20PM.jpeg)\
[click here](https://youtu.be/flowvjD99Vw) to check out the video.\





