---
layout: post
title: "Anticipating many futures: Online human motion prediction and synthesis for human-robot collaboration"
date: 2017-02-27 10:02:40
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Judith Bütepage, Hedvig Kjellström, Danica Kragic
mathjax: true
---

* content
{:toc}

##### Abstract
Fluent and safe interactions of humans and robots require both partners to anticipate the others' actions. A common approach to human intention inference is to model specific trajectories towards known goals with supervised classifiers. However, these approaches do not take possible future movements into account nor do they make use of kinematic cues, such as legible and predictable motion. The bottleneck of these methods is the lack of an accurate model of general human motion. In this work, we present a conditional variational autoencoder that is trained to predict a window of future human motion given a window of past frames. Using skeletal data obtained from RGB depth images, we show how this unsupervised approach can be used for online motion prediction for up to 1660 ms. Additionally, we demonstrate online target prediction within the first 300-500 ms after motion onset without the use of target specific training data. The advantage of our probabilistic approach is the possibility to draw samples of possible future motions. Finally, we investigate how movements and kinematic cues are represented on the learned low dimensional manifold.

##### Abstract (translated by Google)
人类和机器人的流畅和安全的交互需要合作伙伴预测他人的行为。人类意图推断的一种常见方法是用监督分类器为已知目标建立特定的轨迹。但是，这些方法不会考虑将来的移动，也不会利用运动学的线索，如可读的和可预测的运动。这些方法的瓶颈在于缺乏一般人体运动的精确模型。在这项工作中，我们提出了一个条件变分自动编码器，它被训练来预测未来人类运动的窗口给定一个过去的窗口的窗口。使用从RGB深度图像获得的骨架数据，我们展示了这种无监督的方法如何能够用于在线运动预测长达1660毫秒。此外，我们在运动发生后的第一个300-500毫秒内展示在线目标预测，而不使用目标特定训练数据。我们的概率方法的优点是可以绘制未来可能的运动样本。最后，我们研究如何在学习的低维流形上表示运动和运动线索。

##### URL
[https://arxiv.org/abs/1702.08212](https://arxiv.org/abs/1702.08212)

##### PDF
[https://arxiv.org/pdf/1702.08212](https://arxiv.org/pdf/1702.08212)

