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
Relays are most commonly used switching devices used in electronics. They can be used to switch high current loads easily unlike transistors which are limited by the maximum current that can flow through them and also can’t switch AC loads. A 5V 10A Relay Module can switch both AC and DC loads. It is an Electromagnetic switch, when the coil inside is energized with a small current, it can switch ON or OFF the high current circuit. It has PCB screw terminals to directly connect. They can be used in Home automation to switch ON or OFF the appliances, in Electronic circuits to perform switching operations, in safety circuits to disconnect or connect the heavy loads in case of any dangerous situation, in Automobile applications like turning on windscreen wipers, power windows fuel pump, cooling fan etc.<br>
  
