---
layout: post
title: "Leveraging Heteroscedastic Aleatoric Uncertainties for Robust Real-Time LiDAR 3D Object Detection"
date: 2019-02-03 12:25:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection
author: Di Feng, Lars Rosenbaum, Fabian Timm, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a robust real-time LiDAR 3D object detector that leverages heteroscedastic aleatoric uncertainties to significantly improve its detection performance. A multi-loss function is designed to incorporate uncertainty estimations predicted by auxiliary output layers. Using our proposed method, the network ignores to train from noisy samples, and focuses more on informative ones. We validate our method on the KITTI object detection benchmark. Our method surpasses the baseline method which does not explicitly estimate uncertainties by up to nearly 9% in terms of Average Precision (AP). It also produces state-of-the-art results compared to other methods while running with an inference time of only 72 ms. In addition, we conduct extensive experiments to understand how aleatoric uncertainties behave. Extracting aleatoric uncertainties brings almost no additional computation cost during the deployment, making our method highly desirable for autonomous driving applications.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.05590](https://arxiv.org/abs/1809.05590)

##### PDF
[https://arxiv.org/pdf/1809.05590](https://arxiv.org/pdf/1809.05590)

