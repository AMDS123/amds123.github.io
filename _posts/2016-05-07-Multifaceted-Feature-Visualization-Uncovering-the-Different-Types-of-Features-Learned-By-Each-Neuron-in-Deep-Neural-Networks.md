---
layout: post
title: "Multifaceted Feature Visualization: Uncovering the Different Types of Features Learned By Each Neuron in Deep Neural Networks"
date: 2016-05-07 06:30:51
categories: arXiv_CV
tags: arXiv_CV Regularization Face
author: Anh Nguyen, Jason Yosinski, Jeff Clune
mathjax: true
---

* content
{:toc}

##### Abstract
We can better understand deep neural networks by identifying which features each of their neurons have learned to detect. To do so, researchers have created Deep Visualization techniques including activation maximization, which synthetically generates inputs (e.g. images) that maximally activate each neuron. A limitation of current techniques is that they assume each neuron detects only one type of feature, but we know that neurons can be multifaceted, in that they fire in response to many different types of features: for example, a grocery store class neuron must activate either for rows of produce or for a storefront. Previous activation maximization techniques constructed images without regard for the multiple different facets of a neuron, creating inappropriate mixes of colors, parts of objects, scales, orientations, etc. Here, we introduce an algorithm that explicitly uncovers the multiple facets of each neuron by producing a synthetic visualization of each of the types of images that activate a neuron. We also introduce regularization methods that produce state-of-the-art results in terms of the interpretability of images obtained by activation maximization. By separately synthesizing each type of image a neuron fires in response to, the visualizations have more appropriate colors and coherent global structure. Multifaceted feature visualization thus provides a clearer and more comprehensive description of the role of each neuron.

##### Abstract (translated by Google)
我们可以通过识别每个神经元已经学会检测哪些特征来更好地理解深度神经网络。为此，研究人员创建了深度可视化技术，包括激活最大化，该技术综合生成最大程度地激活每个神经元的输入（例如图像）。当前技术的局限性在于，他们假定每个神经元只检测一种类型的特征，但我们知道神经元可以是多方面的，因为它们响应许多不同类型的特征而发射：例如，杂货店类神经元必须激活无论是产品行还是店面。先前的激活最大化技术构建的图像不考虑神经元的多个不同的方面，产生不适当的颜色混合，物体的一部分，尺度，方向等。在这里，我们介绍一种算法，通过产生明确揭示每个神经元的多个方面激活神经元的每种类型的图像的合成可视化。我们还介绍正则化方法，通过激活最大化获得图像的可解释性，产生最新的结果。通过分别合成神经元响应的每种图像类型，可视化具有更合适的颜色和连贯的整体结构。因此多方面的特征可视化提供了一个更清晰和更全面的描述每个神经元的作用。

##### URL
[https://arxiv.org/abs/1602.03616](https://arxiv.org/abs/1602.03616)

##### PDF
[https://arxiv.org/pdf/1602.03616](https://arxiv.org/pdf/1602.03616)

