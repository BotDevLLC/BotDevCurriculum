<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/Botdev.png height="98" width="392">

# VITAL INFORMATION
**Subject(s):**  Robotics

**Topic or Unit:** Communication with the STEMBot

**Grade/Level:** 5th-12th

**Time Allotment:** 30 minutes

**Standards:**           3.4.5. A3. Identify network communication technologies

3.4.6. D2. Use computers appropriately to access and organize and apply information 


  3.4.7.E4.  Illustrate how information can be acquired and sent through a variety of technological sources, including print and electronic media.  
  
  15.4.12.F. Compare and contrast network environments, including the function of network devices and connectivity issues.
  
**Unit Goal(s):**
1.	Understand what VNC Viewer is and the purpose of it
2.	Understand internet protocol addressing (IP Address)
3.	By the end of lesson, students will be able to utilize VNC to remotely operate the raspberry pi

**Objective(s):**
1.	To be able to follow steps to install VNC Viewer 
2.	Connect to the STEMBot through a reliable internet connection
Assessment(s):   
1.	Open a LibreOffice Write (word) document on the desktop of a Raspberry Pi.  Have each student connect to the Raspberry Pi via VNC and write their name on the document.  Be prepared, more than one person may edit the document at once, so antics will ensue.    


# INSTRUCTIONAL PROCEDURES 
  ## A.	Anticipatory Set: 
  The Raspberry Pi is a low cost, credit-card sized computer that plugs into a computer monitor or TV and uses a standard keyboard and mouse. We can use a Virtual Network Computing (VNC) connection to connect to the Raspberry Pi, so that the Raspberry Pi does not need a monitor or keyboard. If a computer doesn’t have its own monitor, and input devices (such as a keyboard) we call it a “headless client.”  Using a VNC to turn another computer into the monitor and keyboard of the Raspberry Pi, we will use it as a headless client. Remeber, that IP addresses can change and you may need to repeat this step every time you connect if you don't assign a static IP address to your Raspberry Pi. An alternative is to purchase an OLED disaply (like Adfruit's OLED display: https://www.adafruit.com/product/3527) that will display the Raspberry Pi's IP address every time you turn it on. A last option is to use a network scanning app like fing on your cell phone to find your Raspberry Pi and its IP address (see below).
  
  ## B. Body: 
This period of instruction is designed around a live demonstration. You may download the pdf file at the bottom to refer to during your demonstration. Before beginning both the Raspberry Pi and your host computer must be on the same internet connection!
1.	Plug in Raspberry Pi to monitor, keyboard and a mouse. Open the terminal by choosing Menu > Accessories > Terminal)

<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/pic%201.png>

2.	Type ipconfig to check the IP address of the Raspberry Pi

<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/pic%202.png>

3.	Check the IP address of the Raspberry Pi at the wlan0 part that shows inet followed by an IP Address... normally something similar to 192.168.1.101

<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/pic%203.png>

4.	Ensure that VNC is enabled on your Raspberry Pi.  Click on the raspberry logo in the upper left corner and select Preferences > Raspberry Pi Configuration.  Click on the second tab in the window that pops up and make sure that the radio button next to Enable to the right of VNC is selected.

<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/pic%204.png width="980">


5.	On the computer you will use to connect to your Raspberry Pi download Real VNC Viewer from your browser (https://www.realvnc.com/en/connect/download/viewer/) by clicking download VNC Viewer for Raspberry Pi and run the executable file

<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/pic%205.png>

6.	Run the executable file to install the program on your device. Open the program once completed.

<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/pic%206.png>

7.	Enter the IP Address of the Raspberry Pi in the VNC Viewer at the top bar to connect to it. You will be prompted to enter a username and password. Raspberry Pi default username and password are:

Username: pi
Password: raspberry

<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/pic%207.png>


8.	An alternative to using ifconfig to get its IP address -which requires a monitor and keyboard-, is to use the Smart Phone network scanning App like “Fing” that can be downloaded on the App store and Play store.  Simply connect your phone to the same Wi-Fi, open the app and scan the network.  Then look for your Raspberry Pi’s name and the IP address will be next to it.

<img src=https://raw.githubusercontent.com/BotDevLLC/BotDevCurriculum/master/Pictures/pic%208.png>



# MATERIALS AND RESOURCES
* Computers with internet connection
* HDMI cord
* STEMBot(Raspberry Pi)
* Monitor
* Keyboard and mouse
* <a href="https://drive.google.com/file/d/1ZucWqtv_8VQikrDmNA8B40afHh6HRREO/view?usp=sharing" target="_blank">Communicating with STEMBot</a>



