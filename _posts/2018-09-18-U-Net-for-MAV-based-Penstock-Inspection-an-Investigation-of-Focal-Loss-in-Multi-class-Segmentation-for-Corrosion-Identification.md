---
layout: post
title: "U-Net for MAV-based Penstock Inspection: an Investigation of Focal Loss in Multi-class Segmentation for Corrosion Identification"
date: 2018-09-18 08:04:42
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Ty Nguyen, Tolga Ozaslan, Ian D. Miller, James Keller, Giuseppe Loianno, Camillo J. Taylor, Daniel D. Lee, Vijay Kumar, Joseph H. Harwood, Jennifer Wozencraft
mathjax: true
---

* content
{:toc}

##### Abstract
Periodical inspection and maintenance of critical infrastructure such as dams, penstocks, and locks are of significant importance to prevent catastrophic failures. Conventional manual inspection methods require inspectors to climb along a penstock to spot corrosion, rust and crack formation which is unsafe, labor-intensive, and requires intensive training. This work presents an alternative approach using a Micro Aerial Vehicle (MAV) that autonomously flies to collect imagery which is then fed into a pretrained deep-learning model to identify corrosion. Our simplified U-Net trained with less than 40 image samples can do inference at 12 fps on a single GPU. We analyze different loss functions to solve the class imbalance problem, followed by a discussion on choosing proper metrics and weights for object classes. Results obtained with the dataset collected from Center Hill Dam, TN show that focal loss function, combined with a proper set of class weights yield better segmentation results than the base loss, Softmax cross entropy. Our method can be used in combination with planning algorithm to offer a complete, safe and cost-efficient solution to autonomous infrastructure inspection.

##### Abstract (translated by Google)
定期检查和维护关键基础设施，如水坝，压力水管和锁具，对于防止灾难性故障具有重要意义。传统的人工检查方法要求检查员沿着压力钢管攀爬以发现腐蚀，生锈和裂缝形成，这是不安全的，劳动密集型的，并且需要强化训练。这项工作提出了一种使用微型飞行器（MAV）的替代方法，该微型飞行器自动飞行以收集图像，然后将图像馈送到预训练的深度学习模型中以识别腐蚀。我们使用少于40个图像样本训练的简化U-Net可以在单个GPU上以12 fps进行推理。我们分析了不同的损失函数来解决类不平衡问题，然后讨论为对象类选择适当的度量和权重。使用从田纳西州中山坝收集的数据集获得的结果显示，焦点损失函数与适当的类权重集合产生比基本损失Softmax交叉熵更好的分割结果。我们的方法可以与规划算法结合使用，为自主基础设施检查提供完整，安全和具有成本效益的解决方案。

##### URL
[https://arxiv.org/abs/1809.06576](https://arxiv.org/abs/1809.06576)

##### PDF
[https://arxiv.org/pdf/1809.06576](https://arxiv.org/pdf/1809.06576)

