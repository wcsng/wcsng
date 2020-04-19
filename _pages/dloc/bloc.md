---
title: "WCSNG Lab - Research"
layout: projectnewslay
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
State of the art localization using Bluetooth Low Energy (BLE) devices uis based on RSSI, while Wi-Fi has achieved decimeter level localization using Channel State Information (CSI) based localization. With this work we bring CSI based sub-meter level accurate localization for BLE tags. With BLoc we achieve

<div class="col-sm-5 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/bloc_1st_contribution.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/bloc_1st_contribution.png" width="70%" style="float: center" > </a>
</div>
<br>



<br>
<br>
<br>
<br>
<br>



<div class="col-sm-5 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/locap_deployed.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/bloc_2nd_contribution.png" width="90%" style="float: center" > </a>
</div>
LocAP is deployed on an autonomous bot which hosts a Lidar and a WiFi client. The bot moves around in a specific path and builds indoor maps using standard SLAM algorithms. Concurrently, the WiFi client on the bot collects channel state information (CSI) data from existing access points and run a novel algorithm on this data to estimate the access point attributes-- location, orientation, and antenna placement.
<br>
<br>
<br>
<br>

***

<div class="col-sm-5 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/locap_deployed.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/bloc_3rd_contribution.png" width="90%" style="float: center" > </a>
</div>
LocAP is deployed on an autonomous bot which hosts a Lidar and a WiFi client. The bot moves around in a specific path and builds indoor maps using standard SLAM algorithms. Concurrently, the WiFi client on the bot collects channel state information (CSI) data from existing access points and run a novel algorithm on this data to estimate the access point attributes-- location, orientation, and antenna placement.
<br>
<br>
<br>
<br>

***

### Watch the Video
<iframe width="900" height="506" src="https://www.youtube.com/embed/tC70Hs8cjwI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
