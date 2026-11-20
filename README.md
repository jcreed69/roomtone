# Roomtone

Ever wanted to make a surround sound system but needed the same speaker model or another reason. But now with Roomtone you can turn any old or new device into a surround sound speaker as long it has a browser and Wi-Fi.

## RoomTone works with:
- Phone
- Tablet
- Laptop
- Bluetooth speaker

## RoomTone best Features

- Features a clean UI
- 3D room scale to see where the devices are placed
- it can tune Left and right
- Allows you to use a Subwoofer (even if it is not(requires extra software which will be detailed on the RoomTune App))
- Uses LocalHost
- Allows more than 1 Bluetooth devices to be connected
- Preloaded Equaliser and a customisable EQ
- change the volume of the devices remotely
- no app needed

# Set-up and Use RoomTone

Guide on how to run the software and use it
## what you need:
- Windows Laptop with latest Python installed
- stable Wi-fi connectivity
- 2 devices - can be a phone or tablet or laptop which has working Wi-Fi and Latest Browser
- Youtube link ready to test
- 
## Running the Interface

1. Download the .zip and extract it
2. open the folder till you see the main.py file
3. in the search bar of file explorer search "cmd"
4. First run python -m pip install -r requirements.txt
5. run python main.py

## Connecting devices

1. on the Host press pair device
2. Make sure both devices are connected to the same Wi-Fi
3. on the target device enter the link provided where it says Device page - This is not the host page this is where you devices connect
4. once the website opens enter the pairing code/room code which should be a 6 digit code
5. Give you device a recognisable name
6. once connected head to start speaker and now it should be capturing audio from host device
   
To Test try a random youtube video to see wether the audio is coming out of the target device make sure the volume is up

## Enabling Left and Right Channels (Surround sound)

1. on the host device head to the 3 lines and click on Room devices
2. devices connect will automatically assign Left or right
3. if you want to change it click the device and assign L or R

Now test with a video by searching "L and R test" or "surround sound test"

## Enabling Subwoofers#

For this you dont need a subwoofer any device works but i recommend a Bluetooth speaker and a JBL branding to notice the Bass
