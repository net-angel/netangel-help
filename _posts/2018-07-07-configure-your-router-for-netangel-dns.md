---
type: Document
title: Generic Router Instructions
description: Configure Your Router for NetAngel DNS
categories:
  - NetAngel DNS
---
## Note

Before changing the DNS settings on your router, make sure you have created a DNS device on the NetAngel Dashboard with the public IP address of your network.

## Sign Into Router

Sign into your router's web-based admin website (usually this is <http://192.168.0.1> or <http://192.168.1.1>).

Find the DNS server settings in your router settings.  This is usually in a setup menu.  Often you will see two DNS fields (one primary and the other secondary)

## IPv4 NetAngel DNS Servers

Enter in the NetAngel DNS server address in the DNS field in your router:

* 54.70.46.42
* 54.70.76.29
* 54.70.99.57

## IPv6 NetAngel DNS Servers

If you have IPv6, you will also need to enter these in the IPv6 DNS settings:

* ::ffff:3646:2e2a
* ::ffff:3646:4c1d
* ::ffff:3646:6339

## Power Cycle

1. Save the DNS settings in your router
2. Restart your devices (computer, smart phone, tablet.etc.)
3. Reboot your router
4. You can test the filter by going to <http://filtertest.netangel.com>

It is important to note that about every 1-2 months, your IP address may change. This will result in a loss of internet connection. If this occurs, you can solve this problem by going to:

[dashboard.netangel.com](dashboard.netangel.com) > click on your router device > click "Manage Device"

On this screen, you'll want to ensure that your "Public IP Address" matches your "Current IP Address". If it does not, simply click "Use this" then click "Save".

![Public IP Address](/help/img/uploads/25x2o3ddwajzvs5zu8e7g16nuwhlg9bf83jxd77sys182c4n79-1.png)
