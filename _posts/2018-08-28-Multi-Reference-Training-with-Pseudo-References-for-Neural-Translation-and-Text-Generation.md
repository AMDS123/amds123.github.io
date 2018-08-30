---
layout: post
title: "Multi-Reference Training with Pseudo-References for Neural Translation and Text Generation"
date: 2018-08-28 22:30:11
categories: arXiv_CL
tags: arXiv_CL Image_Caption Summarization Text_Generation Caption
author: Renjie Zheng, Mingbo Ma, Liang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural text generation, including neural machine translation, image captioning, and summarization, has been quite successful recently. However, during training time, typically only one reference is considered for each example, even though there are often multiple references available, e.g., 4 references in NIST MT evaluations, and 5 references in image captioning data. We first investigate several different ways of utilizing multiple human references during training. But more importantly, we then propose an algorithm to generate exponentially many pseudo-references by first compressing existing human references into lattices and then traversing them to generate new pseudo-references. These approaches lead to substantial improvements over strong baselines in both machine translation (+1.5 BLEU) and image captioning (+3.1 BLEU / +11.7 CIDEr).

##### Abstract (translated by Google)
神经文本生成，包括神经机器翻译，图像字幕和摘要，最近已经非常成功。然而，在训练时间期间，通常对于每个示例仅考虑一个参考，即使经常存在多个参考，例如，NIST MT评估中的4个参考，以及图像字幕数据中的5个参考。我们首先研究了在训练期间使用多个人参考的几种不同方法。但更重要的是，我们然后提出一种算法，通过首先将现有的人类引用压缩到格子中然后遍历它们以生成新的伪引用来生成指数级的许多伪引用。这些方法在机器翻译（+1.5 BLEU）和图像字幕（+3.1 BLEU / +11.7 CIDEr）方面均超过强基线的显着改进。

##### URL
[http://arxiv.org/abs/1808.09564](http://arxiv.org/abs/1808.09564)

##### PDF
[http://arxiv.org/pdf/1808.09564](http://arxiv.org/pdf/1808.09564)

