---
layout: post
title: "Recurrent Saliency Transformation Network: Incorporating Multi-Stage Visual Cues for Small Organ Segmentation"
date: 2017-11-18 21:12:22
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation GAN Optimization Prediction
author: Qihang Yu, Lingxi Xie, Yan Wang, Yuyin Zhou, Elliot K. Fishman, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
We aim at segmenting small organs (e.g., the pancreas) from abdominal CT scans. As the target often occupies a relatively small region in the input image, deep neural networks can be easily confused by the complex and variable background. To alleviate this, researchers proposed a coarse-to-fine approach, which used prediction from the first (coarse) stage to indicate a smaller input region for the second (fine) stage. Despite its effectiveness, this algorithm dealt with two stages individually, which lacked optimizing a global energy function, and limited its ability to incorporate multi-stage visual cues. Missing contextual information led to unsatisfying convergence in iterations, and that the fine stage sometimes produced even lower segmentation accuracy than the coarse stage. This paper presents a Recurrent Saliency Transformation Network. The key innovation is a saliency transformation module, which repeatedly converts the segmentation probability map from the previous iteration as spatial weights and applies these weights to the current iteration. This brings us two-fold benefits. In training, it allows joint optimization over the deep networks dealing with different input scales. In testing, it propagates multi-stage visual information throughout iterations to improve segmentation accuracy. Experiments in the NIH pancreas segmentation dataset demonstrate the state-of-the-art accuracy, which outperforms the previous best by an average of over 2%. Much higher accuracies are also reported on several small organs in a larger dataset collected by ourselves. In addition, our approach enjoys better convergence properties, making it more efficient and reliable in practice.

##### Abstract (translated by Google)
我们的目标是从腹部CT扫描中分割小器官（例如胰腺）。由于目标经常在输入图像中占据相对较小的区域，因此深度神经网络容易被复杂和可变的背景混淆。为了减轻这一点，研究人员提出了一个粗到精的方法，该方法使用第一个（粗略）阶段的预测来指示第二个（精细）阶段的较小输入区域。该算法虽然有效，但分别处理两个阶段，缺乏对全局能量函数的优化，并限制了多阶段视觉线索的融合能力。缺少上下文信息导致迭代收敛不满意，精细阶段有时产生比粗糙阶段更低的分割准确性。本文提出了一个经常性显着性转换网络。关键的创新是一个显着性变换模块，它将前一次迭代的分割概率图反复转换为空间权重，并将这些权重应用到当前迭代中。这给我们带来了双重好处。在训练中，它允许在处理不同输入尺度的深度网络上进行联合优化。在测试中，它在整个迭代过程中传播多阶段的视觉信息，以提高分割的准确性。 NIH胰腺分割数据集的实验证明了最新的精确度，平均超过2％，超过了以前的最佳水平。在我们自己收集的更大的数据集中，也报告了几个较小的器官更高的准确性。此外，我们的方法具有更好的收敛性，使其在实践中更加高效可靠。

##### URL
[https://arxiv.org/abs/1709.04518](https://arxiv.org/abs/1709.04518)

##### PDF
[https://arxiv.org/pdf/1709.04518](https://arxiv.org/pdf/1709.04518)

