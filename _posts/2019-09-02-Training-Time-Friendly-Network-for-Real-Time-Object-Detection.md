---
layout: post
title: "Training-Time-Friendly Network for Real-Time Object Detection"
date: 2019-09-02 12:59:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection
author: Zili Liu, Tu Zheng, Guodong Xu, Zheng Yang, Haifeng Liu, Deng Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Modern object detectors can rarely achieve short training time, fast inference speed, and high accuracy at the same time. To strike a balance between them, we propose the Training-Time-Friendly Network (TTFNet). In this work, we start with light-head, single-stage, and anchor-free designs, enabling fast inference speed. Then, we focus on shortening training time. We notice that producing more high-quality samples plays a similar role as increasing batch size, which helps enlarge the learning rate and accelerate the training process. To this end, we introduce a novel method using Gaussian kernels to produce training samples. Moreover, we design the initiative sample weights for better information utilization. Experiments on MS COCO show that our TTFNet has great advantages in balancing training time, inference speed, and accuracy. It has reduced training time by more than seven times compared to previous real-time detectors while maintaining state-of-the-art performances. In addition, our super-fast version of TTFNet-18 and TTFNet-53 can outperform SSD300 and YOLOv3 by less than one-tenth of their training time, respectively. Code has been made available at \url{https://github.com/ZJULearning/ttfnet}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00700](http://arxiv.org/abs/1909.00700)

##### PDF
[http://arxiv.org/pdf/1909.00700](http://arxiv.org/pdf/1909.00700)

