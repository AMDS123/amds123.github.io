---
layout: post
title: "Crafting GBD-Net for Object Detection"
date: 2016-10-08 20:36:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Xingyu Zeng, Wanli Ouyang, Junjie Yan, Hongsheng Li, Tong Xiao, Kun Wang, Yu Liu, Yucong Zhou, Bin Yang, Zhe Wang, Hui Zhou, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The visual cues from multiple support regions of different sizes and resolutions are complementary in classifying a candidate box in object detection. Effective integration of local and contextual visual cues from these regions has become a fundamental problem in object detection. In this paper, we propose a gated bi-directional CNN (GBD-Net) to pass messages among features from different support regions during both feature learning and feature extraction. Such message passing can be implemented through convolution between neighboring support regions in two directions and can be conducted in various layers. Therefore, local and contextual visual patterns can validate the existence of each other by learning their nonlinear relationships and their close interactions are modeled in a more complex way. It is also shown that message passing is not always helpful but dependent on individual samples. Gated functions are therefore needed to control message transmission, whose on-or-offs are controlled by extra visual evidence from the input sample. The effectiveness of GBD-Net is shown through experiments on three object detection datasets, ImageNet, Pascal VOC2007 and Microsoft COCO. This paper also shows the details of our approach in wining the ImageNet object detection challenge of 2016, with source code provided on \url{this https URL}.

##### Abstract (translated by Google)
来自不同大小和分辨率的多个支持区域的视觉线索在对物体检测中的候选盒进行分类时是相辅相成的。从这些地区有效整合本地和上下文的视觉线索已成为目标检测的根本问题。在本文中，我们提出了一种门控双向CNN（GBD-Net），用于在特征学习和特征提取过程中在不同支持区域的特征之间传递消息。这种消息传递可以通过两个方向上的相邻支撑区域之间的卷积来实现，并且可以在各个层次上进行。因此，局部的和背景的视觉模式可以通过学习他们的非线性关系来验证彼此的存在，他们的密切相互作用是以更复杂的方式建模的。这也表明消息传递并不总是有帮助，但依赖于个别样本。因此，门控功能需要控制消息传输，其开或关由输入样本的额外视觉证据控制。通过对ImageNet，Pascal VOC2007和Microsoft COCO三个对象检测数据集的实验，证明了GBD-Net的有效性。本文还详细介绍了我们在获取2016年ImageNet对象检测挑战方面的方法，并在\ url {this https URL}上提供了源代码。

##### URL
[https://arxiv.org/abs/1610.02579](https://arxiv.org/abs/1610.02579)

##### PDF
[https://arxiv.org/pdf/1610.02579](https://arxiv.org/pdf/1610.02579)

