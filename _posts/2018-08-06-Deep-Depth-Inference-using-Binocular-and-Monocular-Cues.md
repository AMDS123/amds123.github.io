---
layout: post
title: "Deep Depth Inference using Binocular and Monocular Cues"
date: 2018-08-06 17:30:24
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
人类视觉系统依赖于双目立体线索和单眼焦点线索来获得有效的3D感知。在计算机视觉中，这两个问题传统上是在不同的轨道上解决的。在本文中，我们提出了一种统一的基于学习的技术，该技术同时使用两种类型的线索进行深度推理。具体来说，我们使用一对焦点堆栈作为输入来模拟人类感知。我们首先构建了一个由深度引导光场渲染合成的综合焦点堆栈训练数据集。然后，我们构建三个独立的网络：FocusNet从单个焦点堆栈中提取深度，EDoFNet从焦点堆栈获取扩展景深（EDoF）图像，以及StereoNet进行立体匹配。然后，我们将它们集成到统一的解决方案中，以获得高质量的深度图综合实验表明，我们的方法在准确性和速度方面都优于最先进的技术，并有效地模拟人类视觉系统。

##### URL
[http://arxiv.org/abs/1711.10729](http://arxiv.org/abs/1711.10729)

##### PDF
[http://arxiv.org/pdf/1711.10729](http://arxiv.org/pdf/1711.10729)

