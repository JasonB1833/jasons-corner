---
title: "I<sup>2</sup>C"
date: 2025-05-30
categories: [Embedded Garbage]
tags: [jekyll, minimal-mistakes]
---

# What the heck is a "Communication Protocol"

Hey there party people, just wanted to drop a fun little tidbit of knowledge to explain a portion of embedded systems that is super common to anyone who's interested in the topic.

To the un-initiated a "communication protocol" sounds complex, but it's self explanatory. It's the means of which a piece of hardware communicates with another piece of hardware, the idea being that if they have a predetermined system of communication there would be less errors when trying to adapt technology for a given project. I know 'Nerd speak' how yucky, just know it's basically a hardware "secret handshake" that makes sure information is passed properly.


## I<sup>2</sup>C

Now that we have the preliminary info out of the way, I<sup>2</sup>C aka "I tussy" to us "professionals", is a communication protocol that involves 2 wires and a "master" and "slave", sounds like the start of a dirty joke or something if we're being frank.

To get into more detail, the "master" refers to a device that is controlling the other, and "slave" of course being the controlled device. Very controversial naming scheme, but it makes sense. The two wires connect to each of the devices to form a path for communication between devices and I will be going into that in more detail along side some diagrams to help aid with the learning process.


## SDA/SCL

SDA stands for Serial Data, while SCL stands for Serial Clock. The Idea being that the SCL line will tell a device when to read / transfer data and of course the SDA line will transfer the data between devices.
