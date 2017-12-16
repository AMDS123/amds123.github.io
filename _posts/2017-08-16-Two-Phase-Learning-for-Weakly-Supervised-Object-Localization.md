---
layout: post
title: "Two-Phase Learning for Weakly Supervised Object Localization"
date: 2017-08-16 17:51:55
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Weakly_Supervised CNN Semantic_Segmentation Inference Prediction Detection
author: Dahun Kim, Donghyeon Cho, Donggeun Yoo, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised semantic segmentation and localiza- tion have a problem of focusing only on the most important parts of an image since they use only image-level annota- tions. In this paper, we solve this problem fundamentally via two-phase learning. Our networks are trained in two steps. In the first step, a conventional fully convolutional network (FCN) is trained to find the most discriminative parts of an image. In the second step, the activations on the most salient parts are suppressed by inference conditional feedback, and then the second learning is performed to find the area of the next most important parts. By combining the activations of both phases, the entire portion of the tar- get object can be captured. Our proposed training scheme is novel and can be utilized in well-designed techniques for weakly supervised semantic segmentation, salient region detection, and object location prediction. Detailed experi- ments demonstrate the effectiveness of our two-phase learn- ing in each task.

##### Abstract (translated by Google)
弱监督的语义分割和本地化有一个问题，只关注图像最重要的部分，因为他们只使用图像级别的注释。在本文中，我们从根本上通过两阶段学习来解决这个问题。我们的网络分两步进行训练。在第一步中，传统的完全卷积网络（FCN）被训练以找到图像的最有区别的部分。在第二步中，通过推理条件反馈抑制最显着部分上的激活，然后进行第二次学习以找出下一个最重要部分的面积。通过结合两个阶段的激活，可以捕获整个目标对象。我们提出的训练方案是新颖的，可以用于精心设计的技术，用于弱监督语义分割，显着区域检测和对象位置预测。详细的实验证明了我们两个阶段的学习在每个任务中的有效性。

##### URL
[https://arxiv.org/abs/1708.02108](https://arxiv.org/abs/1708.02108)

##### PDF
[https://arxiv.org/pdf/1708.02108](https://arxiv.org/pdf/1708.02108)

