---
layout: post
title: "Improved Image Captioning with Adversarial Semantic Alignment"
date: 2018-06-01 17:43:25
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN Caption RNN Relation
author: Pierre L. Dognin, Igor Melnyk, Youssef Mroueh, Jarret Ross, Tom Sercu (IBM Research, USA)
mathjax: true
---

* content
{:toc}

##### Abstract
We study image captioning as a conditional GAN training, proposing both a context-aware LSTM captioner and co-attentive discriminator, which enforces semantic alignment between images and captions. We empirically study the viability of two training methods: Self-critical Sequence Training (SCST) and Gumbel Straight-Through (ST). We show that, surprisingly, SCST (a policy gradient method) shows more stable gradient behavior and improved results over Gumbel ST, even without accessing the discriminator gradients directly. We also address the open question of automatic evaluation for these models and introduce a new semantic score and demonstrate its strong correlation to human judgement. As an evaluation paradigm, we suggest that an important criterion is the ability of a captioner to generalize to compositions between objects that do not usually occur together, for which we introduce a captioned Out of Context (OOC) test set. The OOC dataset combined with our semantic score is a new benchmark for the captioning community. Under this OOC benchmark, and the traditional MSCOCO dataset, we show that SCST has a strong performance in both semantic score and human evaluation.

##### Abstract (translated by Google)
我们将图像字幕作为条件GAN训练进行研究，提出了上下文感知LSTM字幕和共同注意识别器，它们强制实现图像和字幕之间的语义对齐。我们凭经验研究了两种训练方法的可行性：自我批判序列训练（SCST）和Gumbel直通（ST）。令人惊讶的是，即使没有直接访问鉴别器梯度，SCST（策略梯度法）也显示出比Gumbel ST更稳定的梯度行为和更好的结果。我们还解决了这些模型的自动评估的开放性问题，并引入了新的语义分数，并证明了它与人类判断的强烈相关性。作为评估范例，我们建议一个重要的标准是字幕制作者能够推广通常不会出现在一起的对象之间的组合，我们为此引入了一个标题的Out of Context（OOC）测试集。 OOC数据集与我们的语义分数相结合，是字幕社区的新基准。在此OOC基准测试和传统MSCOCO数据集下，我们表明SCST在语义评分和人工评估方面都有很强的表现。

##### URL
[https://arxiv.org/abs/1805.00063](https://arxiv.org/abs/1805.00063)

##### PDF
[https://arxiv.org/pdf/1805.00063](https://arxiv.org/pdf/1805.00063)

