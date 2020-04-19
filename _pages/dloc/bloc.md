---
title: "WCSNG Lab - Research"
layout: gridlay
excerpt: "LocAP"
sitemap: false
permalink: /bloc/
---

# BLoc: CSI-based accurate localization for BLE tags
---
### CoNEXT'20
```
Authors: Roshan Ayyalasomayajula, Deepak Vasisht, and Dinesh Bharadia
```


#### <a href="{{ site.url }}{{ site.baseurl }}/files/bloc_paper.pdf" style="background-color: white; color: orange;">[Paper]</a> <a href="{{ site.url }}{{ site.baseurl }}/files/bloc-ppt.pdf" style="background-color: white; color: orange;">[Slides]</a> <a href="https://youtu.be/tC70Hs8cjwI" style="background-color: white; color: orange;">[Video]</a>

### Motivation
State of the art localization using Bluetooth Low Energy (BLE) devices uis based on RSSI, while Wi-Fi has achieved decimeter level localization using Channel State Information (CSI) based localization. With this work we bring CSI based sub-meter level accurate localization for BLE tags.

<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/locap_main.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/locap_main.png" width="70%" style="float: center" > </a>
</div>
<br>


LocAP is an autonomous system to physically map the environment and accurately locate the attributes of existing wireless infrastructure in the physical space down to the required stringent accuracy of 3 mm antenna separation and 3 degree deployment orientation median errors, whereas state-of-the-art algorithm reports 150 mm and 25 degree respectively.

<br>
<br>
<br>
<br>
<br>



<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/locap_deployed.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/locap_deployed.png" width="90%" style="float: center" > </a>
</div>
LocAP is deployed on an autonomous bot which hosts a Lidar and a WiFi client. The bot moves around in a specific path and builds indoor maps using standard SLAM algorithms. Concurrently, the WiFi client on the bot collects channel state information (CSI) data from existing access points and run a novel algorithm on this data to estimate the access point attributes-- location, orientation, and antenna placement.
<br>
<br>
<br>
<br>

***

### Watch the Video
<iframe width="900" height="506" src="https://www.youtube.com/embed/tC70Hs8cjwI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

***

#### Latest News:
+ Our WCSNG group inspired from the need of contact tracing and proximity sensing, has developed a BLE based proximity sensing called <a href = "https://wcsng.ucsd.edu/bluble/">BluBLE</a> to tackle with the COVID-19 pandemic.
+ BLoc published in Dec 2018 has prposed the idea of long sequences of 1's and 0's along with multiple antenna BLE master to enable AoA esitmation along with relative ToF esimation. Later in
