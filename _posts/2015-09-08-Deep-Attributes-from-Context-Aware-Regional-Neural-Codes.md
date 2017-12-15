---
layout: post
title: "Deep Attributes from Context-Aware Regional Neural Codes"
date: 2015-09-08 17:53:54
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Jianwei Luo, Jianguo Li, Jun Wang, Zhiguo Jiang, Yurong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, many researches employ middle-layer output of convolutional neural network models (CNN) as features for different visual recognition tasks. Although promising results have been achieved in some empirical studies, such type of representations still suffer from the well-known issue of semantic gap. This paper proposes so-called deep attribute framework to alleviate this issue from three aspects. First, we introduce object region proposals as intermedia to represent target images, and extract features from region proposals. Second, we study aggregating features from different CNN layers for all region proposals. The aggregation yields a holistic yet compact representation of input images. Results show that cross-region max-pooling of soft-max layer output outperform all other layers. As soft-max layer directly corresponds to semantic concepts, this representation is named "deep attributes". Third, we observe that only a small portion of generated regions by object proposals algorithm are correlated to classification target. Therefore, we introduce context-aware region refining algorithm to pick out contextual regions and build context-aware classifiers. We apply the proposed deep attributes framework for various vision tasks. Extensive experiments are conducted on standard benchmarks for three visual recognition tasks, i.e., image classification, fine-grained recognition and visual instance retrieval. Results show that deep attribute approaches achieve state-of-the-art results, and outperforms existing peer methods with a significant margin, even though some benchmarks have little overlap of concepts with the pre-trained CNN models.

##### Abstract (translated by Google)
最近，许多研究采用卷积神经网络模型（CNN）的中间层输出作为不同视觉识别任务的特征。虽然在一些实证研究中已经取得了有希望的结果，但是这种表征仍然存在众所周知的语义鸿沟问题。本文从三个方面提出所谓的深层属性框架来缓解这个问题。首先引入对象区域提案作为中间媒介来表示目标图像，并从区域提议中提取特征。其次，我们研究所有区域提案的不同CNN层次的聚合特征。聚合产生输入图像的整体而紧凑的表示。结果显示软 - 最大层输出的跨区域最大池优于其他所有层。由于软 - 最大层直接对应于语义概念，所以这种表示被称为“深层属性”。第三，我们观察到，只有一小部分的生成区域的对象提议算法与分类目标相关。因此，我们引入上下文感知区域细化算法来挑选上下文区域，并构建上下文感知的分类器。我们将所提出的深度属性框架应用于各种视觉任务。针对三种视觉识别任务的标准基准进行了大量的实验，即图像分类，细粒度识别和视觉实例检索。结果表明，深度属性方法达到了最新的结果，即使有些基准与预先训练的CNN模型的概念重叠不大，但其性能也优于现有的对等方法。

##### URL
[https://arxiv.org/abs/1509.02470](https://arxiv.org/abs/1509.02470)

##### PDF
[https://arxiv.org/pdf/1509.02470](https://arxiv.org/pdf/1509.02470)

