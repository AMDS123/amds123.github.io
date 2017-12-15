---
layout: post
title: "Describing Human Aesthetic Perception by Deeply-learned Attributes from Flickr"
date: 2016-05-25 01:30:12
categories: arXiv_CV
tags: arXiv_CV CNN
author: L. Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Many aesthetic models in computer vision suffer from two shortcomings: 1) the low descriptiveness and interpretability of those hand-crafted aesthetic criteria (i.e., nonindicative of region-level aesthetics), and 2) the difficulty of engineering aesthetic features adaptively and automatically toward different image sets. To remedy these problems, we develop a deep architecture to learn aesthetically-relevant visual attributes from Flickr1, which are localized by multiple textual attributes in a weakly-supervised setting. More specifically, using a bag-ofwords (BoW) representation of the frequent Flickr image tags, a sparsity-constrained subspace algorithm discovers a compact set of textual attributes (e.g., landscape and sunset) for each image. Then, a weakly-supervised learning algorithm projects the textual attributes at image-level to the highly-responsive image patches at pixel-level. These patches indicate where humans look at appealing regions with respect to each textual attribute, which are employed to learn the visual attributes. Psychological and anatomical studies have shown that humans perceive visual concepts hierarchically. Hence, we normalize these patches and feed them into a five-layer convolutional neural network (CNN) to mimick the hierarchy of human perceiving the visual attributes. We apply the learned deep features on image retargeting, aesthetics ranking, and retrieval. Both subjective and objective experimental results thoroughly demonstrate the competitiveness of our approach.

##### Abstract (translated by Google)
计算机视觉中的许多审美模式都有两个缺点：1）那些手工制作的审美标准（即区域美学的非指定性）的描述性和可解释性较低; 2）工程审美特征难以自适应地自动地朝不同的方向发展图像集。为了解决这些问题，我们开发了一个深层次的体系结构来学习Flickr1中与美学相关的视觉属性，这些属性在弱监督环境下被多个文本属性所定位。更具体地，使用频繁Flickr图像标签的BagWord（BoW）表示，稀疏约束子空间算法发现每个图像的紧凑文本属性集合（例如，风景和日落）。然后，弱监督学习算法将图像级的文本属性投影到像素级的高度响应的图像块。这些补丁显示了人类在每个文本属性看上诉区域的位置，这些文本属性被用来学习视觉属性。心理学和解剖学研究表明，人类对等级的视觉概念感知。因此，我们将这些补丁标准化，并将它们馈送到五层卷积神经网络（CNN）中以模仿人类感知视觉属性的层次结构。我们将学习的深度特征应用于图像重定位，美学排名和检索。主观和客观的实验结果都充分证明了我们的方法的竞争力。

##### URL
[https://arxiv.org/abs/1605.07699](https://arxiv.org/abs/1605.07699)

##### PDF
[https://arxiv.org/pdf/1605.07699](https://arxiv.org/pdf/1605.07699)

