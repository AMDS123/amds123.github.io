---
layout: post
title: "Real-to-Virtual Domain Unification for End-to-End Autonomous Driving"
date: 2018-09-06 05:11:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction Detection
author: Luona Yang, Xiaodan Liang, Tairui Wang, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
In the spectrum of vision-based autonomous driving, vanilla end-to-end models are not interpretable and suboptimal in performance, while mediated perception models require additional intermediate representations such as segmentation masks or detection bounding boxes, whose annotation can be prohibitively expensive as we move to a larger scale. More critically, all prior works fail to deal with the notorious domain shift if we were to merge data collected from different sources, which greatly hinders the model generalization ability. In this work, we address the above limitations by taking advantage of virtual data collected from driving simulators, and present DU-drive, an unsupervised real-to-virtual domain unification framework for end-to-end autonomous driving. It first transforms real driving data to its less complex counterpart in the virtual domain and then predicts vehicle control commands from the generated virtual image. Our framework has three unique advantages: 1) it maps driving data collected from a variety of source distributions into a unified domain, effectively eliminating domain shift; 2) the learned virtual representation is simpler than the input real image and closer in form to the "minimum sufficient statistic" for the prediction task, which relieves the burden of the compression phase while optimizing the information bottleneck tradeoff and leads to superior prediction performance; 3) it takes advantage of annotated virtual data which is unlimited and free to obtain. Extensive experiments on two public driving datasets and two driving simulators demonstrate the performance superiority and interpretive capability of DU-drive.

##### Abstract (translated by Google)
在基于视觉的自动驾驶的范围内，香草端到端模型在性能上是不可解释和次优的，而中介感知模型需要额外的中间表示，例如分割掩模或检测边界框，其注释可能过于昂贵，因为我们进一步扩大规模。更重要的是，如果我们要合并从不同来源收集的数据，所有先前的工作都无法处理臭名昭着的域转移，这极大地阻碍了模型的泛化能力。在这项工作中，我们通过利用从驾驶模拟器收集的虚拟数据来解决上述限制，并提出DU-drive，一种用于端到端自动驾驶的无监督的实际到虚拟域统一框架。它首先将实际驾驶数据转换为虚拟域中较不复杂的对应物，然后根据生成的虚拟图像预测车辆控制命令。我们的框架有三个独特的优势：1）它将从各种源分发中收集的驱动数据映射到统一域，有效地消除了域转移; 2）学习的虚拟表示比输入的实际图像更简单，并且形式更接近预测任务的“最小充分统计”，这减轻了压缩阶段的负担，同时优化了信息瓶颈权衡并导致了更好的预测性能; 3）它利用注释的虚拟数据，该数据是无限的，可以自由获取。两个公共驾驶数据集和两个驾驶模拟器的广泛实验证明了DU驱动器的性能优势和解释能力。

##### URL
[http://arxiv.org/abs/1801.03458](http://arxiv.org/abs/1801.03458)

##### PDF
[http://arxiv.org/pdf/1801.03458](http://arxiv.org/pdf/1801.03458)

