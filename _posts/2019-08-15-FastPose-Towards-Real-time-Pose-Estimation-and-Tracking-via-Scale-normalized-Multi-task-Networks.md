---
layout: post
title: "FastPose: Towards Real-time Pose Estimation and Tracking via Scale-normalized Multi-task Networks"
date: 2019-08-15 15:42:57
categories: arXiv_CV
tags: arXiv_CV Re-identification Pose_Estimation Tracking Person_Re-identification Detection
author: Jiabin Zhang, Zheng Zhu, Wei Zou, Peng Li, Yanwei Li, Hu Su, Guan Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Both accuracy and efficiency are significant for pose estimation and tracking in videos. State-of-the-art performance is dominated by two-stages top-down methods. Despite the leading results, these methods are impractical for real-world applications due to their separated architectures and complicated calculation. This paper addresses the task of articulated multi-person pose estimation and tracking towards real-time speed. An end-to-end multi-task network (MTN) is designed to perform human detection, pose estimation, and person re-identification (Re-ID) tasks simultaneously. To alleviate the performance bottleneck caused by scale variation problem, a paradigm which exploits scale-normalized image and feature pyramids (SIFP) is proposed to boost both performance and speed. Given the results of MTN, we adopt an occlusion-aware Re-ID feature strategy in the pose tracking module, where pose information is utilized to infer the occlusion state to make better use of Re-ID feature. In experiments, we demonstrate that the pose estimation and tracking performance improves steadily utilizing SIFP through different backbones. Using ResNet-18 and ResNet-50 as backbones, the overall pose tracking framework achieves competitive performance with 29.4 FPS and 12.2 FPS, respectively. Additionally, occlusion-aware Re-ID feature decreases the identification switches by 37% in the pose tracking process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05593](http://arxiv.org/abs/1908.05593)

##### PDF
[http://arxiv.org/pdf/1908.05593](http://arxiv.org/pdf/1908.05593)

