---
layout: post
title: "Semantically Consistent Image Completion with Fine-grained Details"
date: 2017-11-26 07:42:17
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Pengpeng Liu, Xiaojuan Qi, Pinjia He, Yikang Li, Michael R. Lyu, Irwin King
mathjax: true
---

* content
{:toc}

##### Abstract
Image completion has achieved significant progress due to advances in generative adversarial networks (GANs). Albeit natural-looking, the synthesized contents still lack details, especially for scenes with complex structures or images with large holes. This is because there exists a gap between low-level reconstruction loss and high-level adversarial loss. To address this issue, we introduce a perceptual network to provide mid-level guidance, which measures the semantical similarity between the synthesized and original contents in a similarity-enhanced space. We conduct a detailed analysis on the effects of different losses and different levels of perceptual features in image completion, showing that there exist complementarity between adversarial training and perceptual features. By combining them together, our model can achieve nearly seamless fusion results in an end-to-end manner. Moreover, we design an effective lightweight generator architecture, which can achieve effective image inpainting with far less parameters. Evaluated on CelebA Face and Paris StreetView dataset, our proposed method significantly outperforms existing methods.

##### Abstract (translated by Google)
由于生成敌对网络（GAN）的进步，图像完成取得了显着进展。虽然自然，但合成的内容仍然缺乏细节，特别是对于结构复杂的场景或大的图像。这是因为低水平的重建损失与高水平的对抗性损失之间存在差距。为了解决这个问题，我们引入了一个感知网络来提供中级的指导，这个指导测量了一个相似性增强空间中合成内容和原始内容之间的语义相似性。对图像完成中不同损失和不同级别感知特征的影响进行详细分析，表明对抗性训练与感知特征之间存在互补性。通过将它们结合在一起，我们的模型可以以端到端的方式实现近乎无缝的融合结果。此外，我们设计了一个有效的轻量级发生器架构，可以实现有效的图像修复，参数少得多。在CelebA Face和Paris StreetView数据集上评估，我们提出的方法明显优于现有的方法。

##### URL
[https://arxiv.org/abs/1711.09345](https://arxiv.org/abs/1711.09345)

##### PDF
[https://arxiv.org/pdf/1711.09345](https://arxiv.org/pdf/1711.09345)

