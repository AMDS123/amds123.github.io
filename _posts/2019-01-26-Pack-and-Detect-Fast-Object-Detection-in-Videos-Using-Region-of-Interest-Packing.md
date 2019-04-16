---
layout: post
title: "Pack and Detect: Fast Object Detection in Videos Using Region-of-Interest Packing"
date: 2019-01-26 02:46:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Summarization Tracking Object_Tracking Detection Relation
author: Athindran Ramesh Kumar, Balaraman Ravindran, Anand Raghunathan
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection in videos is an important task in computer vision for various applications such as object tracking, video summarization and video search. Although great progress has been made in improving the accuracy of object detection in recent years due to the rise of deep neural networks, the state-of-the-art algorithms are highly computationally intensive. In order to address this challenge, we make two important observations in the context of videos: (i) Objects often occupy only a small fraction of the area in each video frame, and (ii) There is a high likelihood of strong temporal correlation between consecutive frames. Based on these observations, we propose Pack and Detect (PaD), an approach to reduce the computational requirements of object detection in videos. In PaD, only selected video frames called anchor frames are processed at full size. In the frames that lie between anchor frames (inter-anchor frames), regions of interest (ROIs) are identified based on the detections in the previous frame. We propose an algorithm to pack the ROIs of each inter-anchor frame together into a reduced-size frame. The computational requirements of the detector are reduced due to the lower size of the input. In order to maintain the accuracy of object detection, the proposed algorithm expands the ROIs greedily to provide additional background around each object to the detector. PaD can use any underlying neural network architecture to process the full-size and reduced-size frames. Experiments using the ImageNet video object detection dataset indicate that PaD can potentially reduce the number of FLOPS required for a frame by $4\times$. This leads to an overall increase in throughput of $1.25\times$ on a 2.1 GHz Intel Xeon server with a NVIDIA Titan X GPU at the cost of $1.1\%$ drop in accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.01701](https://arxiv.org/abs/1809.01701)

##### PDF
[https://arxiv.org/pdf/1809.01701](https://arxiv.org/pdf/1809.01701)

