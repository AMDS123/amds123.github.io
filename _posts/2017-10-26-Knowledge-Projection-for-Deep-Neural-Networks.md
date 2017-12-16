---
layout: post
title: "Knowledge Projection for Deep Neural Networks"
date: 2017-10-26 01:30:00
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Zhi Zhang, Guanghan Ning, Zhihai He
mathjax: true
---

* content
{:toc}

##### Abstract
While deeper and wider neural networks are actively pushing the performance limits of various computer vision and machine learning tasks, they often require large sets of labeled data for effective training and suffer from extremely high computational complexity. In this paper, we will develop a new framework for training deep neural networks on datasets with limited labeled samples using cross-network knowledge projection which is able to improve the network performance while reducing the overall computational complexity significantly. Specifically, a large pre-trained teacher network is used to observe samples from the training data. A projection matrix is learned to project this teacher-level knowledge and its visual representations from an intermediate layer of the teacher network to an intermediate layer of a thinner and faster student network to guide and regulate its training process. Both the intermediate layers from the teacher network and the injection layers from the student network are adaptively selected during training by evaluating a joint loss function in an iterative manner. This knowledge projection framework allows us to use crucial knowledge learned by large networks to guide the training of thinner student networks, avoiding over-fitting, achieving better network performance, and significantly reducing the complexity. Extensive experimental results on benchmark datasets have demonstrated that our proposed knowledge projection approach outperforms existing methods, improving accuracy by up to 4% while reducing network complexity by 4 to 10 times, which is very attractive for practical applications of deep neural networks.

##### Abstract (translated by Google)
虽然更深更广的神经网络正在积极地推动各种计算机视觉和机器学习任务的性能极限，但他们通常需要大量标记数据来进行有效的训练，并且计算复杂度极高。在本文中，我们将开发一个新的框架，使用跨网络知识投影在有限的标记样本的数据集上训练深度神经网络，能够在提高网络性能的同时显着降低整体计算复杂度。具体来说，一个大的预先训练的教师网络被用来观察来自训练数据的样本。学习投影矩阵将这个教师水平的知识及其从教师网络的中间层的视觉表示投射到更薄更快的学生网络的中间层，以指导和调节其训练过程。教师网络的中间层和学生网络的注入层在训练期间通过以迭代方式评估联合损失函数来自适应地选择。这种知识投影框架使我们能够利用大型网络学到的关键知识来指导较薄的学生网络的训练，避免过度拟合，实现更好的网络性能，并显着降低复杂性。在基准数据集上的广泛实验结果表明，我们提出的知识投影方法优于现有的方法，精度提高了4％，网络复杂度降低了4〜10倍，这对深度神经网络的实际应用非常有吸引力。

##### URL
[https://arxiv.org/abs/1710.09505](https://arxiv.org/abs/1710.09505)

##### PDF
[https://arxiv.org/pdf/1710.09505](https://arxiv.org/pdf/1710.09505)

