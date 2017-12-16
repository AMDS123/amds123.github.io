---
layout: post
title: "Challenges in Disentangling Independent Factors of Variation"
date: 2017-11-07 01:13:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Classification
author: Attila Szabó, Qiyang Hu, Tiziano Portenier, Matthias Zwicker, Paolo Favaro
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of building models that disentangle independent factors of variation. Such models could be used to encode features that can efficiently be used for classification and to transfer attributes between different images in image synthesis. As data we use a weakly labeled training set. Our weak labels indicate what single factor has changed between two data samples, although the relative value of the change is unknown. This labeling is of particular interest as it may be readily available without annotation costs. To make use of weak labels we introduce an autoencoder model and train it through constraints on image pairs and triplets. We formally prove that without additional knowledge there is no guarantee that two images with the same factor of variation will be mapped to the same feature. We call this issue the reference ambiguity. Moreover, we show the role of the feature dimensionality and adversarial training. We demonstrate experimentally that the proposed model can successfully transfer attributes on several datasets, but show also cases when the reference ambiguity occurs.

##### Abstract (translated by Google)
我们研究建立模型来解决独立变异因素的问题。这样的模型可以被用于编码可以有效地用于分类的特征，并且在图像合成中的不同图像之间传递属性。作为数据，我们使用一个弱标记的训练集。我们的弱标签表明两个数据样本之间单个因素发生了什么变化，但变化的相对值是未知的。这个标签是特别感兴趣的，因为它可以容易地获得而没有注释成本。为了使用弱标签，我们引入一个自编码器模型，并通过对图像对和三元组的约束来训练它。我们正式证明，没有额外的知识，就不能保证具有相同变异因子的两幅图像将被映射到相同的特征。我们把这个问题称为参考模糊。此外，我们还展示了特征维度和对抗性训练的作用。我们通过实验证明，所提出的模型可以在几个数据集上成功地传输属性，但也会显示出引用歧义发生的情况。

##### URL
[https://arxiv.org/abs/1711.02245](https://arxiv.org/abs/1711.02245)

##### PDF
[https://arxiv.org/pdf/1711.02245](https://arxiv.org/pdf/1711.02245)

