---
layout: post
title:  "Transforming a dumb home into a smart home"
date:   2018-02-24
excerpt: "Wading through the technobabble and buzzwords of home automation"
image: "/images/RiserDiagram.jpg"
future: true
---

## Home Automation
Since prior to purchasing a house, I have been thinking about home automation and reading about the various projects that people are completing. If you aren't sure what home automation is about, I would suggest you start by reading the excellent [Wikipedia article](https://en.wikipedia.org/wiki/Home_automation). I would like to automate some elements of my household for reasons of comfort, convenience and energy efficiency.

### Lighting
Automating aspects of the lighting within my household can help me to achieve all three of my objectives:
* Comfort: lights automatically turn on and off in support of our circadian rhythm.
* Convenience: lights automatically turn off if nobody is in the house, or automatically turn on when someone is home.
* Energy efficiency: lights need not come on at full power or can be on constantly if solar power is available.

### Power
* Comfort: ensure that all power-hungry appliances and appliances that require supervision (e.g. iron) are automatically turned off at the wall when there is nobody home.
* Convenience: automatically power on the kettle and have boiling water ready for when we wake up.
* Energy efficiency: power off unneded appliances when nobody is home, preventing all idle power draw. Give warnings about power-hungry appliances when solar power is not available.

### Air-conditioning
* Comfort: automatically have the air-conditioner turn on and cool down the household prior to coming home.
* Convenience: turn off the air-conditioner automatically when everyone has left the house.
* Energy efficiency: automatically adjust the temperature and fan settings depending upon whether solar power is available or not.


## Difficult aspects for DIY home automators
On the topic of air-conditioners, I will say that like most other commercially-available solutions for home automation, the options are severely lacking in variety. Insofar as I can tell, just about every commercially available automated air-conditioner requires a connection to the Internet to function. And by that I mean the appliance must be able to initiate communications with the manufacturers home automation servers via the Internet, even when both your controller (your smart phone) and the appliance are connected to the same WiFi network.

This applies to most currently available smart appliances and is frankly a letdown for the DIY home automator.

How these systems work is illustrated in the following diagram, courtesy of Fujitsu.

![Fujitsu WiFi air-conditioner control flow diagram](/images/fujitsu-img-wi-fi-system-diagram.jpg)

As per the diagram labels;
1. Your control device (phone or tablet) at home will connect to your home WiFi so that it can communicate with (5), the manufacturer home base. Consider the scenario that you accidentally smash your phone or lose it. How do you now control your smart home appliances?
2. Your air conditioner will also connect to your home WiFi so that it can communicate with (5), the manufacturer home base. WiFi in the home is typically an unreliable communications medium. With the density of WiFi networks in modern suburbia, it can be difficult to get a good signal throughout the entire house (and yard).
3. Your home WiFi is a single point of failure in this control scheme. If your Internet goes offline, you can't control your smart appliances anymore.
4. The Internet itself, while a robust global network, is also prone to failures and mishaps. Specifically, nothing that the average user (you and me) send out on to the Internet has any guarantee that it will reach its destination. The Internet works by sending and receiving as much data as it can. Sometimes your data gets lost on the way there, and sometimes it gets lost on the way back. This is not an ideal thing to occur to your request to turn on or off key appliances in your home.
5. While I am sure the manufacturers of smart home devices are doing their utmost to ensure service reliability, the fact remains that most of these companies are completely new to the concept of setting up and maintaining an always-on, Internet-connected service. The key issue here is that there is generally no service agreement between the end-user and the manufacturer which guarantees the continued operation of the Internet-connected service. What this means is that the manufacturer may decided to turn off the Internet-enabled features of your smart home appliance when that appliance is superseded by a newer model. A good example of this is when Logitech [decided to shutdown](https://arstechnica.com/gadgets/2017/11/logitech-to-shut-down-service-and-support-for-harmony-link-devices-in-2018/) its Harmony Link devices at the end of 2017, leading to much community uproar and Logitech having to provide free upgrades to new devices for all affected users. That's fine for a cheap media player, but an impossible-to-believe scenario for any whitegoods manufacturer to give all its customers a free refrigerator or air-conditioner every time they release a new model.

## What is the solution?
Ideally, manufactures of smart home appliances would publish all the technical specifications of their WiFi interfaces and communications protocols so that these devices could continue to operate in the likely scenario that the services through which we communicate with our smart phones or tablets are taken offline in the future. Publication of such information would also greatly assist DIY-ers such as myself to create custom solutions to fill the gaps left by mediocre manufacturer software even while the appliance in question is a new and supported product.
