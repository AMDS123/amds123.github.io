---
layout: post
title: "Joint Pixel and Feature-level Domain Adaptation in the Wild"
date: 2018-02-28 20:23:20
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Knowledge GAN Recognition
author: Luan Tran, Kihyuk Sohn, Xiang Yu, Xiaoming Liu, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Recent developments in deep domain adaptation have allowed knowledge transfer from a labeled source domain to an unlabeled target domain at the level of intermediate features or input pixels. We propose that advantages may be derived by combining them, in the form of different insights that lead to a novel design and complementary properties that result in better performance. At the feature level, inspired by insights from semi-supervised learning in a domain adversarial neural network, we propose a novel regularization in the form of domain adversarial entropy minimization. Next, we posit that insights from computer vision are more amenable to injection at the pixel level and specifically address the key challenge of adaptation across different semantic levels. In particular, we use 3D geometry and image synthesization based on a generalized appearance flow to preserve identity across higher-level pose transformations, while using an attribute-conditioned CycleGAN to translate a single source into multiple target images that differ in lower-level properties such as lighting. We validate on a novel problem of car recognition in unlabeled surveillance images using labeled images from the web, handling explicitly specified, nameable factors of variation through pixel-level and implicit, unspecified factors through feature-level adaptation. Extensive experiments achieve state-of-the-art results, demonstrating the effectiveness of complementing feature and pixel-level information via our proposed domain adaptation method.

##### Abstract (translated by Google)
最近在深度域适应方面的发展已经允许从中间特征或输入像素水平的标记源域到未标记目标域的知识转移。我们提出，可以通过将不同洞察结合在一起，通过结合它们来获得优势，从而形成新颖的设计和互补性能，从而实现更好的性能。在功能层面，受到领域对抗神经网络中半监督学习的启发，我们提出了一种以域对抗熵最小化为形式的新正则化。接下来，我们假定来自计算机视觉的见解更适合于像素级的注入，并特别针对跨不同语义层次的适应性关键挑战。具体而言，我们使用基于广义外观流的3D几何和图像合成来保持更高级别姿态变换中的身份，同时使用属性调节的CycleGAN将单个源转换为多个目标图像，这些图像在较低级属性作为照明。我们使用来自网络的标记图像验证未标记监视图像中的汽车识别的新问题，通过特征级适应处理通过像素级和隐含的，未指定的因素明确指定的，可命名的变异因子。广泛的实验获得了最新的结果，通过我们提出的领域自适应方法展示了补充特征和像素级信息的有效性。

##### URL
[http://arxiv.org/abs/1803.00068](http://arxiv.org/abs/1803.00068)

##### PDF
[http://arxiv.org/pdf/1803.00068](http://arxiv.org/pdf/1803.00068)

