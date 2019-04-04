---
layout: post
title: "End-to-end Binaural Sound Localisation from the Raw Waveform"
date: 2019-04-03 11:07:46
categories: arXiv_SD
tags: arXiv_SD CNN
author: Paolo Vecchiotti, Ning Ma, Stefano Squartini, Guy J. Brown
mathjax: true
---

* content
{:toc}

##### Abstract
A novel end-to-end binaural sound localisation approach is proposed which estimates the azimuth of a sound source directly from the waveform. Instead of employing hand-crafted features commonly employed for binaural sound localisation, such as the interaural time and level difference, our end-to-end system approach uses a convolutional neural network (CNN) to extract specific features from the waveform that are suitable for localisation. Two systems are proposed which differ in the initial frequency analysis stage. The first system is auditory-inspired and makes use of a gammatone filtering layer, while the second system is fully data-driven and exploits a trainable convolutional layer to perform frequency analysis. In both systems, a set of dedicated convolutional kernels are then employed to search for specific localisation cues, which are coupled with a localisation stage using fully connected layers. Localisation experiments using binaural simulation in both anechoic and reverberant environments show that the proposed systems outperform a state-of-the-art deep neural network system. Furthermore, our investigation of the frequency analysis stage in the second system suggests that the CNN is able to exploit different frequency bands for localisation according to the characteristics of the reverberant environment.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01916](https://arxiv.org/abs/1904.01916)

##### PDF
[https://arxiv.org/pdf/1904.01916](https://arxiv.org/pdf/1904.01916)

