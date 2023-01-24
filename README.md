# DuckyPi
 Making BAD USB from Raspberry Pi Pico

Instructions to Make Pico USB Rubber Ducky:

 - Connect the Raspberry Pi Pico to your PC and wait for it to be shown as mass storage
 - Copy the circuit python file 'adafruit-circuitpython-raspberry_pi_pico-en_US-7.3.3.uf2' for Raspberry Pi Pico form the Source files folder given in the repository
 - After the file has been copied, the Raspberry Pi Pico will reconnect again to the PC and will have some python code inside it.
 - Now copy all the files in the lib folder of this repository to the lib folder in the Raspberry Pi Pico 
 - Copy the file "duckyinpython.py" from the Source files folder to your Raspberry Pi Pico, which converts the ducky scripts to python scripts to run on Raspberry Pi Pico.
 - Delete the file named "code.py" inside the Raspberry Pi Pico and change the name of the file you copied onto the Raspberry Pi Pico from "duckyinpython.py" to "code.py".
 - After the process is finished whenever the Raspberry Pi Pico is connected to the PC it will run the code.py file which will deploy your ducky script onto the PC.
 - To make the ducky script fo your Raspberry Pi Pico you first need to get a ducky script or make your own ducky script if you want to.
 - Once you have the ducky script that you want to deploy, open the text editor and copy the ducky script on the text editor and save it as "payload.dd". Remember to save it as .dd extension.
 - WARNING! you have to be careful since the raspberry Pi Pico will run the ducky script as soon as it is copied so you must unplug it immediately.
 - Now your Raspberry Pi Pico is successfully converted to a BAD USB Device.

Insrructions for Resetting Raspberry Pi Pico:

 - If you want to change the rubber ducky script that is on the Raspberry Pi Pico or just want to reset the Raspberry Pi Pico to its original state.
 - Connect the Raspberry Pi Pico to the PC while holding down the "BOOTSEL" button. It will connect the Raspberry Pi Pico in the same state as it was the first time we connected the Raspberry Pi Pico.
 - Download the python script file called "Nuke" form the link "LINK HERE" that basically Factory Resets your Raspberry Pi Pico.
 - Follow the above procedure again to deploy your new ducky script file

NOTE:
 I have added all the source code materials that I have used to program my Raspberry Pi Pico to a BAD USB. You can just copy and paste those files.
