---
layout: post
title: "Self-Paced Learning with Adaptive Deep Visual Embeddings"
date: 2018-07-24 16:01:00
categories: arXiv_CV
tags: arXiv_CV Salient Embedding CNN Image_Classification Classification Recognition
author: Vithursan Thangarasa, Graham W. Taylor
mathjax: true
---

* content
{:toc}

##### Abstract
Selecting the most appropriate data examples to present a deep neural network (DNN) at different stages of training is an unsolved challenge. Though practitioners typically ignore this problem, a non-trivial data scheduling method may result in a significant improvement in both convergence and generalization performance. In this paper, we introduce Self-Paced Learning with Adaptive Deep Visual Embeddings (SPL-ADVisE), a novel end-to-end training protocol that unites self-paced learning (SPL) and deep metric learning (DML). We leverage the Magnet Loss to train an embedding convolutional neural network (CNN) to learn a salient representation space. The student CNN classifier dynamically selects similar instance-level training examples to form a mini-batch, where the easiness from the cross-entropy loss and the true diverseness of examples from the learned metric space serve as sample importance priors. To demonstrate the effectiveness of SPL-ADVisE, we use deep CNN architectures for the task of supervised image classification on several coarse- and fine-grained visual recognition datasets. Results show that, across all datasets, the proposed method converges faster and reaches a higher final accuracy than other SPL variants, particularly on fine-grained classes.

##### Abstract (translated by Google)
选择最合适的数据示例以在不同的训练阶段呈现深度神经网络（DNN）是一个未解决的挑战。虽然从业者通常忽略了这个问题，但是非平凡的数据调度方法可以导致收敛和泛化性能的显着改进。在本文中，我们介绍了自适应深度视觉嵌入的自学习（SPL-ADVisE），这是一种新颖的端到端训练协议，它将自定进度学习（SPL）和深度量学习（DML）结合在一起。我们利用Magnet Loss训练嵌入卷积神经网络（CNN）来学习显着的表示空间。学生CNN分类器动态地选择类似的实例级训练示例以形成小批量，其中来自交叉熵损失的容易性和来自所学习的度量空间的示例的真实多样性用作样本重要性先验。为了证明SPL-ADVisE的有效性，我们使用深度CNN架构来完成几个粗粒度和细粒度视觉识别数据集的监督图像分类任务。结果表明，在所有数据集中，所提出的方法收敛速度更快，并且达到比其他SPL变体更高的最终精度，特别是在细粒度类上。

##### URL
[https://arxiv.org/abs/1807.09200](https://arxiv.org/abs/1807.09200)

##### PDF
[https://arxiv.org/pdf/1807.09200](https://arxiv.org/pdf/1807.09200)

