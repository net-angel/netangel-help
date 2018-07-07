---
layout: post
title: Configure Your Router for NetAngel DNS
categories: NetAngel DNS
---
Note: Before changing the DNS settings on your router, make sure you have created a DNS device on the NetAngel Dashboard with the public IP address of your network.

1. Sign into your router's web-based admin website (usually this is http://192.168.0.1 or http://192.168.1.1)
2. Find the DNS server settings in your router settings.  This is usually in a setup menu.  Often you will see two DNS fields (one primary and the other secondary)
3. Enter in the NetAngel DNS server address in the DNS field in your router.  
   * 54.70.46.42
   * 54.70.76.29
   * 54.70.99.57
4. OR, if you have IPv6, use:
   * ::ffff:3646:2e2a
   * ::ffff:3646:4c1d
   * ::ffff:3646:6339
5. Save the DNS settings in your router
6. Restart your devices (computer, smart phone, tablet.etc.)
7. Reboot your router
8. You can test the filter by going to testfilter.netangel.com

It is important to note that about every 1-2 months, your IP address may change. This will result in a loss of internet connection. If this occurs, you can solve this problem by going to dashboard.netangel.com > click on your router device > click "Manage Device". On this screen, you'll want to ensure that your "Public IP Address" matches your "Current IP Address". If it does not, simply click "Use this" then click "Save".

![Public IP Address](/img/uploads/25x2o3ddwajzvs5zu8e7g16nuwhlg9bf83jxd77sys182c4n79.png)
