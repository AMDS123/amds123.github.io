---
layout: post
title: "Revisiting Batch Normalization For Practical Domain Adaptation"
date: 2016-11-08 06:11:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Deep_Learning Detection
author: Yanghao Li, Naiyan Wang, Jianping Shi, Jiaying Liu, Xiaodi Hou
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNN) have shown unprecedented success in various computer vision applications such as image classification and object detection. However, it is still a common annoyance during the training phase, that one has to prepare at least thousands of labeled images to fine-tune a network to a specific domain. Recent study (Tommasi et al. 2015) shows that a DNN has strong dependency towards the training dataset, and the learned features cannot be easily transferred to a different but relevant task without fine-tuning. In this paper, we propose a simple yet powerful remedy, called Adaptive Batch Normalization (AdaBN) to increase the generalization ability of a DNN. By modulating the statistics in all Batch Normalization layers across the network, our approach achieves deep adaptation effect for domain adaptation tasks. In contrary to other deep learning domain adaptation methods, our method does not require additional components, and is parameter-free. It archives state-of-the-art performance despite its surprising simplicity. Furthermore, we demonstrate that our method is complementary with other existing methods. Combining AdaBN with existing domain adaptation treatments may further improve model performance.

##### Abstract (translated by Google)
深度神经网络（DNN）在诸如图像分类和对象检测等各种计算机视觉应用中已经取得了前所未有的成功。然而，在训练阶段，这仍然是一个普遍的烦恼，必须准备至少数千个标记的图像，以将网络微调到特定的领域。最近的研究（Tommasi等，2015）表明，DNN对训练数据集具有很强的依赖性，学习的特征不能轻易地转移到另一个相关的任务而不需要微调。在本文中，我们提出了一个简单而强大的补救措施，称为自适应批量标准化（AdaBN），以提高DNN的泛化能力。通过对网络中所有批量规范化层次的统计调整，我们的方法实现了对领域适应任务的深度适应效果。与其他深度学习领域适应方法相反，我们的方法不需要额外的组件，并且是无参数的。它存档了最先进的性能，尽管其惊人的简单性。此外，我们证明我们的方法是与其他现有方法互补的。将AdaBN与现有的领域适应处理相结合可能会进一步提高模型性能。

##### URL
[https://arxiv.org/abs/1603.04779](https://arxiv.org/abs/1603.04779)

##### PDF
[https://arxiv.org/pdf/1603.04779](https://arxiv.org/pdf/1603.04779)

