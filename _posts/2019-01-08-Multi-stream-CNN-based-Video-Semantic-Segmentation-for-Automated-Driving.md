---
layout: post
title: "Multi-stream CNN based Video Semantic Segmentation for Automated Driving"
date: 2019-01-08 20:45:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation RNN
author: Ganesh Sistu, Sumanth Chennupati, Senthil Yogamani
mathjax: true
---

* content
{:toc}

##### Abstract
Majority of semantic segmentation algorithms operate on a single frame even in the case of videos. In this work, the goal is to exploit temporal information within the algorithm model for leveraging motion cues and temporal consistency. We propose two simple high-level architectures based on Recurrent FCN (RFCN) and Multi-Stream FCN (MSFCN) networks. In case of RFCN, a recurrent network namely LSTM is inserted between the encoder and decoder. MSFCN combines the encoders of different frames into a fused encoder via 1x1 channel-wise convolution. We use a ResNet50 network as the baseline encoder and construct three networks namely MSFCN of order 2 &amp; 3 and RFCN of order 2. MSFCN-3 produces the best results with an accuracy improvement of 9% and 15% for Highway and New York-like city scenarios in the SYNTHIA-CVPR'16 dataset using mean IoU metric. MSFCN-3 also produced 11% and 6% for SegTrack V2 and DAVIS datasets over the baseline FCN network. We also designed an efficient version of MSFCN-2 and RFCN-2 using weight sharing among the two encoders. The efficient MSFCN-2 provided an improvement of 11% and 5% for KITTI and SYNTHIA with negligible increase in computational complexity compared to the baseline version.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02511](http://arxiv.org/abs/1901.02511)

##### PDF
[http://arxiv.org/pdf/1901.02511](http://arxiv.org/pdf/1901.02511)

