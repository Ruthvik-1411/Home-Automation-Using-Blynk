# Home-Automation-Using-Blynk
Just a basic Home Automation project using Node MCU, Relay Modules, Blynk app and its Libraries.<br><br>
<b>Components Used:</b>
<li>Node MCU(ESP8266 any version)
<li>5V 10A Relay Module 
<li>Jumper wires
<li>Blynk APP: <a href="https://play.google.com/store/apps/details?id=cc.blynk&hl=en_IN&gl=US">Blynk</a>
<li>Library( you can type Blynk in google and download the library from github): <a href="https://github.com/blynkkk/blynk-server">blynk-library-master</a>
<li>Devices that work in home (led bulbs, Fans etc)
<br><br>
By using the working of Relay modules we can control the devices that are connected to the internet using Node MCU and the blynk app.
What I did here is that I installed the blynk library that allows users to upload the predefined code examples on Node mcu and connect the device to the server.<br>
In the Blynk app one can create their projects easily with switches and many more features. Once registerd on the app you get a auth token that can be used by you anytime you connect that device. By simply entering this auth token, wifi name and password the device can be operated through the app over the internet.<br>
By tapping the switches on the app the voltage levels of the Node MCU's pins can be manipulated. This can then be used to turn ON/OFF the appliances that are connected through
the Relay.<br><br>

<b>Working of Relay</b><br>
Relays are most commonly used switching devices used in electronics. They can be used to switch high current loads easily unlike transistors which are limited by the maximum current that can flow through them and also can’t switch AC loads. A 5V 10A Relay Module can switch both AC and DC loads. It is an Electromagnetic switch, when the coil inside is energized with a small current, it can switch ON or OFF the high current circuit. It has PCB screw terminals to directly connect. They can be used in Home automation to switch ON or OFF the appliances, in Electronic circuits to perform switching operations, in safety circuits to disconnect or connect the heavy loads in case of any dangerous situation, in Automobile applications like turning on windscreen wipers, power windows fuel pump, cooling fan etc.<br><br>
<img src="https://github.com/Ruthvik-1411/Home-Automation-Using-Blynk/blob/main/Relay-Module_600x600.jpg"><br>
First connect the input pins to the board i.e. Vcc to 5V/3.3V supply, Gnd to Gnd and the Input pin to any GPIO pin. Now the Input pins recieves a signal from the Node MCU board.
It can recieve a High or Low depending on the operation.<br>
There are two ways you can use a Relay. The Load is connected or disconnected when the Relay is working i.e. when it recieves a signal.<br> 
Let us assume a dc motor as our load. So, we have +ve, -ve of motor and a battery(9V) with +ve, -ve terminals. To understand the working of Relay, Let us connect the +ve terminals 
of motor and battery directly. Now, we only have two -ve terminals. Connect the -ve terminal of the battery to the Common(middle socket) of the relay. Now let us say we gave the 
Relay signal as LOW. The light on Relay is on. Now if we connect the -ve terminal of dc motor to the Normal open(Right in the pic) the motor works. When the same wire is connected to other terminal it doesnt operate.<br>
The other way is to connect the -ve terminal of the motor to Normally closed(Left in the pic) and give a signal HIGH to Relay. It works and if connected to other terminal it doesnt operate.<br>
In a nutshell, It is just like a switch and its operation can be controlled using the signal pin from GPIO pins on the boards like Arduino Uno, Mega, Node MCU etc.

  <b>Demo:</b> <a href="https://drive.google.com/file/d/1G6nYSn1oq_ZSCiegJK6c5PXyeWOtGuO0/view?usp=sharing"> Link</a>
