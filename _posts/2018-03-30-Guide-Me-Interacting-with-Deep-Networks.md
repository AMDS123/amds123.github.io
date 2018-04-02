---
layout: post
title: "Guide Me: Interacting with Deep Networks"
date: 2018-03-30 17:28:52
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN Inference
author: Christian Rupprecht, Iro Laina, Nassir Navab, Gregory D. Hager, Federico Tombari
mathjax: true
---

* content
{:toc}

##### Abstract
Interaction and collaboration between humans and intelligent machines has become increasingly important as machine learning methods move into real-world applications that involve end users. While much prior work lies at the intersection of natural language and vision, such as image captioning or image generation from text descriptions, less focus has been placed on the use of language to guide or improve the performance of a learned visual processing algorithm. In this paper, we explore methods to flexibly guide a trained convolutional neural network through user input to improve its performance during inference. We do so by inserting a layer that acts as a spatio-semantic guide into the network. This guide is trained to modify the network's activations, either directly via an energy minimization scheme or indirectly through a recurrent model that translates human language queries to interaction weights. Learning the verbal interaction is fully automatic and does not require manual text annotations. We evaluate the method on two datasets, showing that guiding a pre-trained network can improve performance, and provide extensive insights into the interaction between the guide and the CNN.

##### Abstract (translated by Google)
随着机器学习方法转变为涉及最终用户的实际应用，人类与智能机器之间的交互与协作变得越来越重要。虽然以前的工作主要集中在自然语言和视觉的交集处，例如图像字幕或从文本描述中生成图像，但很少关注使用语言来指导或改进学习的视觉处理算法的性能。在本文中，我们探索通过用户输入灵活指导训练的卷积神经网络的方法，以提高其在推断期间的性能。我们通过在网络中插入一个充当空间语义指南的层来实现。本指南经过训练，可以直接通过能量最小化方案修改网络激活，也可以通过将人类语言查询转换为互动权重的循环模型间接进行修改。学习口头交互是完全自动的，不需要手动文本注释。我们在两个数据集上评估该方法，显示指导预先训练的网络可以提高性能，并提供对指南和CNN之间交互的深入见解。

##### URL
[https://arxiv.org/abs/1803.11544](https://arxiv.org/abs/1803.11544)

##### PDF
[https://arxiv.org/pdf/1803.11544](https://arxiv.org/pdf/1803.11544)

