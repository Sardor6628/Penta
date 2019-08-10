# Penta-Security-using-Raspberry-Pi
Door lock and unlock system using Raspberry Pi 3 Model B. It gives a chance to lock or unlock the door using 5 ways. 

## Main techniques
      Mobile Application
      Keypad System
      Fingerprint System
      Face Recognition System
      Metallic Key
      
## Used tools
      Python
      Java Script
      Java
      OpenCV
      Jason files
      Modules
      Raspberry Pi 3 Model B
      Linux OS
      Blyink Server
      Raspberry Pi Camera
      Jump Wires

# Mobile Application

Mainly, we have used Blyink server in order to integrate our application. The coding part was done in Python and Linux System. The users can open or lock the doors easily. Here is output:

![image](https://user-images.githubusercontent.com/52565814/60770703-06b09180-a119-11e9-83b4-9d42a91044d9.png)

# Keypad System

In this part, the users can request for Raspberry Pi to send one time 4 digit password via their Mobile Appliation. Then, They can accept 4 random generated numbers via their App. Here is output:

![image](https://user-images.githubusercontent.com/52565814/60771353-cf92ae00-a121-11e9-931f-f848048faf2c.png)

# Fingerprint System

It looks like a general fingerprint srategy. Host users should store their fingerprints to the database. Here is the outhput:

![image](https://user-images.githubusercontent.com/52565814/60771379-4f207d00-a122-11e9-84fc-cc1208b24d14.png)

# Face recognition

Its srategy is the same with the fingerprint system. OpenCV is used to integrate in this forum. Here you can see in case, the user is unkown (the Pi rejects to open the door):

![image](https://user-images.githubusercontent.com/52565814/60771406-c2c28a00-a122-11e9-8e0a-316e0c3fd11b.png)

and the user is known (the Pi opens the door):

![image](https://user-images.githubusercontent.com/52565814/60771409-cb1ac500-a122-11e9-87cb-965bdb2da14b.png)

# Metallic Key

The last way to lock or unlock the door is with the metallic key as it is the vey usual way.
