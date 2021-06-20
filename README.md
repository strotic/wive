## WIVE - Wireless Driver Installer 

![WIVE](https://user-images.githubusercontent.com/86202527/122684071-eccbc480-d1f2-11eb-8e84-30b457aedc66.png)



"WIVE" was created to provide a simple, easy and reliable way 
to install Realtek wifi drivers on your linux machine. 
This tool is NBU compliant which means even a cyber dummy can run it.


## Installation 

*Prerequisites*

Please check to ensure that you have python and python pip installled. If you dont
please enter the following into your terminal.

`` sudo apt-get update``

``sudo apt install python3``

*Step 1*

Clone the github repository.

``python 
git clone https://github.com/strotic/wive.git
``

*Step 2*

Run the following terminal command

``sudo su python wive.py``

You will be prompt to enter your password. Please do so to continue the driver installation.



## Supported Drives 


| Driver Version | Supported |
|----------------| ----------|
|Realtek RTL8723BU | Yes     |
|Realtek RTL8723DE | Yes     |
|Realtek RTL8723BE | Yes     |
|Realtek RTL8814AU | Yes     |
|Realtek RTL8821CE | Yes     |
|Realtek RTL8822CE | Yes     |
|Realtek RTL8188FU | Yes     |



## Must Read.

If your device isn't able to connect to the internet, 
please try creating a local hotspot from your phone. 
Connect your phone to your laptop/PC via a USB.
Enable on your phone "Bluetooth tethering".
On your linux machine, right click the bluetooth icon (or find the bluetooth settings)
and select bluetooth devices.
Right-click the connected device and select "Network Access Point".
It should allow connectivity via bluetooth to download this repository and it's dependencies.
