# Arduino UNO bluetooth code uploader

I was looking for a mean to **collect data** and **transmit it via bluetooth**.
An **Arduino UNO** associated to an **HC-05 BT module** seemed to be the right candidates for my project.

Given that this system was intended to be installed in a hard-to-reach location, why not also use Bluetooth for downloading the software?
I was quite sure that a lot of people had already done the same and that it would take me five minutes to find a guideline with Google or chatGPT.

In fact no. A lot of project didn't solved the issue of using the hardware UART of the UNO and used a software UART instead.
And regarding the code uploading, the issue of the board reset was neither clearly solved.

Hence I enventually drew the circuit by myself.
Given that this circuit isn't that complicated, but that it is not straightforward for a person not well versed in EE enginieering, I decided to share it.

The detailed description is provided in the [wiki](https://github.com/Art-ut-Kia/ArduinoBluetoothLoader/wiki)

And here is a picture of the prototype:
![text](https://github.com/Art-ut-Kia/ArduinoBluetoothLoader/blob/main/Wiki_images/BT_Loader.jpg)
