---
layout: post
title: Next steps
#feature-img: "assets/img/about.jpg"
#thumbnail: "assets/img/about.jpg"   # Add a thumbnail image on blog view
tags: []
hide_title: false # Hide the title when displaying the post, but shown in lists of posts
---

Here is a small update on the progress of the project

## Firmware

In the meantime, we had the opportunity again to test the current version of the
bt-trx firmware (0.1.0) with further radio models. It turns out that
accessory radios usually work without problems. Some manufacturer radios, on
the other hand, cannot currently be connected.
We already have a few configuration values of the WT32i Bluetooth module that
should fix this problem and will do some tests soon.

## Hardware

We are currently in the process of developing the fourth version of the bt-trx
development board.
The most significant change is that instead of the Teensy 3.2 module, we'll switch
to an ESP32.
This is mainly because the ESP32 will cost about half of the price of the
Teensy module. As a further advantage, the ESP32 offers integrated
Wifi, which we may use in the future for configuration and firmware updates
of the bt-trx. With the integrated Bluetooth LE we can e.g.
wirelessly connect a PTT button.

As soon as we are finished with the development of v4, we will get started to 
make bt-trx kits available.
