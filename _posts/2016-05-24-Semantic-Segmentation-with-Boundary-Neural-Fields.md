---
layout: post
title: "Semantic Segmentation with Boundary Neural Fields"
date: 2016-05-24 23:32:10
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Optimization Prediction Quantitative Detection
author: Gedas Bertasius, Jianbo Shi, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
The state-of-the-art in semantic segmentation is currently represented by fully convolutional networks (FCNs). However, FCNs use large receptive fields and many pooling layers, both of which cause blurring and low spatial resolution in the deep layers. As a result FCNs tend to produce segmentations that are poorly localized around object boundaries. Prior work has attempted to address this issue in post-processing steps, for example using a color-based CRF on top of the FCN predictions. However, these approaches require additional parameters and low-level features that are difficult to tune and integrate into the original network architecture. Additionally, most CRFs use color-based pixel affinities, which are not well suited for semantic segmentation and lead to spatially disjoint predictions. To overcome these problems, we introduce a Boundary Neural Field (BNF), which is a global energy model integrating FCN predictions with boundary cues. The boundary information is used to enhance semantic segment coherence and to improve object localization. Specifically, we first show that the convolutional filters of semantic FCNs provide good features for boundary detection. We then employ the predicted boundaries to define pairwise potentials in our energy. Finally, we show that our energy decomposes semantic segmentation into multiple binary problems, which can be relaxed for efficient global optimization. We report extensive experiments demonstrating that minimization of our global boundary-based energy yields results superior to prior globalization methods, both quantitatively as well as qualitatively.

##### Abstract (translated by Google)
语义分割的最新技术目前由完全卷积网络（FCN）来表示。然而，FCNs使用较大的感受野和许多汇合层，这两者在深层中造成模糊和低空间分辨率。因此，FCN倾向于产生在对象边界周围定位不好的分割。之前的工作试图在后处理步骤中解决这个问题，例如在FCN预测之上使用基于颜色的CRF。然而，这些方法需要额外的参数和低级特征，难以调整和整合到原有的网络架构中。此外，大多数CRF使用基于颜色的像素亲和力，这不太适合于语义分割并导致空间不相交的预测。为了克服这些问题，我们引入了边界神经场（BNF），这是一个整合FCN预测与边界线索的全球能量模型。边界信息用于增强语义片段的连贯性并改善对象的定位。具体来说，我们首先证明语义FCN的卷积滤波器为边界检测提供了良好的特征。然后我们使用预测的界限来定义我们能量中的成对势。最后，我们展示了我们的能量将语义分割分解成多个二元问题，可以放松高效的全局优化。我们报告了广泛的实验，证明了我们的全球边界能量收益最小化的结果优于先前的全球化方法，无论是在数量上还是质量上。

##### URL
[https://arxiv.org/abs/1511.02674](https://arxiv.org/abs/1511.02674)

##### PDF
[https://arxiv.org/pdf/1511.02674](https://arxiv.org/pdf/1511.02674)

