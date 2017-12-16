---
layout: post
title: "Learning Deep Representations for Scene Labeling with Semantic Context Guided Supervision"
date: 2017-06-09 04:15:55
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Zhe Wang, Hongsheng Li, Wanli Ouyang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Scene labeling is a challenging classification problem where each input image requires a pixel-level prediction map. Recently, deep-learning-based methods have shown their effectiveness on solving this problem. However, we argue that the large intra-class variation provides ambiguous training information and hinders the deep models' ability to learn more discriminative deep feature representations. Unlike existing methods that mainly utilize semantic context for regularizing or smoothing the prediction map, we design novel supervisions from semantic context for learning better deep feature representations. Two types of semantic context, scene names of images and label map statistics of image patches, are exploited to create label hierarchies between the original classes and newly created subclasses as the learning supervisions. Such subclasses show lower intra-class variation, and help CNN detect more meaningful visual patterns and learn more effective deep features. Novel training strategies and network structure that take advantages of such label hierarchies are introduced. Our proposed method is evaluated extensively on four popular datasets, Stanford Background (8 classes), SIFTFlow (33 classes), Barcelona (170 classes) and LM+Sun datasets (232 classes) with 3 different networks structures, and show state-of-the-art performance. The experiments show that our proposed method makes deep models learn more discriminative feature representations without increasing model size or complexity.

##### Abstract (translated by Google)
场景标记是一个具有挑战性的分类问题，其中每个输入图像需要像素级别的预测图。最近，基于深度学习的方法在解决这个问题上表现出了有效性。然而，我们认为，大的类内变异提供了模糊的训练信息，并阻碍了深层模型学习更具辨别性的深度特征表示的能力。与现有的主要利用语义上下文对预测图进行正则化或平滑处理的方法不同，我们从语义上下文中设计新的监督学习，以便学习更好的深度特征表示。利用两种语义语境，图像的场景名称和图像块的标签图统计，在原始类和新创建的子类之间创建标签层次作为学习监督。这样的小类表现出更低的课堂内变化，并且帮助CNN检测更有意义的视觉模式并学习更有效的深层特征。介绍了利用这种标签层次结构的新型训练策略和网络结构。我们提出的方法在三种不同的网络结构的四个流行数据集，斯坦福背景（8类），SIFTFlow（33类），巴塞罗那（170类）和LM + Sun数据集（232类）上进行了广泛的评估，最先进的表现。实验表明，本文提出的方法使得深层模型能够在不增加模型大小和复杂度的情况下，学习更多的判别性特征表示。

##### URL
[https://arxiv.org/abs/1706.02493](https://arxiv.org/abs/1706.02493)

##### PDF
[https://arxiv.org/pdf/1706.02493](https://arxiv.org/pdf/1706.02493)

