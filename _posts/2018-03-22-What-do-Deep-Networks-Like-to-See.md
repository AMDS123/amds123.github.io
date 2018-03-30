---
layout: post
title: "What do Deep Networks Like to See?"
date: 2018-03-22 13:10:47
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation
author: Sebastian Palacio, Joachim Folz, Jörn Hees, Federico Raue, Damian Borth, Andreas Dengel
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel way to measure and understand convolutional neural networks by quantifying the amount of input signal they let in. To do this, an autoencoder (AE) was fine-tuned on gradients from a pre-trained classifier with fixed parameters. We compared the reconstructed samples from AEs that were fine-tuned on a set of image classifiers (AlexNet, VGG16, ResNet-50, and Inception~v3) and found substantial differences. The AE learns which aspects of the input space to preserve and which ones to ignore, based on the information encoded in the backpropagated gradients. Measuring the changes in accuracy when the signal of one classifier is used by a second one, a relation of total order emerges. This order depends directly on each classifier's input signal but it does not correlate with classification accuracy or network size. Further evidence of this phenomenon is provided by measuring the normalized mutual information between original images and auto-encoded reconstructions from different fine-tuned AEs. These findings break new ground in the area of neural network understanding, opening a new way to reason, debug, and interpret their results. We present four concrete examples in the literature where observations can now be explained in terms of the input signal that a model uses.

##### Abstract (translated by Google)
我们提出了一种通过量化输入信号量来衡量和理解卷积神经网络的新方法。为此，自动编码器（AE）根据预先训练的具有固定参数的分类器的梯度进行微调。我们比较了在一组图像分类器（AlexNet，VGG16，ResNet-50和Inception〜v3）上进行了微调的AE的重建样本，发现了很大的差异。 AE基于反向传播梯度中编码的信息，学习输入空间的哪些方面要保留，哪些方面要忽略。当一个分类器的信号被另一个分类器使用时，测量准确度的变化，就会出现总顺序的关系。该顺序直接取决于每个分类器的输入信号，但与分类准确性或网络大小无关。通过测量原始图像与来自不同微调AE的自动编码重建之间的归一化互信息来提供这种现象的进一步证据。这些发现突破了神经网络理解领域的新局面，开辟了推理，调试和解释其结果的新途径。我们在文献中给出了四个具体的例子，现在可以用模型使用的输入信号来解释观测。

##### URL
[https://arxiv.org/abs/1803.08337](https://arxiv.org/abs/1803.08337)

##### PDF
[https://arxiv.org/pdf/1803.08337](https://arxiv.org/pdf/1803.08337)

