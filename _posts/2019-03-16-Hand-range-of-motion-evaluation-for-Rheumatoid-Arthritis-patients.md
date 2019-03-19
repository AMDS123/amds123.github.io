---
layout: post
title: "Hand range of motion evaluation for Rheumatoid Arthritis patients"
date: 2019-03-16 15:51:23
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking CNN
author: Luciano Walenty Xavier Cejnog, Roberto Marcondes Cesar Jr., Teofilo Emidio de Campos, Valeria Meirelles Carril Elui
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a framework for dynamic evaluation of the fingers movements: flexion, extension, abduction and adduction. This framework estimates angle measurements from joints computed by a hand pose estimation algorithm using a depth sensor (Realsense SR300). Given depth maps as input, our framework uses Pose-REN, which is a state-of-art hand pose estimation method that estimates 3D hand joint positions using a deep convolutional neural network. The pose estimation algorithm runs in real-time, allowing users to visualise 3D skeleton tracking results at the same time as the depth images are acquired. Once 3D joint poses are obtained, our framework estimates a plane containing the wrist and MCP joints and measures flexion/extension and abduction/aduction angles by applying computational geometry operations with respect to this plane. We analysed flexion and abduction movement patterns using real data, extracting the movement trajectories. Our preliminary results show that this method allows an automatic discrimination of hands with Rheumatoid Arthritis (RA) and healthy patients. The angle between joints can be used as an indicative of current movement capabilities and function. Although the measurements can be noisy and less accurate than those obtained statically through goniometry, the acquisition is much easier, non-invasive and patient-friendly, which shows the potential of our approach. The system can be used with and without orthosis. Our framework allows the acquisition of measurements with minimal intervention and significantly reduces the evaluation time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06949](http://arxiv.org/abs/1903.06949)

##### PDF
[http://arxiv.org/pdf/1903.06949](http://arxiv.org/pdf/1903.06949)

