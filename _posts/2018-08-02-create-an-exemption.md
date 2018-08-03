---
type: Document
title: Create an Exemption
description: How to create an exemption with your NetAngel Router
categories:
  - FAQs
---
Sometimes the NetAngel VPN can prevent certain devices from running properly. When that happens, it is best to allow those devices to go straight to the internet without being filtered. Things like Netflix, security systems, game consoles, etc. can bypass the filter when set up as follows:



1. Log into your router's web interface

2. Click on "VPN" on the left side menu

3. Click on "OpenVPN Clients"

4. Towards the bottom you will see "Redirect Internet traffic"

5. Set that to "Policy rules"

 

You will put in two rules in the "Rules for routing client traffic through the tunnel".

 \*\* Rule #1 will always be NetAngel. 

Rule 1:

Description

NetAngel Filter

Source IP

0.0.0.0

Destination IP

0.0.0.0/0

Iface

VPN

Rule 2:

Description

TV (or whichever device you're trying to exempt from being filtered)

Source IP

Drop down the list and select your TV device

Destination IP

0.0.0.0/0

Iface

WAN

Be sure to have the "/0" at the end of the Destination IP for the rules.  After adding these rules, select "Apply".

 

You can add as many exceptions as you need.
