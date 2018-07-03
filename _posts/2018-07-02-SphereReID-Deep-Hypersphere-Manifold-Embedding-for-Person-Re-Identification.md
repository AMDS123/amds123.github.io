---
layout: post
title: "SphereReID: Deep Hypersphere Manifold Embedding for Person Re-Identification"
date: 2018-07-02 08:53:01
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding CNN Classification
author: Xing Fan, Wei Jiang, Hao Luo, Mengjuan Fei,
mathjax: true
---

* content
{:toc}

##### Abstract
Many current successful Person Re-Identification(ReID) methods train a model with the softmax loss function to classify images of different persons and obtain the feature vectors at the same time. However, the underlying feature embedding space is ignored. In this paper, we use a modified softmax function, termed Sphere Softmax, to solve the classification problem and learn a hypersphere manifold embedding simultaneously. A balanced sampling strategy is also introduced. Finally, we propose a convolutional neural network called SphereReID adopting Sphere Softmax and training a single model end-to-end with a new warming-up learning rate schedule on four challenging datasets including Market-1501, DukeMTMC-reID, CHHK-03, and CUHK-SYSU. Experimental results demonstrate that this single model outperforms the state-of-the-art methods on all four datasets without fine-tuning or re-ranking. For example, it achieves 94.4% rank-1 accuracy on Market-1501 and 83.9% rank-1 accuracy on DukeMTMC-reID. The code and trained weights of our model will be released.

##### Abstract (translated by Google)
许多当前成功的人员重新识别（ReID）方法训练具有softmax损失函数的模型以对不同人的图像进行分类并同时获得特征向量。但是，忽略了底层特征嵌入空间。在本文中，我们使用改进的softmax函数，称为Sphere Softmax，来解决分类问题并同时学习超球面流形嵌入。还引入了平衡抽样策略。最后，我们提出了一个名为SphereReID的卷积神经网络，采用Sphere Softmax，并在四个具有挑战性的数据集（包括Market-1501，DukeMTMC-reID，CHHK-03）和一个新的预热学习速率计划中端到端地训练单个模型。香港中文大学，中山大学。实验结果表明，该单一模型在所有四个数据集上均优于最先进的方法，无需进行微调或重新排序。例如，它在Market-1501上达到94.4％的一级准确度，在DukeMTMC-reID上达到83.9％的一级精度。我们的模型的代码和训练重量将被释放。

##### URL
[http://arxiv.org/abs/1807.00537](http://arxiv.org/abs/1807.00537)

##### PDF
[http://arxiv.org/pdf/1807.00537](http://arxiv.org/pdf/1807.00537)

