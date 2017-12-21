---
layout: post
title: "DeepFuse: A Deep Unsupervised Approach for Exposure Fusion with Extreme Exposure Image Pairs"
date: 2017-12-20 09:47:51
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Quantitative
author: K. Ram Prabhakar, V. Sai Srikar, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel deep learning architecture for fusing static multi-exposure images. Current multi-exposure fusion (MEF) approaches use hand-crafted features to fuse input sequence. However, the weak hand-crafted representations are not robust to varying input conditions. Moreover, they perform poorly for extreme exposure image pairs. Thus, it is highly desirable to have a method that is robust to varying input conditions and capable of handling extreme exposure without artifacts. Deep representations have known to be robust to input conditions and have shown phenomenal performance in a supervised setting. However, the stumbling block in using deep learning for MEF was the lack of sufficient training data and an oracle to provide the ground-truth for supervision. To address the above issues, we have gathered a large dataset of multi-exposure image stacks for training and to circumvent the need for ground truth images, we propose an unsupervised deep learning framework for MEF utilizing a no-reference quality metric as loss function. The proposed approach uses a novel CNN architecture trained to learn the fusion operation without reference ground truth image. The model fuses a set of common low level features extracted from each image to generate artifact-free perceptually pleasing results. We perform extensive quantitative and qualitative evaluation and show that the proposed technique outperforms existing state-of-the-art approaches for a variety of natural images.

##### Abstract (translated by Google)
我们提出了一种融合静态多重曝光图像的新型深度学习架构。目前的多重曝光融合（MEF）方法使用手工制作的特征来融合输入序列。然而，手工制作的表示对于不同的输入条件并不稳健。而且，对于极端曝光的图像对，它们表现不佳。因此，非常希望有一种对变化的输入条件稳健并且能够处理没有伪影的极端曝光的方法。已知深度表示对于输入条件是强健的，并且在监督环境下显示出惊人的性能。然而，MEF深入学习的绊脚石却是缺乏足够的训练数据和一个预言来为监督提供基础真相。为了解决上述问题，我们收集了一个用于训练的多重曝光图像堆栈的大数据集，并且为了规避对地面真实图像的需要，我们提出了一个无监督的MEF深度学习框架，它使用无参考质量度量作为损失函数。所提出的方法使用经过训练的新颖的CNN架构来学习融合操作，而无需参考地面真实图像。该模型融合了从每个图像中提取的一组常见的低级特征，以产生无伪影的令人满意的结果。我们进行广泛的定量和定性评估，并表明所提出的技术胜过现有的各种自然图像的最先进的方法。

##### URL
[https://arxiv.org/abs/1712.07384](https://arxiv.org/abs/1712.07384)

##### PDF
[https://arxiv.org/pdf/1712.07384](https://arxiv.org/pdf/1712.07384)

