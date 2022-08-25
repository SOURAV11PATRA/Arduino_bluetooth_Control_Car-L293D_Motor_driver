# Arduino_bluetooth_Control_Car-L293D_Motor_driver



![IMG_20220825_224031](https://user-images.githubusercontent.com/68585330/186734564-2d2d0501-542f-4500-8261-aea39913fd9e.png)

This is my first Arduino-based, Bluetooth-controlled RC car. It is controlled by a smart phone application.

step1:Assemble the circuit as shown in the schematic given below. You can use the battery pack for powering driver circuit which I have mentioned in the components section or you could try out some other battery pack, but keep it mind it should deliver between 7-12V and atleast 3500mAh. Also, use different battery/battery-packs for powering Arduino and the Motor-Driver module, but ensure they share a common ground. Battery is one of the most important thing in this project.

Step 2: Compile the code given below in the Arduino-IDE and hit upload, but before that make sure you have disconnected RX of Arduino from TX of Bluetooth Module (HC-05). 

Step 3: Install the application on your Android device through a link provided below. 

Step 4: Pair your Android device and HC-05 over Bluetooth. Now, open the app and click on Bluetooth-icon and select your device from the list. 

Step 5: Now you have gone through all the hard work ! Just sit back and relax and use the on-screen controls available on the app to control the car/bot. You could also change the schematic and code, and add some servos or other actuators to it. But keep it mind as you increase the quantity of actuators, your car/bot would demand more power from the battery/battery-pack. 


![IMG20220824205348_copy_798x749](https://user-images.githubusercontent.com/68585330/186735097-3e15998e-2728-48ab-bea1-60587c085bee.jpg)
