---
title: "Homelab"
permalink: /homelab/
layout: single
author_profile: true
---
## How It Started
In my current position, I was fortunate enough to connect with one of our sys admins and we got to talking about Raspberry Pi's and some simple homelab things I could do as I wanted to get more comfortable with Linux since I don't touch it as part of my job duties. Between ideas that came from classwork and some individual training I've taken, I began leaning more into virtual machines as a way to build out temporary machines much easier than dealing with multiple Pi's and extra hardware.

It just so happens that pandemic me had the foresight to build out a gaming pc that is incredibly overspecced... Who am I to turn down Black Friday deals when they come up? With that computer, I'm able to handle 4-5 reasonable VMs depending on scale.

## Goals
My current project is sitting down and actually moving the miscellaneous machines I've accumulated during my program and studies to VMWare Workstation Pro and consolidating to a core network. At one point I think I had 5 or 6 different Linux machines to play around with as I couldn't figure out which flavor worked best for me. (Ubuntu ended up doing it for me) as I've been tempted to play around with the [Blackbuntu](https://blackbuntu.org/) security offshoot and see if they can sway me away from Kali

By this spring I hope to have that list of machines narrowed down to include the following and allow for room to easily branch out if I ever want to dive into something like forensics or malware analysis.
    1. Kali Linux to serve as an attack machine
    2. Vulnerable Linux workstation/server
        - I'm leaning towards [Metasploitable2](https://information.rapid7.com/metasploitable-download.html) for my vulnerable linux machine as I've had some experience with it as part of classwork
    3. PfSense to serve as Router/Firewall
        - Networking is probably my biggest weakness currently and something I want to really work on improving. Between VLANs and firewall rules, this seems to fit the bill
    4. [SecurityOnion](https://securityonionsolutions.com/)
        - I wanted to avoid spinning up and managing a lot of separate machines at once and SecurityOnion offers probably the closest to a one-stop-shop as I can find for a defensive or Analyst machine akin to what Kali is to the offensive world
    5. Vulnerable Windows environment
        - This is most likely a ways away. Ideally I want to build this section out to resemble an AD environment akin to what Heath Adams has in his [Practical Ethical Hacking course](https://academy.tcm-sec.com/)

### Layout
To be completed once I get everything transitioned and working together