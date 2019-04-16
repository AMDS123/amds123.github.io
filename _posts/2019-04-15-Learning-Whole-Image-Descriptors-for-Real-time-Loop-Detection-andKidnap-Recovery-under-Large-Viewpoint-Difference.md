---
layout: post
title: "Learning Whole-Image Descriptors for Real-time Loop Detection andKidnap Recovery under Large Viewpoint Difference"
date: 2019-04-15 11:01:04
categories: arXiv_RO
tags: arXiv_RO Weakly_Supervised Detection SLAM
author: Manohar Kuse, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a real-time stereo visual-inertial-SLAM system which is able to recover from complicatedkidnap scenarios and failures online in realtime. We propose to learn the whole-image-descriptorin a weakly supervised manner based on NetVLAD and decoupled convolutions. We analyse thetraining difficulties in using standard loss formulations and propose an allpairloss and show itseffect through extensive experiments. Compared to standard NetVLAD, our network takes an orderof magnitude fewer computations and model parameters, as a result runs about three times faster.We evaluate the representation power of our descriptor on standard datasets with precision-recall.Unlike previous loop detection methods which have been evaluated only on fronto-parallel revisits,we evaluate the performace of our method with competing methods on scenarios involving largeviewpoint difference. Finally, we present the fully functional system with relative computation andhandling of multiple world co-ordinate system which is able to reduce odometry drift, recover fromcomplicated kidnap scenarios and random odometry failures. We open source our fully functional system as an add-on for the popular VINS-Fusion.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06962](http://arxiv.org/abs/1904.06962)

##### PDF
[http://arxiv.org/pdf/1904.06962](http://arxiv.org/pdf/1904.06962)

