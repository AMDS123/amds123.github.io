---
layout: post
title: "Are Facial Attributes Adversarially Robust?"
date: 2016-09-16 21:49:14
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification
author: Andras Rozsa, Manuel Günther, Ethan M. Rudd, Terrance E. Boult
mathjax: true
---

* content
{:toc}

##### Abstract
Facial attributes are emerging soft biometrics that have the potential to reject non-matches, for example, based on mismatching gender. To be usable in stand-alone systems, facial attributes must be extracted from images automatically and reliably. In this paper, we propose a simple yet effective solution for automatic facial attribute extraction by training a deep convolutional neural network (DCNN) for each facial attribute separately, without using any pre-training or dataset augmentation, and we obtain new state-of-the-art facial attribute classification results on the CelebA benchmark. To test the stability of the networks, we generated adversarial images -- formed by adding imperceptible non-random perturbations to original inputs which result in classification errors -- via a novel fast flipping attribute (FFA) technique. We show that FFA generates more adversarial examples than other related algorithms, and that DCNNs for certain attributes are generally robust to adversarial inputs, while DCNNs for other attributes are not. This result is surprising because no DCNNs tested to date have exhibited robustness to adversarial images without explicit augmentation in the training procedure to account for adversarial examples. Finally, we introduce the concept of natural adversarial samples, i.e., images that are misclassified but can be easily turned into correctly classified images by applying small perturbations. We demonstrate that natural adversarial samples commonly occur, even within the training set, and show that many of these images remain misclassified even with additional training epochs. This phenomenon is surprising because correcting the misclassification, particularly when guided by training data, should require only a small adjustment to the DCNN parameters.

##### Abstract (translated by Google)
面部属性是新兴的软生物识别技术，有可能拒绝非匹配，例如，基于不匹配的性别。要在独立系统中使用，必须自动和可靠地从图像中提取面部属性。本文提出了一种简单而有效的面部属性自动提取方法，通过对每个面部属性分别训练一个深度卷积神经网络（DCNN），而不需要使用任何预训练或数据集增量， CelebA基准测试中最先进的面部属性分类结果。为了测试网络的稳定性，我们通过一种新颖的快速翻转属性（FFA）技术，产生对抗图像 - 通过将不可察觉的非随机扰动添加到导致分类错误的原始输入中而形成。我们表明，FFA比其他相关算法产生更多的对抗性的例子，并且对于某些属性的DCNN通常对敌对输入是强壮的，而对于其他属性的DCNN则不是。这个结果是令人惊讶的，因为迄今为止测试的DCNN没有显示对抗图像的鲁棒性，而在训练过程中没有明确的增强来解释对抗的例子。最后，我们引入自然对抗样本的概念，即错误分类的图像，但通过应用小的扰动可以很容易地转化为正确分类的图像。我们证明，即使在训练集内，通常也会出现自然的敌对样本，并且表明即使有额外的训练时期，这些图像中的许多仍然被错误分类。这种现象是令人惊讶的，因为纠正错误分类，特别是在训练数据的指导下，只需要对DCNN参数进行微小的调整。

##### URL
[https://arxiv.org/abs/1605.05411](https://arxiv.org/abs/1605.05411)

##### PDF
[https://arxiv.org/pdf/1605.05411](https://arxiv.org/pdf/1605.05411)

