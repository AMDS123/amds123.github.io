---
layout: post
title: "Do Better ImageNet Models Transfer Better?"
date: 2018-05-23 06:12:35
categories: arXiv_CV
tags: arXiv_CV Image_Classification Transfer_Learning Classification Relation
author: Simon Kornblith, Jonathon Shlens, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Transfer learning has become a cornerstone of computer vision with the advent of ImageNet features, yet little work has been done to evaluate the performance of ImageNet architectures across different datasets. An implicit hypothesis in modern computer vision research is that models that perform better on ImageNet necessarily perform better on other vision tasks. However, this hypothesis has never been systematically tested. Here, we compare the performance of 13 classification models on 12 image classification tasks in three settings: as fixed feature extractors, fine-tuned, and trained from random initialization. We find that, when networks are used as fixed feature extractors, ImageNet accuracy is only weakly predictive of accuracy on other tasks ($r^2=0.24$). In this setting, ResNets consistently outperform networks that achieve higher accuracy on ImageNet. When networks are fine-tuned, we observe a substantially stronger correlation ($r^2 = 0.86$). We achieve state-of-the-art performance on eight image classification tasks simply by fine-tuning state-of-the-art ImageNet architectures, outperforming previous results based on specialized methods for transfer learning. Finally, we observe that, on three small fine-grained image classification datasets, networks trained from random initialization perform similarly to ImageNet-pretrained networks. Together, our results show that ImageNet architectures generalize well across datasets, with small improvements in ImageNet accuracy producing improvements across other tasks, but ImageNet features are less general than previously suggested.

##### Abstract (translated by Google)
随着ImageNet特性的出现，转移学习已经成为计算机视觉的基石，但是很少有人在评估不同数据集中ImageNet体系结构的性能。现代计算机视觉研究中的一个隐含假设是，在ImageNet上执行得更好的模型必须在其他视觉任务上表现得更好。然而，这个假设从来没有经过系统的测试。在这里，我们比较了12种图像分类任务中的13种分类模型在三种设置下的性能：作为固定特征提取器，微调和从随机初始化训练。我们发现，当网络被用作固定特征提取器时，ImageNet的准确性只能对其他任务的准确性有微弱的预测（$ r ^ 2 = 0.24 $）。在此设置中，ResNet一直比在ImageNet上实现更高精度的网络性能更出色。当网络进行微调时，我们观察到一个更强的相关性（$ r ^ 2 = 0.86 $）。我们通过微调最先进的ImageNet架构，在八种图像分类任务上实现了最先进的性能，超越了基于专门的转移学习方法的结果。最后，我们观察到，在三个小的细粒度图像分类数据集上，从随机初始化训练的网络执行类似于ImageNet预训练网络。我们的研究结果一起表明，ImageNet架构能够很好地跨数据集进行泛化，ImageNet准确度略有提高，可以在其他任务中实现改进，但是ImageNet功能比先前建议的要少。

##### URL
[http://arxiv.org/abs/1805.08974](http://arxiv.org/abs/1805.08974)

##### PDF
[http://arxiv.org/pdf/1805.08974](http://arxiv.org/pdf/1805.08974)

