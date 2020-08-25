---
title: "WCSNG - Research"
layout: gridlay
excerpt: "mMobile"
sitemap: false
permalink: /mmobile/
---

# mMobile: Building a mmWave testbed for 5G NR mobility management
---
### mmNets 2020 Workshop (with Mobicom)
```
Authors: Ish Kumar Jain, Raghav Subbaraman, Tejas Harekrishna Sadarahalli, Xiangwei Shao, Hou-Wei Lin, Dinesh Bharadia
```
#### <a href="{{ site.url }}{{ site.baseurl }}/files/mmobile.pdf" style="background-color: white; color: orange;">[Paper]</a> [Slides] [Video] [Datasets]

<!--
<div class="well">
<h3> WiFi Datasets News: </h3>
<h4> 06/20/2020: We are releasing the largest location labelled WiFi CSI dataset, that can be accessed at <a href= "https://wcsng.ucsd.edu/wild">WILD</a> webpage.</h4>
</div>
-->

### Abstract
To achieve the promised performance of mmWave 5G-NR in high mobility applications like Vehicle-to-Everything (V2X) communication, there is a need to critically evaluate and improve beamforming methods. Conventional beam management methods developed for higher frequency applications do not directly carry over to the 28 GHz mmWave regime, where propagation and reflection characteristics are vastly different. Further, real system deployments and tests are required to verify these methods in a practical setting. In this work, we develop mMobile, a custom 5G-NR compliant mmWave testbed with the intention of evaluating beam management algorithms. We describe the architecture and challenges in building such a testbed. We then develop a novel and lightweight beam tracking algorithm by exploiting the structure of the 5G-NR waveform and evaluate its performance on the testbed. The algorithm is able to sustain almost twice the average throughput compared to the baseline.


<br>
<br>

<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_testbed.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_testbed.png" width="90%" style="float: center" > </a>
</div>
<br>

We show that mMobile is well designed and can support 5G-NR specifications. Especially, it can support a high throughput link with up to 256-QAM constellation with the bit error rate as low as 0.0022 without channel coding. The FPGA baseband platform can be used as gNB with a high bandwidth of 400 MHz required for 5G NR. We also show that our phased array module can produce the desired beam patterns when measured in an anechoic chamber. 

<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_256qam_beampatterns.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_256qam_beampatterns.png" width="90%" style="float: center" > </a>
</div>

---



## mMobile dataset
Finally, the access to such a testbed is generally out-of-reach to a large research community. To allow the large research community to test and verify novel algorithms for 5G NR mobility management, we release one-of-its-kind mobility dataset. We build the dataset of channel measurements with two important goals. First, it should allow the testing of algorithms based on 5G-NR specific features such as the SSB and CSI-RS. Second, it should easily allow other testbeds to collect and publish similar measurements. We envision this dataset will be useful for testing any new algorithm for mmWave user tracking and mobility management. The dataset is catered to meet these requirements. We plan to continuously add more experiments. 

<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_results.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_results.png" width="90%" style="float: center" > </a>
</div>

Our dataset which consists of multiple indoor and outdoor experiments for up to 30 m gNB-UE link. In each experiment, we fixed the location of the gNB and move the UE with an increment of roughly one degrees. The table specifies the direction of user movement with respect to gNB-UE link, distance resolution, and the number of user locations for which we conduct channel measurements. Outdoor 30 m data also contains blockage between 3.9 m to 4.8 m. At each location, we scan the transmission beam and collect data for each beam. By doing so, we can get the full OFDM channels for different locations along the moving trajectory with all the beam angles. Moreover, we use 240 kHz subcarrier spacing, which is consistent with the 5G NR numerology at FR2, so the data we collect will be a true reflection of what a 5G UE will see. 

We collect the dataset in by manually moving the UE at different locations on a grid to acquire accurate ground truth location data. We emphasize that this location-based data can be analysed for any speed of user movement. Different user speed will have a different frequency of CSI-RS channel measurements with time. For instance, the UE moving at 30 m/s (1m/s) will have channel data every 20 ms (600 ms) for the outdoor 30 m dataset. Finally, the dataset is collected with fine distance resolution to be used for CSI-RS based tracking. However, a low-resolution variant of the dataset can also be used to evaluate SSB-based beam-acquisition algorithms in practical settings.

### Datasets: TBD
### Code: TBD



