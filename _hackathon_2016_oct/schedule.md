---
layout: page
title: Schedule
eventpath: hackathon_2016_oct
---

* TOC
{:toc}

## Schedule

### Friday October 28th

| Time  | Comment |
| ------------- | ------------- |
| 17:30 | We open and orders pizzas  |
| 18:00  | Official start with pitches  |


### Saturday October 29th

Nothing specific planned except continued work on the games


### Sunday October 30th


| Time  | Comment |
| ------------- | ------------- |
| 14:00 -  | Expo of prototypes created |


## Proposed projects


### DIY Wearable Pollution Detector (Steffen Mogensen)

The project is an IoT (Internet of things) solution, where you with an arduino, a gas sensor, a bluetooth module and a smartphone is capable of registering air pollution, at any given location..
The idea is to have the arduino to use the gas sensor to detect the polution level and, using bluetooth, send the information to the smartphone, which in turn uses its GPS for localisation.
You can then either send this information to a REASTful API in the cloud, or show it locally on a map. The first solution would be the coolest given the mulituser perspective.

The project will probably include some of the follwoing

  * C-programming (Arduino)
  * Some soldering
  * Java/Android programming
  * 3D print of cabinet
  * optionally developping a RESTful service.



### IoT router (Morten Bo Nielsen)

Normally iot device (and all other networked devices) have unlimited acces to the internet from a home network.
These devices are known to be generally insecure, and we usually don't know what they are doing.

In this project we will create an iot subnet - maybe wireless, maybe using virtual machines - to monitor and to allow/deny certain trafic to and from these devices.
Whenever a device does somethin new, a message is send to a smart phone

We will be using

* virtual machines
* python (?) scripting
* iptables
* android programming
* some network protocol, perhaps a RESTfull API over HTTP(S?)
* some homepage (html/css) and graphics

## Realized projects

One group worked with RESTfull APIs and created an android app. see writeup [here](https://moozing.wordpress.com/2016/11/03/android-and-restfull-api/)
