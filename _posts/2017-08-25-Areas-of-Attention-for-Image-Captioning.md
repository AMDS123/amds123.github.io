---
layout: post
title: "Areas of Attention for Image Captioning"
date: 2017-08-25 14:36:01
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Attention Caption CNN RNN Language_Model Detection
author: Marco Pedersoli, Thomas Lucas, Cordelia Schmid, Jakob Verbeek
mathjax: true
---

* content
{:toc}

##### Abstract
We propose "Areas of Attention", a novel attention-based model for automatic image captioning. Our approach models the dependencies between image regions, caption words, and the state of an RNN language model, using three pairwise interactions. In contrast to previous attention-based approaches that associate image regions only to the RNN state, our method allows a direct association between caption words and image regions. During training these associations are inferred from image-level captions, akin to weakly-supervised object detector training. These associations help to improve captioning by localizing the corresponding regions during testing. We also propose and compare different ways of generating attention areas: CNN activation grids, object proposals, and spatial transformers nets applied in a convolutional fashion. Spatial transformers give the best results. They allow for image specific attention areas, and can be trained jointly with the rest of the network. Our attention mechanism and spatial transformer attention areas together yield state-of-the-art results on the MSCOCO dataset.o meaningful latent semantic structure in the generated captions.

##### Abstract (translated by Google)
我们提出了“注意区域”，一种基于注意力的自动图像字幕模型。我们的方法使用三个成对交互来模拟图像区域，字幕单词和RNN语言模型的状态之间的依赖关系。与之前仅将图像区域关联到RNN状态的基于注意力的方法相比，我们的方法允许字幕字和图像区域之间的直接关联。在训练期间，这些关联是从图像级别的标题推断出来的，类似于弱监督的物体检测器训练。这些关联有助于通过在测试期间本地化相应区域来改进字幕。我们还提出并比较产生关注区域的不同方式：CNN激活网格，对象建议和以卷积方式应用的空间变换网络。空间变压器可带来最佳效果。它们允许图像特定的关注区域，并且可以与网络的其余部分一起训练。我们的注意机制和空间变换器注意区域一起在MSCOCO数据集上产生最先进的结果。在生成的标题中有意义的潜在语义结构。

##### URL
[https://arxiv.org/abs/1612.01033](https://arxiv.org/abs/1612.01033)

##### PDF
[https://arxiv.org/pdf/1612.01033](https://arxiv.org/pdf/1612.01033)

