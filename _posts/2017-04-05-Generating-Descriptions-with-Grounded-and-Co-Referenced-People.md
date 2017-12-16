---
layout: post
title: "Generating Descriptions with Grounded and Co-Referenced People"
date: 2017-04-05 16:36:13
categories: arXiv_CV
tags: arXiv_CV Attention
author: Anna Rohrbach, Marcus Rohrbach, Siyu Tang, Seong Joon Oh, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Learning how to generate descriptions of images or videos received major interest both in the Computer Vision and Natural Language Processing communities. While a few works have proposed to learn a grounding during the generation process in an unsupervised way (via an attention mechanism), it remains unclear how good the quality of the grounding is and whether it benefits the description quality. In this work we propose a movie description model which learns to generate description and jointly ground (localize) the mentioned characters as well as do visual co-reference resolution between pairs of consecutive sentences/clips. We also propose to use weak localization supervision through character mentions provided in movie descriptions to learn the character grounding. At training time, we first learn how to localize characters by relating their visual appearance to mentions in the descriptions via a semi-supervised approach. We then provide this (noisy) supervision into our description model which greatly improves its performance. Our proposed description model improves over prior work w.r.t. generated description quality and additionally provides grounding and local co-reference resolution. We evaluate it on the MPII Movie Description dataset using automatic and human evaluation measures and using our newly collected grounding and co-reference data for characters.

##### Abstract (translated by Google)
在计算机视觉和自然语言处理社区中学习如何生成图像或视频的描述都受到了重大关注。虽然有一些作品提出要在无监督的方式下（通过注意机制）在生成过程中学习接地，但仍不清楚接地质量有多好，是否有利于描述质量。在这项工作中，我们提出了一个电影描述模型，学习生成描述和联合研究（定位）提到的字符，以及做连续的句子/剪辑之间的视觉共同参考的决议。我们还建议通过电影描述中提供的字符提及来使用弱的本地化监督来学习字符的基础。在培训的时候，我们首先要学习如何通过半监督的方式将他们的视觉外观与描述中的提及相关联来对文字进行本地化。然后，我们将这种（嘈杂的）监督提供给我们的描述模型，这大大提高了它的性能。我们提出的描述模型比以前的工作改进了很多。生成的描述质量，并提供接地和本地共参考分辨率。我们在MPII电影描述数据集上使用自动评估和人为评估措施评估它，并使用我们新收集的字符的接地和共参考数据。

##### URL
[https://arxiv.org/abs/1704.01518](https://arxiv.org/abs/1704.01518)

##### PDF
[https://arxiv.org/pdf/1704.01518](https://arxiv.org/pdf/1704.01518)

