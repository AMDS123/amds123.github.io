---
layout: post
title: "LSUN: Construction of a Large-scale Image Dataset using Deep Learning with Humans in the Loop"
date: 2016-06-04 09:51:30
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Recognition
author: Fisher Yu, Ari Seff, Yinda Zhang, Shuran Song, Thomas Funkhouser, Jianxiong Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
While there has been remarkable progress in the performance of visual recognition algorithms, the state-of-the-art models tend to be exceptionally data-hungry. Large labeled training datasets, expensive and tedious to produce, are required to optimize millions of parameters in deep network models. Lagging behind the growth in model capacity, the available datasets are quickly becoming outdated in terms of size and density. To circumvent this bottleneck, we propose to amplify human effort through a partially automated labeling scheme, leveraging deep learning with humans in the loop. Starting from a large set of candidate images for each category, we iteratively sample a subset, ask people to label them, classify the others with a trained model, split the set into positives, negatives, and unlabeled based on the classification confidence, and then iterate with the unlabeled set. To assess the effectiveness of this cascading procedure and enable further progress in visual recognition research, we construct a new image dataset, LSUN. It contains around one million labeled images for each of 10 scene categories and 20 object categories. We experiment with training popular convolutional networks and find that they achieve substantial performance gains when trained on this dataset.

##### Abstract (translated by Google)
虽然在视觉识别算法的性能方面取得了显着的进步，但是最先进的模型往往是非常需要数据的。需要大量标记的训练数据集，昂贵且繁琐的生产，需要在深度网络模型中优化数百万个参数。在模型能力增长落后的情况下，可用数据集在大小和密度方面正在迅速变得过时。为了规避这一瓶颈，我们建议通过部分自动化的标签方案来扩大人力，利用循环中的人类进行深度学习。从每个类别的大量候选图像开始，我们迭代地对一个子集进行采样，要求人们给它们加标签，用一个训练好的模型对其他人进行分类，根据分类置信度将这个集合分为正数，负数和未标记数据，然后迭代未标记的集合。为了评估这种级联过程的有效性，并使视觉识别研究取得进一步的进展，我们构建了一个新的图像数据集LSUN。它包含10个场景类别和20个对象类别中的每一个的大约一百万个标记的图像。我们试验了流行的卷积网络的训练，发现在训练这个数据集时，他们获得了很大的性能提升。

##### URL
[https://arxiv.org/abs/1506.03365](https://arxiv.org/abs/1506.03365)

##### PDF
[https://arxiv.org/pdf/1506.03365](https://arxiv.org/pdf/1506.03365)

