---
layout: post
title: "Multimodal Unsupervised Image-to-Image Translation"
date: 2018-08-14 18:44:12
categories: arXiv_CV
tags: arXiv_CV Image_Caption
author: Xun Huang, Ming-Yu Liu, Serge Belongie, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised image-to-image translation is an important and challenging problem in computer vision. Given an image in the source domain, the goal is to learn the conditional distribution of corresponding images in the target domain, without seeing any pairs of corresponding images. While this conditional distribution is inherently multimodal, existing approaches make an overly simplified assumption, modeling it as a deterministic one-to-one mapping. As a result, they fail to generate diverse outputs from a given source domain image. To address this limitation, we propose a Multimodal Unsupervised Image-to-image Translation (MUNIT) framework. We assume that the image representation can be decomposed into a content code that is domain-invariant, and a style code that captures domain-specific properties. To translate an image to another domain, we recombine its content code with a random style code sampled from the style space of the target domain. We analyze the proposed framework and establish several theoretical results. Extensive experiments with comparisons to the state-of-the-art approaches further demonstrates the advantage of the proposed framework. Moreover, our framework allows users to control the style of translation outputs by providing an example style image. Code and pretrained models are available at https://github.com/nvlabs/MUNIT

##### Abstract (translated by Google)
无监督的图像到图像转换是计算机视觉中的重要且具有挑战性的问题。给定源域中的图像，目标是学习目标域中的对应图像的条件分布，而不会看到任何对应的图像对。虽然这种条件分布本质上是多模式的，但是现有方法做出了过度简化的假设，将其建模为确定性的一对一映射。结果，它们无法从给定的源域图像生成不同的输出。为了解决这个限制，我们提出了一种多模态无监督图像到图像转换（MUNIT）框架。我们假设图像表示可以分解为域不变的内容代码，以及捕获特定于域的属性的样式代码。为了将图像转换为另一个域，我们将其内容代码重新组合为从目标域的样式空间中采样的随机样式代码。我们分析了提出的框架并建立了几个理论结果。通过与现有技术方法的比较进行的广泛实验进一步证明了所提出的框架的优势。此外，我们的框架允许用户通过提供示例样式图像来控制翻译输出的样式。代码和预训练模型可从https://github.com/nvlabs/MUNIT获得

##### URL
[http://arxiv.org/abs/1804.04732](http://arxiv.org/abs/1804.04732)

##### PDF
[http://arxiv.org/pdf/1804.04732](http://arxiv.org/pdf/1804.04732)

