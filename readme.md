virtualenv arduino-env

source arduino-env/bin/activate

-----------------------------------------------------

pip3 install pyfirmata (in environment use pip)

---------------------------------------------------

sudo adduser $USER dialout (sometimes not neseccary)

run "groups" in terminal

or groups name_of_the_os

ls /dev/tty*

find the name of the usbport (for example /dev/ttyUSB0 or dev/ttyACM)

run python ard-python.py or python3 ard-python.py

if says permission denied 


sudo chmod 777 /dev/ttyUSB0


before doing all of these first open arduino IDE file > examples > firmata > standartfirmata and upload that to the arduino then run the python script (ard-python.py)
