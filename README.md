# Wildlife-Camera
Individual project completed at home that captured and recorded wildlife activity using a Raspberry Pi Zero W and MotionEyeOS. The portable Wi-Fi camera featured motion detection, video recording, and accessibility over the local network or the internet
# Hardware
- Rasberry Pi Zero W
- Compatible pi camera (night vision to use in the dark)
- SD card
- Waterproof container
- Soldering gun or drill
- Pi power supply
- Portable charger 
- Laptop/pc to monitor the camera and save recordings and pictures
# Steps
- Download MotionEyeOS and flash image to SD card
- Download the wpa_supplicant text file. This connects the pi to your Wi-Fi network. Change the country code, network name, and the network password. Then rename the file to wpa_supplicant.conf and add it to the SD card
- Place the SD card into the pi and connect the camera
- Boot up the pi
- Find the IP address of the Pi. I did this by connecting via ethernet
- Type the address in your browser
- The camera feed should be shown on your device
- Assign a manual IP to the pi by going into the MotionEyeOS settings
- Login to your routers configuration page and add a port forwarding instruction. This way requests from outside your local network are forwarded to your pi camera. This enables access to your camera over the internet
- Change the settings of the camera as you prefer (turn on motion detection)
- Connect to the server on your laptop/pc and login. Now you can see all the images and recordings.  
- Solder a hole in the waterproof container and fit the pi camera and in. Power the pi using a portable charger. Then place it ouside to see wildlife! 
![Camera1_19-40-51](https://github.com/user-attachments/assets/37f788e2-e38c-4120-bf7b-b8744db10681)
![IMG_3564](https://github.com/user-attachments/assets/faeb5afc-c38f-4cd7-baa5-ddbeb03bc561)
![IMG_3548](https://github.com/user-attachments/assets/b402d208-2612-4f0e-9ed8-f6081b7b9763)
![IMG_3345](https://github.com/user-attachments/assets/5c7b66b9-278f-45f9-a30c-86aa7690ad25)
