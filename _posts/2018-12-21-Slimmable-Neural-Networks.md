---
layout: post
title: "Slimmable Neural Networks"
date: 2018-12-21 03:36:48
categories: arXiv_AI
tags: arXiv_AI Object_Detection Segmentation Classification Detection
author: Jiahui Yu, Linjie Yang, Ning Xu, Jianchao Yang, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple and general method to train a single neural network executable at different widths (number of channels in a layer), permitting instant and adaptive accuracy-efficiency trade-offs at runtime. Instead of training individual networks with different width configurations, we train a shared network with switchable batch normalization. At runtime, the network can adjust its width on the fly according to on-device benchmarks and resource constraints, rather than downloading and offloading different models. Our trained networks, named slimmable neural networks, achieve similar (and in many cases better) ImageNet classification accuracy than individually trained models of MobileNet v1, MobileNet v2, ShuffleNet and ResNet-50 at different widths respectively. We also demonstrate better performance of slimmable models compared with individual ones across a wide range of applications including COCO bounding-box object detection, instance segmentation and person keypoint detection without tuning hyper-parameters. Lastly we visualize and discuss the learned features of slimmable networks. Code and models are available at: https://github.com/JiahuiYu/slimmable_networks

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08928](http://arxiv.org/abs/1812.08928)

##### PDF
[http://arxiv.org/pdf/1812.08928](http://arxiv.org/pdf/1812.08928)

