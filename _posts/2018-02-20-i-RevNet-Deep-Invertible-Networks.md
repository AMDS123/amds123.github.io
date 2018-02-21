---
layout: post
title: "i-RevNet: Deep Invertible Networks"
date: 2018-02-20 12:38:49
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN
author: J&#xf6;rn-Henrik Jacobsen (IvI), Arnold Smeulders (IvI), Edouard Oyallon (CVN, GALEN, SEQUEL, DI-ENS)
mathjax: true
---

* content
{:toc}

##### Abstract
It is widely believed that the success of deep convolutional networks is based on progressively discarding uninformative variability about the input with respect to the problem at hand. This is supported empirically by the difficulty of recovering images from their hidden representations, in most commonly used network architectures. In this paper we show via a one-to-one mapping that this loss of information is not a necessary condition to learn representations that generalize well on complicated problems, such as ImageNet. Via a cascade of homeomorphic layers, we build the i-RevNet, a network that can be fully inverted up to the final projection onto the classes, i.e. no information is discarded. Building an invertible architecture is difficult, for one, because the local inversion is ill-conditioned, we overcome this by providing an explicit inverse. An analysis of i-RevNets learned representations suggests an alternative explanation for the success of deep networks by a progressive contraction and linear separation with depth. To shed light on the nature of the model learned by the i-RevNet we reconstruct linear interpolations between natural image representations.

##### Abstract (translated by Google)
人们普遍认为，深度卷积网络的成功是基于逐步丢弃关于输入的关于手头问题的无形变化。在大多数常用的网络体系结构中，这是通过从隐藏表示中恢复图像的难度经验上支持的。在本文中，我们通过一对一的映射表明，这种信息丢失并不是学习表示的一个必要条件，这些表示很好地解决了复杂问题，例如ImageNet。通过一系列同胚层，我们构建了i-RevNet网络，该网络可以完全倒置到最终投影到类上，即没有信息被丢弃。建立一个可逆的体系结构很困难，因为局部反演是有条件的，我们通过提供一个明确的逆向来克服这个问题。对i-RevNet学习表示的分析表明深度网络的成功通过渐进收缩和线性分离与深度成为另一种解释。为了阐明由i-RevNet学习的模型的性质，我们重建了自然图像表示之间的线性插值。

##### URL
[http://arxiv.org/abs/1802.07088](http://arxiv.org/abs/1802.07088)

##### PDF
[http://arxiv.org/pdf/1802.07088](http://arxiv.org/pdf/1802.07088)

