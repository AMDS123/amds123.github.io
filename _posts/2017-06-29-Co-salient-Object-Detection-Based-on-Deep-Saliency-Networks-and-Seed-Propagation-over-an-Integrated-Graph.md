---
layout: post
title: "Co-salient Object Detection Based on Deep Saliency Networks and Seed Propagation over an Integrated Graph"
date: 2017-06-29 09:40:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Detection
author: Dong-ju Jeong, Insung Hwang, Nam Ik Cho
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a co-salient object detection method to find common salient regions in a set of images. We utilize deep saliency networks to transfer co-saliency prior knowledge and better capture high-level semantic information, and the resulting initial co-saliency maps are enhanced by seed propagation steps over an integrated graph. The deep saliency networks are trained in a supervised manner to avoid online weakly supervised learning and exploit them not only to extract high-level features but also to produce both intra- and inter-image saliency maps. Through a refinement step, the initial co-saliency maps can uniformly highlight co-salient regions and locate accurate object boundaries. To handle input image groups inconsistent in size, we propose to pool multi-regional descriptors including both within-segment and within-group information. In addition, the integrated multilayer graph is constructed to find the regions that the previous steps may not detect by seed propagation with low-level descriptors. In this work, we utilize the useful complementary components of high-, low-level information, and several learning-based steps. Our experiments have demonstrated that the proposed approach outperforms comparable co-saliency detection methods on widely used public databases and can also be directly applied to co-segmentation tasks.

##### Abstract (translated by Google)
本文提出了一种用于在一组图像中寻找共同显着区域的共显着物体检测方法。我们利用深度显着性网络来传递先前知识的共同显着性，并更好地捕获高级语义信息，并且通过种子传播步骤在整合图上增强所产生的初始共同显着性图。深度显着性网络以监督方式进行训练，以避免在线弱监督学习，并利用它们不仅提取高级特征，而且还产生图像内和图像间显着图。通过精化步骤，初始共同显着性图可以统一地突出显示共同显着区域并定位准确的对象边界。为了处理大小不一致的输入图像组，我们建议汇集包括分段内和分组内信息的多区域描述符。另外，构建综合多层图以找出以前的步骤可能无法通过种子传播用低级描述符检测的区域。在这项工作中，我们利用高级，低级信息的有用补充成分和几个基于学习的步骤。我们的实验已经证明，所提出的方法在广泛使用的公共数据库上优于可比较的协同显着性检测方法，并且也可以直接应用于协同分割任务。

##### URL
[https://arxiv.org/abs/1706.09650](https://arxiv.org/abs/1706.09650)

##### PDF
[https://arxiv.org/pdf/1706.09650](https://arxiv.org/pdf/1706.09650)

