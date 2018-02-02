---
layout: post
title: "Deep Depth Inference using Binocular and Monocular Cues"
date: 2018-02-01 09:39:21
categories: arXiv_CV
tags: arXiv_CV Inference
author: Xinqing Guo, Zhang Chen, Siyuan Li, Yang Yang, Jingyi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Human visual system relies on both binocular stereo cues and monocular focusness cues to gain effective 3D perception. In computer vision, the two problems are traditionally solved in separate tracks. In this paper, we present a unified learning-based technique that simultaneously uses both types of cues for depth inference. Specifically, we use a pair of focal stacks as input to emulate human perception. We first construct a comprehensive focal stack training dataset synthesized by depth-guided light field rendering. We then construct three individual networks: a FocusNet to extract depth from a single focal stack, a EDoFNet to obtain the extended depth of field (EDoF) image from the focal stack, and a StereoNet to conduct stereo matching. We then integrate them into a unified solution to obtain high quality depth maps. Comprehensive experiments show that our approach outperforms the state-of-the-art in both accuracy and speed and effectively emulates human vision systems.

##### Abstract (translated by Google)
人类视觉系统依靠双眼立体声线索和单眼聚焦线索来获得有效的3D感知。在计算机视觉中，这两个问题传统上是分开来解决的。在本文中，我们提出了一个统一的基于学习的技术，同时使用这两种类型的线索深度推断。具体来说，我们使用一对焦点堆栈作为输入来模拟人类的感知。我们首先构建一个由深度引导光场渲染合成的综合焦点堆栈训练数据集。然后，我们构建了三个单独的网络：FocusNet从单个焦点堆栈中提取深度，从焦点堆栈获取扩展景深（EDoF）图像的EDoFNet以及进行立体匹配的StereoNet。然后，我们将它们整合到统一的解决方案中，以获得高质量的深度图全面的实验表明，我们的方法在准确性和速度方面都超过了最新的水平，并且有效地模拟了人类的视觉系统。

##### URL
[http://arxiv.org/abs/1711.10729](http://arxiv.org/abs/1711.10729)

##### PDF
[http://arxiv.org/pdf/1711.10729](http://arxiv.org/pdf/1711.10729)

