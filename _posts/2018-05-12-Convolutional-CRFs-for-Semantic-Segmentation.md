---
layout: post
title: "Convolutional CRFs for Semantic Segmentation"
date: 2018-05-12 20:37:27
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Marvin T. T. Teichmann, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
For the challenging semantic image segmentation task the most efficient models have traditionally combined the structured modelling capabilities of Conditional Random Fields (CRFs) with the feature extraction power of CNNs. In more recent works however, CRF post-processing has fallen out of favour. We argue that this is mainly due to the slow training and inference speeds of CRFs, as well as the difficulty of learning the internal CRF parameters. To overcome both issues we propose to add the assumption of conditional independence to the framework of fully-connected CRFs. This allows us to reformulate the inference in terms of convolutions, which can be implemented highly efficiently on GPUs. Doing so speeds up inference and training by a factor of more then 100. All parameters of the convolutional CRFs can easily be optimized using backpropagation. To facilitating further CRF research we make our implementation publicly available. Please visit: this https URL

##### Abstract (translated by Google)
对于具有挑战性的语义图像分割任务，最有效的模型传统上将条件随机场（CRF）的结构化建模能力与CNN的特征提取能力相结合。然而，在最近的作品中，CRF后期处理已经不受青睐。我们认为这主要是由于CRF的训练和推断速度缓慢以及学习内部CRF参数的难度所致。为了克服这两个问题，我们建议将条件独立的假设添加到完全关联的CRF的框架中。这使得我们可以在卷积方面重新进行推理，这可以在GPU上高效地实现。这样做可以将推理和训练加速超过100倍。卷积CRF的所有参数都可以使用反向传播轻松进行优化。为了促进CRF的进一步研究，我们公开实施了我们的实施。请访问：此https网址

##### URL
[https://arxiv.org/abs/1805.04777](https://arxiv.org/abs/1805.04777)

##### PDF
[https://arxiv.org/pdf/1805.04777](https://arxiv.org/pdf/1805.04777)

