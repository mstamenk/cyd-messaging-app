# cyd-messaging-app
Cheap Yellow Display - Messaging app 

# Project

Messaging app using the CYD - ESP32-2432S028. The goal of the project is to connect two ESP32 via Wi-fi and send messages to each other using the touch screen.

# Installation on macos

The framework consists of a ESP32 firmware using the `lvgl` library for button displays, `x2046pt` and `ili9341` to control the touch screen and print text and messages. 

Instructions are based of [ESP32-Cheap-Yellow-Display-Micropython-LVGL|https://github.com/de-dh/ESP32-Cheap-Yellow-Display-Micropython-LVGL]. The IDE used is `Thonny`. 

First, one needs to install the firmware:

```
git clone git@github.com:mstamenk/cyd-messaging-app.git

wget https://stefan.box2code.de/wp-content/uploads/2024/04/lv_micropython-WROOM_AOIEspNow.zip .


```


