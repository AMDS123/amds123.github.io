---
layout: post
title: 'Taming Adversarial Domain Transfer with Structural Constraints for Image Enhancement'
date: 2017-12-05 21:10:17
categories: arXiv_CV
[arXiv_CV,Image Enhancement]
author: Elias Vansteenkiste, Patrick Kern
---

* content
{:toc}

##### Abstract
The goal of this work is to clarify images of traffic scenes that are degraded by natural causes such as fog, rain and limited visibility during the night. For these applications, it is next to impossible to get pixel perfect pairs of the same scene, with and without the degrading conditions. This makes it unsuitable for conventional supervised learning approaches. It is however easy to collect a dataset of unpaired images of the scenes in a perfect and in a degraded condition. To enhance the images taken in a poor visibility condition, domain transfer models can be trained to transform an image from the degraded to the clear domain. A well-known concept for unsupervised domain transfer are cycle consistent generative adversarial models. Unfortunately, the resulting generators often change the structure of the scene. This causes an undesirable change in the semantics of the traffic situation. We propose three ways to cope with this problem depending on the type of degradation: forcing the same perception in both domains, forcing the same edges in both domains or guiding the generator to produce semantically sound transformations.

##### Abstract (translated by Google)
这项工作的目标是澄清由于自然原因（例如雾，雨和夜间能见度有限）而恶化的交通场景的图像。对于这些应用来说，几乎不可能获得相同场景的像素完美对，有和没有恶化条件。这使得它不适合传统的监督学习方法。然而，很容易收集完美和退化情况下不成对的场景图像的数据集。为了增强在低能见度条件下拍摄的图像，可以训练域转移模型以将图像从降级域转换到清晰域。无监督域转移的一个众所周知的概念是周期一致的生成对抗模型。不幸的是，由此产生的发电机常常改变场景的结构。这导致交通状况的语义上的不希望的改变。根据退化的类型，我们提出了三种方法来解决这个问题：在两个领域强迫相同的感知，迫使两个领域的边缘相同或引导生成器产生语义上的声音转换。

##### URL
[http://arxiv.org/abs/1712.00598](http://arxiv.org/abs/1712.00598)

