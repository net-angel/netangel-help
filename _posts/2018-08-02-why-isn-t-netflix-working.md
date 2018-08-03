---
type: Document
title: Why Isn't Netflix Working?
description: How to solve Netflix streaming problems
categories:
  - FAQs
---
Some customers have reported experiencing issues streaming Netflix after purchasing a NetAngel Router. We have found the best way to fix this is to create an exemption for the device you watch Netflix on (your TV, for example.) This prevents the television from being filtered, which prevents Netflix from being blocked. Use the following steps to create an exemption on your router:  





1. Log into your router's web interface

2. Click on "VPN" on the left side menu

3. Click on "OpenVPN Clients"

4. Towards the bottom you will see "Redirect Internet traffic"

5. Set that to "Policy rules"



You will put in two rules in the "Rules for routing client traffic through the tunnel".



Rule 1:

\* Description

o NetAngel Filter

\* Source IP

0.0.0.0

\* Destination IP

0.0.0.0/0

\* Iface

o VPN



 Rule 2:

\* Description

o Gaming System/TV/etc. you watch Netflix on

\* Source IP

o Drop down the list and select your device

\* Destination IP

 0.0.0.0/0

\* Iface

o WAN



Be sure to have the "/0" at the end of the Destination IP for the rules. After adding these rules, select "Apply".
