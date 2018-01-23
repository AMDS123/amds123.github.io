---
layout: post
title: "Depth CNNs for RGB-D scene recognition: learning from scratch better than transferring from RGB-CNNs"
date: 2018-01-21 09:38:50
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised CNN Recognition
author: Xinhang Song, Luis Herranz, Shuqiang Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Scene recognition with RGB images has been extensively studied and has reached very remarkable recognition levels, thanks to convolutional neural networks (CNN) and large scene datasets. In contrast, current RGB-D scene data is much more limited, so often leverages RGB large datasets, by transferring pretrained RGB CNN models and fine-tuning with the target RGB-D dataset. However, we show that this approach has the limitation of hardly reaching bottom layers, which is key to learn modality-specific features. In contrast, we focus on the bottom layers, and propose an alternative strategy to learn depth features combining local weakly supervised training from patches followed by global fine tuning with images. This strategy is capable of learning very discriminative depth-specific features with limited depth images, without resorting to Places-CNN. In addition we propose a modified CNN architecture to further match the complexity of the model and the amount of data available. For RGB-D scene recognition, depth and RGB features are combined by projecting them in a common space and further leaning a multilayer classifier, which is jointly optimized in an end-to-end network. Our framework achieves state-of-the-art accuracy on NYU2 and SUN RGB-D in both depth only and combined RGB-D data.

##### Abstract (translated by Google)
由于卷积神经网络（CNN）和大型场景数据集，已经广泛研究了RGB图像的场景识别，并且已经达到了非常显着的识别水平。相比之下，当前的RGB-D场景数据受到的限制更多，因此通常会利用RGB大数据集，通过传输预训练的RGB CNN模型并与目标RGB-D数据集进行微调。然而，我们表明这种方法有几乎达不到底层的限制，这是学习特定模式特征的关键。相反，我们关注底层，并提出了一种可选择的策略来学习深度特征，这种深度特征结合了局部弱补偿跟踪全局微调的训练和图像。这种策略能够在深度图像有限的情况下学习深度特定的特征，而不必求助于Places-CNN。另外，我们提出了一个修改后的CNN架构来进一步匹配模型的复杂性和可用的数据量。对于RGB-D场景识别，深度和RGB特征通过将它们投影到公共空间中进行组合，并进一步倾斜在端到端网络中联合优化的多层分类器。我们的框架仅在深度和RGB-D数据两者中实现了NYU2和SUN RGB-D的最新精度。

##### URL
[https://arxiv.org/abs/1801.06797](https://arxiv.org/abs/1801.06797)

##### PDF
[https://arxiv.org/pdf/1801.06797](https://arxiv.org/pdf/1801.06797)

