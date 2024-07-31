# Wildlife-Camera
Individual project completed at home that captured and recorded wildlife activity using a Raspberry Pi Zero W and MotionEyeOS. The portable Wi-Fi camera featured motion detection, video recording, and accessibility over the local network or the internet
# Hardware
- Compatible pi camera (night vision to use in the dark)
- SD card
- Waterproof container
- Soldering gun or drill to make a hole in the plastic
- Pi power supply
- External device to monitor the camera and save recordings/pictures
# Steps
- Download MotionEyeOS and flash image to SD card
- Download the wpa_supplicant text file. This connects the pi to your Wi-Fi network. Change the country code, network name, and the network password. Then rename the file to wpa_supplicant.conf and add it to the SD card
- Place the SD card into the pi and connect the camera
- Boot up the pi
- Find the IP address of the Pi. I did this by connecting via ethernet
- Type the address in your browser
- The camera feed should be shown on your device
- Assign a manual IP to the pi by going into the MotionEyeOS settings
- Login to your routers configuration page and add a port forwarding instruction. This way requests from outside your local network are forwarded to your pi camera. This enables access to your camera over the internet in the same way you could do it locally
- Change the settings of the camera as you prefer (turn on motion detection)
- Solder a hole in the waterproof container and fit the pi camera in. Then place it ouside to see wildlife! 
