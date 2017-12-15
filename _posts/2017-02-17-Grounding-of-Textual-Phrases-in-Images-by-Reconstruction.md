---
layout: post
title: "Grounding of Textual Phrases in Images by Reconstruction"
date: 2017-02-17 21:02:05
categories: arXiv_CL
tags: arXiv_CL Attention Language_Model
author: Anna Rohrbach, Marcus Rohrbach, Ronghang Hu, Trevor Darrell, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Grounding (i.e. localizing) arbitrary, free-form textual phrases in visual content is a challenging problem with many applications for human-computer interaction and image-text reference resolution. Few datasets provide the ground truth spatial localization of phrases, thus it is desirable to learn from data with no or little grounding supervision. We propose a novel approach which learns grounding by reconstructing a given phrase using an attention mechanism, which can be either latent or optimized directly. During training our approach encodes the phrase using a recurrent network language model and then learns to attend to the relevant image region in order to reconstruct the input phrase. At test time, the correct attention, i.e., the grounding, is evaluated. If grounding supervision is available it can be directly applied via a loss over the attention mechanism. We demonstrate the effectiveness of our approach on the Flickr 30k Entities and ReferItGame datasets with different levels of supervision, ranging from no supervision over partial supervision to full supervision. Our supervised variant improves by a large margin over the state-of-the-art on both datasets.

##### Abstract (translated by Google)
在视觉内容中对任意自由形式的文本短语进行基础化（即本地化）是人机交互和图像文本参考分辨率的许多应用中具有挑战性的问题。很少有数据集提供了短语的地面真实空间定位，因此需要从没有或几乎没有接地监督的数据中学习。我们提出了一种新颖的方法，通过使用注意机制重建给定的短语来学习基础，该机制可以是潜在的，也可以是直接优化的。在训练过程中，我们的方法使用循环网络语言模型对短语进行编码，然后学习注意相关图像区域以重建输入短语。在测试时间，评估正确的注意力，即接地。如果接地监督可用，可以通过注意机制的损失直接应用。我们展示了我们在Flickr 30k Entities和ReferItGame数据集上的方法的有效性，这些数据集具有不同的监督级别，从不监督部分监督到全面监督。我们的监督式变体在两个数据集上都比现有技术有很大提高。

##### URL
[https://arxiv.org/abs/1511.03745](https://arxiv.org/abs/1511.03745)

##### PDF
[https://arxiv.org/pdf/1511.03745](https://arxiv.org/pdf/1511.03745)

