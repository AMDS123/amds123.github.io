---
layout: post
title: "FANTrack: 3D Multi-Object Tracking with Feature Association Network"
date: 2019-05-07 23:26:03
categories: arXiv_AI
tags: arXiv_AI Tracking CNN Object_Tracking Optimization Inference Deep_Learning Detection
author: Erkan Baser, Venkateshwaran Balasubramanian, Prarthana Bhattacharyya, Krzysztof Czarnecki
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a data-driven approach to online multi-object tracking (MOT) that uses a convolutional neural network (CNN) for data association in a tracking-by-detection framework. The problem of multi-target tracking aims to assign noisy detections to a-priori unknown and time-varying number of tracked objects across a sequence of frames. A majority of the existing solutions focus on either tediously designing cost functions or formulating the task of data association as a complex optimization problem that can be solved effectively. Instead, we exploit the power of deep learning to formulate the data association problem as inference in a CNN. To this end, we propose to learn a similarity function that combines cues from both image and spatial features of objects. Our solution learns to perform global assignments in 3D purely from data, handles noisy detections and a varying number of targets, and is easy to train. We evaluate our approach on the challenging KITTI dataset and show competitive results. Our code is available at https://git.uwaterloo.ca/wise-lab/fantrack.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02843](http://arxiv.org/abs/1905.02843)

##### PDF
[http://arxiv.org/pdf/1905.02843](http://arxiv.org/pdf/1905.02843)

