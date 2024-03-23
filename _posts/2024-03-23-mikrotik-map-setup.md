---
type: Document
title: MikroTik mAP Setup
description: How to install your MikroTik mAP
categories:
  - NetAngel DOH
---
For the MikroTik mAP you must have separate Internet Service Provider equipment and wifi router.  The image below shows the components necessary.  If you do not have the correct devices for this setup, please contact us at info@netangel.com and we will be happy to help get you the correct device for your equipment.  

![null](/img/uploads/separate-modem-router-with-map.png)

These instructions will have you connect cables to WAN and LAN ports on the various devices.  If you do not understand the difference please check out [https://www.router-switch.com/faq/lan-wan-port-comparison-of-lan-and-wan.html ](https://www.router-switch.com/faq/lan-wan-port-comparison-of-lan-and-wan.html)

To install your MicroTik mAP pre-configured with NetAngel Connect the MikroTik mAP in between your internet connection (most likely your modem) and your wifi router as follows:

* Connect one ethernet cable from a LAN port your Internet Service Provider's equipment (usually a modem) to Eth1 on the MikroTik mAP.  

  `* Your Internet Service Equipment (modem) may vary in number, color or other ways.  However they are usually yellow, or labeled LAN`

![null](/img/uploads/modems-and-map-reduced.png)

* Connect another ethernet cable between the MikroTik mAP's Eth2 port and the WAN or Internet port on your wifi router.

`* Your router's WAN port may vary in color, label, or position.  In general there should just be a single WAN port, it may be blue or silver, and maybe labeled WAN or Internet`

![null](/img/uploads/router-wan.png)

![null](/img/uploads/mikrotik_map_back_eth2.png)

* Plug in the provided power addapter for the MikroTik mAP
* Unplug the power from your Internet Service Provider device (modem) and wait 30 seconds then plug it back in.  (This may or may not be necessary for your modem, but some modems must be power cycled when a new device is connected to them.)
* Wait until all your equipment has time to boot up (30 seconds to 5 minutes depneding on your equipment).  

Your network should now be protected.  You can test that the filter is working properly by accessing [testfilter.netangel.com](https://testfilter.netangel.com) from a device that is connected to your network.  This page should come up as blocked and you should shortly receive a notification of the blockage.
