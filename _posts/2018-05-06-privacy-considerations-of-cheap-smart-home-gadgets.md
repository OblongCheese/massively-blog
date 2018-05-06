---
layout: post
title:  "Privacy cosniderations of cheap smart home gadgets"
date:   2018-05-06
excerpt: "Privacy is still important in 2018"
image: "/images/magnifying-glass-1607208_1920.jpg"
future: true
---

## Home Security
Unfortunately in this day and age it seems almost a certainty that at some point, someone unscrupulous will try to do something illegal on or around your property. Forgoing all pretense of decency on behalf of my fellow humans means I can pragmatically consider the protections afforded me from such events. In essence, home security is an important aspect of the modern home.

### Video Surveillance
Video surveillance systems are as old as broadcast video. Today it is easy to buy pre-packaged systems with two, four or six cameras that connect wirelessly back to a central recording console accessible from anywhere in the world via the Internet. Of course, I wouldn't want to make things too easy for myself, so I am opting to go the DIY route for some aspects of this type of home security system.

### IP cameras
IP surveillance cameras use IP-based networking concepts to digitally transmit surveillance data in the form of video or picture feeds. I currently have two Hikvision cameras that are designed to be used as standalone solutions. They can be set up easily using a mobile phone app. This is a pain point for me. This ease of use implies a certain level of trust placed by the user (me) in the manufacturer (Hikvision). For the Hikvision cameras to work via the Hikvision app, I have to give up my privacy by permitting data from said cameras being sent via the Internet to systems unknown to me, as well as to my mobile phone.

### Privacy of the Home User
This screenshot from my DNS server shows that the noisiest two devices on my home network are my two Hikvision IP cameras. They are constantly making DNS requests for a specific hostname. This appears to be the cloud-based service that Hikvision offers to end users to ease the use of their products. I personally do not require the use of this cloud service. I do permit the cameras to make these DNS queries, but they are unable to establish any kind of connectivity to Internet destinations.
![Hikvision IP Camera DNS query log](/images/hikvision-dev-ezviz7-dns-requests.png)

I do not want any photos or video of myself or my family to be accessed, processed or stored by systems unknown to me. So I do not permit that to occur.

### Privacy of the Home Invader
Although I can't say I have much sympathy for them, anyone who is caught on my surveillance cameras engaging in illegal activities would likely also wish to have this information kept private. And it will be kept private. Private between myself and the local police.
