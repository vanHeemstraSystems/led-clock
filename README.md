led-clock
# LED Clock

Based on "S14Clock 14 Segment LED Clock" at https://youtu.be/q_kRyNXgdq0

Based on "Welcome to the s14clock wiki!" at https://github.com/simpleavr/s14clock/wiki

Based on "s14clock" at https://github.com/simpleavr/s14clock

Based on "SimpleAvr Projects" at https://simpleavr.github.io/ 

S14Clock is a bar shaped, web synchronized word clock featuring 24 or 12 characters, 14 segment display

## 100 - Introduction

## 200 - Requirements

This device requires power by USB-C male cable. Order this adaptor, for example, https://www.allekabels.nl/laptop-adapter/532/3637174/laptop-adapter.html

## 300 - Building Our Application

See also the video at https://www.youtube.com/watch?v=q_kRyNXgdq0

When powered up, the LED will display its Network ID ("ESP-*******"), find the matching Network ID in your WiFi networks list and coonect to it. When prompted enter the password (connect with password “12345678”.). 

Next, open the web interface (http://172.217.28.1) to change any settings and/or post messages to the device. See [Initial Setup](https://simpleavr.github.io/s14clock/#initial-setup)

Browse to http://172.217.28.1/_ac (note: after you have provided the Network Password (12345678) when picking the LED Clock from the WiFi List ("ESP-******"), you will automatically be brougth to the Web interface).

Choose from the “3-bar” menu (top right), when in mobile screen size, “Configure new AP” (or browse to http://172.217.28.1/_ac/config) and select your home network.

Enter your home network WIFI credentials and hit “Apply” button.

**WARNING**: The LED Clock will from this instance on no longer show in the list of WiFi Networks, which is perfectly fine. 

Your S14Clock should connect to your home network and will start to work after showing it’s IP address briefly. You may need to reset the S14Clock via the bottom hardware reset button.

The new IPof the LED Clock is now: 192.168.68.113 (as shown briefly on its display when starting up the LED Clock).

You can from now on browse to this new IP address to see the LED Clock web page: http://192.168.68.113

**Configuration**

To adjust the timemzone to Amsterdam, enter "2" in the textbox for Time Zone (meaning UPC time plus 2), and click "Save Configuration". The time on the LED Clock will from now on show the time as it is in Amsterdam.

## 400 - Conclusion
