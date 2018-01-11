---
layout: post
title: "Unsupervised Real-to-Virtual Domain Unification for End-to-End Highway Driving"
date: 2018-01-10 17:08:54
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction Detection
author: Luona Yang, Xiaodan Liang, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
In the spectrum of vision-based autonomous driving, vanilla end-to-end models are not interpretable and suboptimal in performance, while mediated perception models require additional intermediate representations such as segmentation masks or detection bounding boxes, whose annotation can be prohibitively expensive as we move to a larger scale. Raw images and existing intermediate representations are also loaded with nuisance details that are irrelevant to the prediction of vehicle commands, e.g. the style of the car in front or the view beyond the road boundaries. More critically, all prior works fail to deal with the notorious domain shift if we were to merge data collected from different sources, which greatly hinders the model generalization ability. In this work, we address the above limitations by taking advantage of virtual data collected from driving simulators, and present DU-drive, an unsupervised real to virtual domain unification framework for end-to-end driving. It transforms real driving data to its canonical representation in the virtual domain, from which vehicle control commands are predicted. Our framework has several advantages: 1) it maps driving data collected from different source distributions into a unified domain, 2) it takes advantage of annotated virtual data which is free to obtain, 3) it learns an interpretable, canonical representation of driving image that is specialized for vehicle command prediction. Extensive experiments on two public highway driving datasets clearly demonstrate the performance superiority and interpretive capability of DU-drive.

##### Abstract (translated by Google)
在基于视觉的自主驾驶的范围中，香草端到端模型在性能上是不可理解的，并且是次优的，而中介感知模型需要额外的中间表示，例如分割掩模或检测边界框，其注解可能是非常昂贵的，因为我们转向更大的规模。原始图像和现有的中间表示也加载有与车辆命令的预测无关的烦扰细节，例如，前方车的风格或超越道路界限的视野。更重要的是，如果我们合并从不同来源收集的数据，所有以前的工作都不能应对臭名昭着的域名转移，这极大地阻碍了模型的泛化能力。在这项工作中，我们通过利用从驾驶模拟器收集的虚拟数据来解决上述限制，并且提出了DU-驱动，一种无监督的真实到虚拟域统一框架，用于端到端驾驶。它将实际驾驶数据转换为虚拟领域中的规范表示，从中预测车辆控制命令。我们的框架有几个优点：1）将从不同源分布中收集的驾驶数据映射到一个统一的域中; 2）利用注释的虚拟数据，这是免费获得的; 3）它学习了一个可解释的，专门用于车辆指挥预测。两个公路行驶数据集的大量实验清楚地表明了DU驱动的性能优势和解释能力。

##### URL
[https://arxiv.org/abs/1801.03458](https://arxiv.org/abs/1801.03458)

##### PDF
[https://arxiv.org/pdf/1801.03458](https://arxiv.org/pdf/1801.03458)

