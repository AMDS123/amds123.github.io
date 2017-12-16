---
layout: post
title: "Transfer learning from synthetic to real images using variational autoencoders for robotic applications"
date: 2017-09-20 08:18:07
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning
author: Tadanobu Inoue, Subhajit Chaudhury, Giovanni De Magistris, Sakyasingha Dasgupta
mathjax: true
---

* content
{:toc}

##### Abstract
Robotic learning in simulation environments provides a faster, more scalable, and safer training methodology than learning directly with physical robots. Also, synthesizing images in a simulation environment for collecting large-scale image data is easy, whereas capturing camera images in the real world is time consuming and expensive. However, learning from only synthetic images may not achieve the desired performance in real environments due to the gap between synthetic and real images. We thus propose a method that transfers learned capability of detecting object position from a simulation environment to the real world. Our method enables us to use only a very limited dataset of real images while leveraging a large dataset of synthetic images using multiple variational autoencoders. It detects object positions 6 to 7 times more precisely than the baseline of directly learning from the dataset of the real images. Object position estimation under varying environmental conditions forms one of the underlying requirement for standard robotic manipulation tasks. We show that the proposed method performs robustly in different lighting conditions or with other distractor objects present for this requirement. Using this detected object position, we transfer pick-and-place or reaching tasks learned in a simulation environment to an actual physical robot without re-training.

##### Abstract (translated by Google)
模拟环境中的机器人学习提供了比直接学习物理机器人更快，更可扩展，更安全的培训方法。而且，在用于收集大规模图像数据的模拟环境中合成图像是容易的，而在现实世界中捕获照相机图像是耗时且昂贵的。然而，由于合成和真实图像之间的差距，仅从合成图像学习可能无法在实际环境中达到期望的性能。因此，我们提出了一种将学习到的物体位置检测能力从模拟环境转移到现实世界的方法。我们的方法使我们能够仅使用非常有限的真实图像数据集，同时利用多变量自动编码器利用合成图像的大数据集。它比从真实图像的数据集中直接学习的基线更准确地检测对象位置6到7倍。在不同环境条件下进行目标位置估计是标准机器人操作任务的基本要求之一。我们表明，所提出的方法在不同的照明条件下执行鲁棒性或与此要求存在的其他干扰对象。使用这个检测到的对象位置，我们将在模拟环境中学习到的拾取或放置任务传送给实际的物理机器人，而不需要重新训练。

##### URL
[https://arxiv.org/abs/1709.06762](https://arxiv.org/abs/1709.06762)

##### PDF
[https://arxiv.org/pdf/1709.06762](https://arxiv.org/pdf/1709.06762)

