---
layout: post
title: "Less is More: Simultaneous View Classification and Landmark Detection for Abdominal Ultrasound Images"
date: 2018-05-25 21:55:09
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Classification Detection
author: Zhoubing Xu, Yuankai Huo, JinHyeong Park, Bennett Landman, Andy Milkowski, Sasa Grbic, Shaohua Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
An abdominal ultrasound examination, which is the most common ultrasound examination, requires substantial manual efforts to acquire standard abdominal organ views, annotate the views in texts, and record clinically relevant organ measurements. Hence, automatic view classification and landmark detection of the organs can be instrumental to streamline the examination workflow. However, this is a challenging problem given not only the inherent difficulties from the ultrasound modality, e.g., low contrast and large variations, but also the heterogeneity across tasks, i.e., one classification task for all views, and then one landmark detection task for each relevant view. While convolutional neural networks (CNN) have demonstrated more promising outcomes on ultrasound image analytics than traditional machine learning approaches, it becomes impractical to deploy multiple networks (one for each task) due to the limited computational and memory resources on most existing ultrasound scanners. To overcome such limits, we propose a multi-task learning framework to handle all the tasks by a single network. This network is integrated to perform view classification and landmark detection simultaneously; it is also equipped with global convolutional kernels, coordinate constraints, and a conditional adversarial module to leverage the performances. In an experimental study based on 187,219 ultrasound images, with the proposed simplified approach we achieve (1) view classification accuracy better than the agreement between two clinical experts and (2) landmark-based measurement errors on par with inter-user variability. The multi-task approach also benefits from sharing the feature extraction during the training process across all tasks and, as a result, outperforms the approaches that address each task individually.

##### Abstract (translated by Google)
腹部超声检查是最常见的超声检查，需要大量的手动操作来获取标准的腹腔器官视野，注释文本中的观点，并记录临床相关的器官测量。因此，器官的自动视图分类和界标检测可以有助于简化检查工作流程。然而，这是一个具有挑战性的问题，不仅因为超声波模态的固有困难，例如低对比度和大变化，而且跨任务的异质性，即所有视图的一个分类任务，以及每个视图的一个标志检测任务相关观点。尽管卷积神经网络（CNN）在超声图像分析方面比传统的机器学习方法显示出更有希望的结果，但由于大多数现有超声扫描仪上的计算和存储资源有限，部署多个网络（每个任务一个网络）变得不切实际。为了克服这些限制，我们提出了一个多任务学习框架来处理单个网络的所有任务。该网络被集成以同时执行视图分类和界标检测;它还配备了全局卷积核，坐标约束和有条件的对抗模块以利用性能。在基于187,219个超声图像的实验研究中，使用所提出的简化方法，我们实现了（1）比两个临床专家之间的一致性更好的观察分类准确度，以及（2）与用户间可变性相当的基于地标的测量误差。多任务方法还可以在训练过程中共享所有任务期间的特征提取，并因此优于单独解决每个任务的方法。

##### URL
[http://arxiv.org/abs/1805.10376](http://arxiv.org/abs/1805.10376)

##### PDF
[http://arxiv.org/pdf/1805.10376](http://arxiv.org/pdf/1805.10376)

