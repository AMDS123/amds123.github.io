---
layout: post
title: "Near Real-Time Data Labeling Using a Depth Sensor for EMG Based Prosthetic Arms"
date: 2018-11-10 11:59:56
categories: arXiv_CV
tags: arXiv_CV Face
author: Geesara Prathap, Titus Nanda Kumara, Roshan Ragel
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing sEMG (Surface Electromyography) signals belonging to a particular action (e.g., lateral arm raise) automatically is a challenging task as EMG signals themselves have a lot of variation even for the same action due to several factors. To overcome this issue, there should be a proper separation which indicates similar patterns repetitively for a particular action in raw signals. A repetitive pattern is not always matched because the same action can be carried out with different time duration. Thus, a depth sensor (Kinect) was used for pattern identification where three joint angles were recording continuously which is clearly separable for a particular action while recording sEMG signals. To Segment out a repetitive pattern in angle data, MDTW (Moving Dynamic Time Warping) approach is introduced. This technique is allowed to retrieve suspected motion of interest from raw signals. MDTW based on DTW algorithm, but it will be moving through the whole dataset in a pre-defined manner which is capable of picking up almost all the suspected segments inside a given dataset an optimal way. Elevated bicep curl and lateral arm raise movements are taken as motions of interest to show how the proposed technique can be employed to achieve auto identification and labelling. The full implementation is available at https://github.com/GPrathap/OpenBCIPython

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04239](http://arxiv.org/abs/1811.04239)

##### PDF
[http://arxiv.org/pdf/1811.04239](http://arxiv.org/pdf/1811.04239)

