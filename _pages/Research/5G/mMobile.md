---
title: "WCSNG - Research"
layout: gridlay
excerpt: "mMobile"
sitemap: false
permalink: /mmobile/
---

# mMobile: Building a mmWave Testbed to Evaluate and Address Mobility Effects
---
### mmNets 2020 Workshop (with Mobicom)
```
Authors: Ish Kumar Jain, Raghav Subbaraman, Tejas Harekrishna Sadarahalli, Xiangwei Shao, Hou-Wei Lin, Dinesh Bharadia
```
#### <a href="{{ site.url }}{{ site.baseurl }}/files/mmobile.pdf" style="background-color: white; color: orange;">[Paper]</a> [Slides] [Video] <a href="https://github.com/ucsdwcsng/mMobile" style="background-color: white; color: green;">[Datasets]</a>

<!--
<div class="well">
<h3> WiFi Datasets News: </h3>
<h4> 06/20/2020: We are releasing the largest location labelled WiFi CSI dataset, that can be accessed at <a href= "https://wcsng.ucsd.edu/wild">WILD</a> webpage.</h4>
</div>
-->

### Abstract
Beamforming methods need to be critically evaluated and improved to achieve the promised performance of millimeter wave (mmWave) 5G NR in high mobility applications like Vehicle-to-Everything (V2X) communication. Conventional beam management methods developed for higher frequency applications do not directly carry over to the 28 GHz mmWave regime, where propagation and reflection characteristics are vastly different. Further, real system deployments and tests are required to verify these methods in a practical setting. In this work, we develop mMobile, a custom 5G NR compliant mmWave testbed to evaluate beam management algorithms. We describe the architecture and challenges in building such a testbed. We then create a novel, low-complexity beam tracking algorithm by exploiting the 5G NR waveform structure and evaluate its performance on the testbed. The algorithm can sustain almost twice the average throughput compared to the baseline.


<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_testbed.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_testbed.png" width="90%" style="float: center" > </a>
</div>

We show that mMobile is well designed and can support 5G NR specifications. We established a link with 240 kHz subcarrier spacing with a bandwidth of 50 MHz. The radiated transmit power is fixed to an EIRP of 30 dBm. We demonstrate that \name can support a high throughput link with up to 256-QAM constellation with the bit error rate as low as 0.0022 without channel coding. We have also verified that our FPGA baseband platform can be used as gNB with high bandwidth of 400 MHz required for 5G NR. Finally, we show that our phased array module can produce the desired beam patterns when measured in an anechoic chamber.


<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_256qam_beampatterns.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_256qam_beampatterns.png" width="90%" style="float: center" > </a>
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



## mMobile dataset
The access to such a testbed is generally out-of-reach to a large research community. To allow the large research community to test and verify novel algorithms for 5G NR mobility management, we release one-of-its-kind mobility dataset. We build the dataset of channel measurements with two important goals. First, it should allow the testing of algorithms based on 5G-NR specific features such as the SSB and CSI-RS. Second, it should easily allow other testbeds to collect and publish similar measurements. We envision this dataset will be useful for testing any new algorithm for mmWave user tracking and mobility management. The dataset is catered to meet these requirements. We plan to continuously add more experiments. 


<div class="col-sm-9 clearfix">
  <a href="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_results.png"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/5G/mMobile_results.png" width="90%" style="float: center" > </a>
</div>

Our dataset which consists of multiple indoor and outdoor experiments for up to 30 m gNB-UE link. In each experiment, we fixed the location of the gNB and move the UE with an increment of roughly one degrees. The table specifies the direction of user movement with respect to gNB-UE link, distance resolution, and the number of user locations for which we conduct channel measurements. Outdoor 30 m data also contains blockage between 3.9 m to 4.8 m. At each location, we scan the transmission beam and collect data for each beam. By doing so, we can get the full OFDM channels for different locations along the moving trajectory with all the beam angles. Moreover, we use 240 kHz subcarrier spacing, which is consistent with the 5G NR numerology at FR2, so the data we collect will be a true reflection of what a 5G UE will see. 



### <a href="https://github.com/ucsdwcsng/mMobile" style="background-color: white;"> Go to Datasets and code</a>


| Setting | LinkLen | MovingDir | Resol\. | #pts | Blockage     |
|:---------:|:-----:|:---------:|:-------:|:-------:|:------------:|
| Indoor  | 2\.5m   | 90$^o$    | 0\.1m   | 21      | No |
| Indoor  | 4\.2m   | 90$^o$    | 0\.1m   | 32      | No |
| Outdoor | 10m     | 90$^o$    | 0\.2m   | 31      | No |
| Outdoor | 30m     | 120$^o$   | 0\.6m   | 45      | Yes |
 	

