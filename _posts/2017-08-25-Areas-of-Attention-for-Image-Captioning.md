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
我们提出了“注意力领域”，一种基于关注的自动图像字幕模型。我们的方法使用三个成对的相互作用来模拟图像区域，标题词和RNN语言模型的状态之间的依赖关系。与之前的基于注意的方法相比，图像区域仅与RNN状态相关联，我们的方法允许字幕词和图像区域之间的直接关联。在训练期间，这些关联是从图像级别的标题推断的，类似于弱监督的对象检测器训练。这些关联有助于在测试过程中通过本地化相应区域来改善字幕。我们还提出和比较了不同的产生关注领域的方式：以卷积方式应用CNN激活网格，对象提议和空间变换网络。空间变换器给出最好的结果。他们考虑到图像特定的关注领域，并可以与其他网络联合进行培训。我们的注意力机制和空间转换关注领域一起，在MSCOCO数据集上产生了最新的结果。生成字幕中的有意义的潜在语义结构。

##### URL
[https://arxiv.org/abs/1612.01033](https://arxiv.org/abs/1612.01033)

##### PDF
[https://arxiv.org/pdf/1612.01033](https://arxiv.org/pdf/1612.01033)

