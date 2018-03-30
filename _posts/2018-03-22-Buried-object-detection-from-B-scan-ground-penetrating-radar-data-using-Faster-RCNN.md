---
layout: post
title: "Buried object detection from B-scan ground penetrating radar data using Faster-RCNN"
date: 2018-03-22 15:41:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Minh-Tan Pham, Sébastien Lefèvre
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we adapt the Faster-RCNN framework for the detection of underground buried objects (i.e. hyperbola reflections) in B-scan ground penetrating radar (GPR) images. Due to the lack of real data for training, we propose to incorporate more simulated radargrams generated from different configurations using the gprMax toolbox. Our designed CNN is first pre-trained on the grayscale Cifar-10 database. Then, the Faster-RCNN framework based on the pre-trained CNN is trained and fine-tuned on both real and simulated GPR data. Preliminary detection results show that the proposed technique can provide significant improvements compared to classical computer vision methods and hence becomes quite promising to deal with this kind of specific GPR data even with few training samples.

##### Abstract (translated by Google)
在本文中，我们采用Faster-RCNN框架来检测B扫描地面穿透雷达（GPR）图像中的地下埋藏物体（即双曲线反射）。由于缺乏训练的真实数据，我们建议使用gprMax工具箱合并更多不同配置生成的模拟雷达图。我们设计的CNN首先在灰度级Cifar-10数据库上进行预先培训。然后，基于预先训练的CNN的Faster-RCNN框架在实际和模拟GPR数据上进行训练和微调。初步检测结果表明，与传统的计算机视觉方法相比，所提出的技术可以提供显着的改进，因此即使只有很少的训练样本，也可以处理这种特定的GPR数据。

##### URL
[https://arxiv.org/abs/1803.08414](https://arxiv.org/abs/1803.08414)

##### PDF
[https://arxiv.org/pdf/1803.08414](https://arxiv.org/pdf/1803.08414)

