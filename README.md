# USB_PD_Sink

### USB C all the things!.

With this breakout of the STUSB4500, you can power all of your devices and electronics projects. From Arduinos to Laptops, USB-C Power Delivery can provide up to **100W (20V @ 5A).**

You can now purchase this from my [Tindie!](https://www.tindie.com/products/ketszim/usb-c-pd-sink-stusb4500/)

This device can store 3 PDOs (Power Delivery Outputs), and upon connection it will attempt to negotiate the highest of these 3. This means that it can operate as a standalone device, without the need for an external microcontroller. The PDO negotiated is shown by the following colors. By default, the device has the following PDOs:

|PDO1|PDO2|PDO3|
|:-----:|:-----:|:-----:|
|5V @ 1.5A|15V @ 1.5A|20V @ 1A|
|Blue|Green|Red|

The PDOs can also be customized by programming the Non-Volatile Memory (NVM) registers via I2C.
The device can also be connected to a microcontroller, to allow on the fly negotiation of the PD contract. To do this the device just needs to be connected via I2C according to the pinout below. Libraries for Arduino exist and are quick and easy to use.

#### Technical Specs
- Controller: STUSB4500
- Output Voltage: 5-20V*
- Output Current: 0-5A*
- LED: Built in LED to display which PDO is negotiated (See above for specifics)
- Protection: ESD and Transient Protection on both Power and USB-C Pins, Discharge of VBUS path on voltage change or capable detach

Designed and manufactured in Canada

*\*Output power is limited by the capability of your charger*

<a href="https://www.tindie.com/stores/ketszim/?ref=offsite_badges&utm_source=sellers_ketszim&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>

![Pinout](https://github.com/ketszim97/USB_PD_Sink/blob/master/Renders/Fusion_Render_17_800px.png)

![Fusion Render 1](https://github.com/ketszim97/USB_PD_Sink/blob/master/Renders/Fusion_Render_18.png)
