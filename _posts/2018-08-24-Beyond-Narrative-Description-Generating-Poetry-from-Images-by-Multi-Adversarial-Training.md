---
layout: post
title: "Beyond Narrative Description: Generating Poetry from Images by Multi-Adversarial Training"
date: 2018-08-24 07:35:26
categories: arXiv_AI
tags: arXiv_AI Sentiment Adversarial Attention Embedding
author: Bei Liu, Jianlong Fu, Makoto P. Kato, Masatoshi Yoshikawa
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic generation of natural language from images has attracted extensive attention. In this paper, we take one step further to investigate generation of poetic language (with multiple lines) to an image for automatic poetry creation. This task involves multiple challenges, including discovering poetic clues from the image (e.g., hope from green), and generating poems to satisfy both relevance to the image and poeticness in language level. To solve the above challenges, we formulate the task of poem generation into two correlated sub-tasks by multi-adversarial training via policy gradient, through which the cross-modal relevance and poetic language style can be ensured. To extract poetic clues from images, we propose to learn a deep coupled visual-poetic embedding, in which the poetic representation from objects, sentiments and scenes in an image can be jointly learned. Two discriminative networks are further introduced to guide the poem generation, including a multi-modal discriminator and a poem-style discriminator. To facilitate the research, we have released two poem datasets by human annotators with two distinct properties: 1) the first human annotated image-to-poem pair dataset (with 8,292 pairs in total), and 2) to-date the largest public English poem corpus dataset (with 92,265 different poems in total). Extensive experiments are conducted with 8K images, among which 1.5K image are randomly picked for evaluation. Both objective and subjective evaluations show the superior performances against the state-of-the-art methods for poem generation from images. Turing test carried out with over 500 human subjects, among which 30 evaluators are poetry experts, demonstrates the effectiveness of our approach.

##### Abstract (translated by Google)
从图像中自动生成自然语言已引起广泛关注。在本文中，我们更进一步研究诗歌语言（多行）的生成，以形成自动诗歌创作的图像。这项任务涉及多个挑战，包括从图像中发现诗意线索（例如，希望来自绿色），以及生成诗歌以满足与图像的相关性和语言水平的诗意。为了解决上述挑战，我们通过政策梯度的多对抗训练，将诗歌生成的任务分为两个相关的子任务，通过这种任务可以保证跨模式的相关性和诗歌的语言风格。为了从图像中提取诗意线索，我们建议学习深度耦合的视觉 - 诗意嵌入，其中可以共同学习图像中的对象，情感和场景的诗意表达。进一步引入两个判别网络来指导诗歌生成，包括多模态鉴别器和诗式鉴别器。为了便于研究，我们发布了两个由人类注释者创作的诗歌数据集，其中包含两个不同的属性：1）第一个人类注释的图像对诗对数据集（总共8,292对），以及2）迄今为止最大的公共英语诗歌语料库数据集（共有92,265首不同的诗歌）。用8K图像进行了大量实验，其中随机挑选1.5K图像进行评估。客观评价和主观评价都表明，对于从图像中生成诗歌的最先进方法，它具有优越的性能。对超过500名人类受试者进行图灵测试，其中30名评估员是诗歌专家，证明了我们的方法的有效性。

##### URL
[http://arxiv.org/abs/1804.08473](http://arxiv.org/abs/1804.08473)

##### PDF
[http://arxiv.org/pdf/1804.08473](http://arxiv.org/pdf/1804.08473)

