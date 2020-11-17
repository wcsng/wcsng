---
title: "WCSNG - Research"
layout: gridlay
excerpt: "Pointillism"
sitemap: false
permalink: /pointillism/
---

# Pointillism: Accurate 3D Bounding Box Estimation with Multi-Radars
---
### Sensys 2020
```
Authors: Kshitiz Bansal, Keshav Rungta, Siyuan Zhu and Dinesh Bharadia
```
#### <a href="{{ site.url }}{{ site.baseurl }}/files/Pointillism_paper.pdf" style="background-color: white; color: orange;">[Paper]</a> [Slides] <a href="https://www.youtube.com/watch?v=drZR-Lgpqww&list=PL6jLuiS6wP5Y15NUvvfaQPAtqN7NQm30n&index=3">[Video]</a> 

<!--<a href="https://github.com/ucsdwcsng/mMobile" style="background-color: white; color: green;">[Datasets]</a>-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/drZR-Lgpqww" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div class="well">
<h3> Datasets News: </h3>
<h5> Nov 2020: Multi-radar dataset will be released soon</h5>
</div>


### Abstract
Autonomous perception requires high-quality environment sensing
in the form of 3D bounding boxes of dynamic objects. The primary
sensors used in automotive systems are light-based cameras and
LiDARs. However, they are known to fail in adverse weather conditions.
Radars can potentially solve this problem as they are barely
affected by adverse weather conditions. However, specular reflections
of wireless signals cause poor performance of radar point
clouds.We introduce Pointillism, a system that combines data from
multiple spatially separated radars with an optimal separation to
mitigate these problems. We introduce a novel concept of Cross
Potential Point Clouds, which uses the spatial diversity induced by
multiple radars and solves the problem of noise and sparsity in radar
point clouds. Furthermore, we present the design of RP-net, a novel
deep learning architecture, designed explicitly for radar’s sparse
data distribution, to enable accurate 3D bounding box estimation.
The spatial techniques designed and proposed in this paper are
fundamental to radars point cloud distribution and would benefit
other radar sensing applications.

---
<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/Radar/pointillism.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/Radar/pointillism.png" width="40%" style="float: center" > </a>
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/Radar/pointillism_overview.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/Radar/pointillism_overview.png" width="40%" style="float: center" > </a>
</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
### Pointillism data collection platform.
 (Top Left) 16-
channel Ouster LiDAR, RealSense Depth Camera for ground truth
labels. (Top Right) our radars. (Bottom) Our System: Two radars,
LiDAR, Depth camera combined synchronously to common clock.


<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/Radar/pointillism_setup.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/Radar/pointillism_setup.png" width="40%" style="float: center" > </a>
</div>

---

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>




### Cite the paper
Kshitiz Bansal, Keshav Rungta, Siyuan Zhu and Dinesh Bharadia†. 2020.
Pointillism: Accurate 3D Bounding Box Estimation with Multi-Radars. In
The 18th ACM Conference on Embedded Networked Sensor Systems (SenSys
’20), November 16–19, 2020, Virtual Event, Japan. ACM, New York, NY, USA,
14 pages. https://doi.org/10.1145/3384419.3430783





