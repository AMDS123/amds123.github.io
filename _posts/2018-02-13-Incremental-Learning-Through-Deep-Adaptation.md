---
layout: post
title: "Incremental Learning Through Deep Adaptation"
date: 2018-02-13 19:41:40
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Amir Rosenfeld, John K. Tsotsos
mathjax: true
---

* content
{:toc}

##### Abstract
Given an existing trained neural network, it is often desirable to learn new capabilities without hindering performance of those already learned. Existing approaches either learn sub-optimal solutions, require joint training, or incur a substantial increment in the number of parameters for each added domain, typically as many as the original network. We propose a method called \emph{Deep Adaptation Networks} (DAN) that constrains newly learned filters to be linear combinations of existing ones. DANs precisely preserve performance on the original domain, require a fraction (typically 13\%, dependent on network architecture) of the number of parameters compared to standard fine-tuning procedures and converge in less cycles of training to a comparable or better level of performance. When coupled with standard network quantization techniques, we further reduce the parameter cost to around 3\% of the original with negligible or no loss in accuracy. The learned architecture can be controlled to switch between various learned representations, enabling a single network to solve a task from multiple different domains. We conduct extensive experiments showing the effectiveness of our method on a range of image classification tasks and explore different aspects of its behavior.

##### Abstract (translated by Google)
鉴于现有的训练过的神经网络，通常需要学习新的能力而不妨碍已经学过的人的表现。现有的方法要么学习次优解决方案，需要联合培训，要么大大增加每个添加域的参数数量，通常与原始网络一样多。我们提出了一种称为\ emph {Deep Adaptation Networks}（DAN）的方法，将新学习的过滤器限制为现有过滤器的线性组合。 DAN在原始域中精确地保持性能，与标准微调程序相比，需要一小部分（通常取决于网络架构的13％）的参数数量，并且在较少的训练周期内收敛到相当或更好的性能水平。当与标准网络量化技术相结合时，我们将参数成本进一步降低到原来的3％左右，精度可以忽略不计或没有损失。可以控制学习的体系结构以在各种学习表示之间切换，从而使单个网络能够解决来自多个不同领域的任务。我们进行了广泛的实验，展示了我们的方法在一系列图像分类任务中的有效性，并探索了其行为的不同方面。

##### URL
[http://arxiv.org/abs/1705.04228](http://arxiv.org/abs/1705.04228)

##### PDF
[http://arxiv.org/pdf/1705.04228](http://arxiv.org/pdf/1705.04228)

