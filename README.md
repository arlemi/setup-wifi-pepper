# How to setup Pepper when arriving at a new venue

Pre-requisites:

- a Pepper robot (duh)
- Choregraphe installed on your machine
- SSH client installed on your machine (ex: putty)
- the little fork-like motor securing lock

## Connect Pepper's head

- Open the Pepper head from the head back inserting the fork-like motor securing (blue plastic) lock
- Plug Pepper using an ethernet cable straight from its head to a laptop
- Turn Pepper on
- Press the chest button once to get Pepper's IP address
- Open a browser and go to Pepper's IP address
- Go to the WiFi tab
- Click on the WiFi you want to connect to OR on the add button if the SSID is not broadcasted
- Enter the WEP/WPA key if needed OR the SSID and the WEP/WPA key if needed
- Click connect

-> Pepper's head is now connected to the WiFi

## Connect Pepper's tablet

- Open a terminal
- Connect to Pepper using SSH

	- ssh nao@PEPPER_IP
	- (if asked) say yes to use an unsecure connection
	- enter the password

- Run the following command line:
`qicli call ALTabletService._openSettings`

- The Settings menu should now be opened on the tablet
- Click on WiFi
- Click on the WiFi you want to connect to OR click on Add Connection if the SSID is not broadcasted
- Enter the WEP/WPA key if needed OR the SSID and the WEP/WPA key if needed
- Click connect

-> Pepper's tablet is now connected to the Wifi

## Finish
- Turn Pepper off
- Unplug the ethernet cable
- Close the head
- Start Pepper

ALL DONE \o/

## Troubleshooting 

In case you are provided with a WiFi that requires to connect through a login page well... pray that the IT guys of the venue are kind enough to change that. 
