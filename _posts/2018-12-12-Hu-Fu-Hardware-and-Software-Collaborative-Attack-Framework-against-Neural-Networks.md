---
layout: post
title: "Hu-Fu: Hardware and Software Collaborative Attack Framework against Neural Networks"
date: 2018-12-12 06:33:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Image_Classification Classification Deep_Learning Detection Recognition Face_Recognition
author: Wenshuo Li, Jincheng Yu, Xuefei Ning, Pengjun Wang, Qi Wei, Yu Wang, Huazhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Deep Learning (DL), especially Convolutional Neural Network (CNN), develops rapidly and is applied to many tasks, such as image classification, face recognition, image segmentation, and human detection. Due to its superior performance, DL-based models have a wide range of application in many areas, some of which are extremely safety-critical, e.g. intelligent surveillance and autonomous driving. Due to the latency and privacy problem of cloud computing, embedded accelerators are popular in these safety-critical areas. However, the robustness of the embedded DL system might be harmed by inserting hardware/software Trojans into the accelerator and the neural network model, since the accelerator and deploy tool (or neural network model) are usually provided by third-party companies. Fortunately, inserting hardware Trojans can only achieve inflexible attack, which means that hardware Trojans can easily break down the whole system or exchange two outputs, but can't make CNN recognize unknown pictures as targets. Though inserting software Trojans has more freedom of attack, it often requires tampering input images, which is not easy for attackers. So, in this paper, we propose a hardware-software collaborative attack framework to inject hidden neural network Trojans, which works as a back-door without requiring manipulating input images and is flexible for different scenarios. We test our attack framework for image classification and face recognition tasks, and get attack success rate of 92.6% and 100% on CIFAR10 and YouTube Faces, respectively, while keeping almost the same accuracy as the unattacked model in the normal mode. In addition, we show a specific attack scenario in which a face recognition system is attacked and gives a specific wrong answer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.05098](http://arxiv.org/abs/1805.05098)

##### PDF
[http://arxiv.org/pdf/1805.05098](http://arxiv.org/pdf/1805.05098)

