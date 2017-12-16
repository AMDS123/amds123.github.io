---
layout: post
title: "Hierarchical Model for Long-term Video Prediction"
date: 2017-07-03 06:27:39
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN RNN Prediction
author: Peter Wang, Zhongxia Yan, Jeff Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Video prediction has been an active topic of research in the past few years. Many algorithms focus on pixel-level predictions, which generates results that blur and disintegrate within a few frames. In this project, we use a hierarchical approach for long-term video prediction. We aim at estimating high-level structure in the input frame first, then predict how that structure grows in the future. Finally, we use an image analogy network to recover a realistic image from the predicted structure. Our method is largely adopted from the work by Villegas et al. The method is built with a combination of LSTMs and analogy-based convolutional auto-encoder networks. Additionally, in order to generate more realistic frame predictions, we also adopt adversarial loss. We evaluate our method on the Penn Action dataset, and demonstrate good results on high-level long-term structure prediction.

##### Abstract (translated by Google)
视频预测在过去几年一直是一个活跃的研究课题。许多算法专注于像素级预测，这会在几帧内产生模糊和分解的结果。在这个项目中，我们使用分层方法进行长期视频预测。我们的目标是先估计输入框架中的高层次结构，然后预测未来结构如何增长。最后，我们使用图像类比网络从预测的结构中恢复出真实的图像。我们的方法大部分来自Villegas等人的工作。该方法由LSTM和基于类比的卷积自动编码器网络组合而成。另外，为了产生更逼真的帧预测，我们也采取对抗性的损失。我们在宾夕法尼亚大学行动数据集上评估我们的方法，并在高层次的长期结构预测上展示出良好的结果。

##### URL
[https://arxiv.org/abs/1706.08665](https://arxiv.org/abs/1706.08665)

##### PDF
[https://arxiv.org/e-print/1706.08665](https://arxiv.org/e-print/1706.08665)

