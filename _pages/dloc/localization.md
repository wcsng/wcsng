---
title: "WCSNG Lab - Research"
layout: redirected
excerpt: "WCSNG Lab -- Localization"
sitemap: false
permalink: /dloc/
redirect_to:  https://wcsng.ucsd.edu/dloc
---

# Indoor Navigation using Deep Learning
---

## DLoc deployment
<div class="row">
<div class="col-sm-3 clearfix">
<br>
<br>
<br>
<p align="justify">Once DLoc has been trained using the data collected from MapFind. Any new user entering the environment can use their smartphone to estimate their location with the help of the trained network.</p>
</div>

<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/pubpic/user_example.gif"><img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/user_example_extended.gif" width="70%" style="float: center" > </a>
</div>

---
## MapFind to train DLoc

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/pubpic/bot_data_collection_medium_slow.gif"><img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/bot_data_collection_medium_slow.gif" width="100%" style="float: center" > </a>
After the map is generated, MapFind goes around the mapped space in an optimal path pre-determined by our path-planning algorithm so as to cover sufficient space in the provided map as shown above.
</div>

<div class="col-sm-6 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/pubpic/network_trainig_medium_slow.gif"><img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/network_trainig_medium_slow.gif" width="100%" style="float: center" > </a>

Simultaneously the server on board the bot collects the CSI information and converts them into the Input heatmaps as shown above. These Input images are then used to train the DLoc network shown above using both L<sub>Location</sub> and L<sub>Consistency</sub> losses. These losses back propogate as shown by the red dotted lines to train DLoc.
</div>

---


## DLoc code and data
While being the first in in Deep Learning based Indoor Navigation with WiFi data, we want to build WiFi CSI dataset on par with [ImageNet](http://www.image-net.org/) to assist further research in WiFi based indoor localization and their applications.

### Datasets: TBD
### DLoc code: TBD



