---
layout: post
title: "Weakly-supervised Visual Grounding of Phrases with Linguistic Structures"
date: 2017-05-03 11:53:33
categories: arXiv_CV
tags: arXiv_CV Attention Caption
author: Fanyi Xiao, Leonid Sigal, Yong Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a weakly-supervised approach that takes image-sentence pairs as input and learns to visually ground (i.e., localize) arbitrary linguistic phrases, in the form of spatial attention masks. Specifically, the model is trained with images and their associated image-level captions, without any explicit region-to-phrase correspondence annotations. To this end, we introduce an end-to-end model which learns visual groundings of phrases with two types of carefully designed loss functions. In addition to the standard discriminative loss, which enforces that attended image regions and phrases are consistently encoded, we propose a novel structural loss which makes use of the parse tree structures induced by the sentences. In particular, we ensure complementarity among the attention masks that correspond to sibling noun phrases, and compositionality of attention masks among the children and parent phrases, as defined by the sentence parse tree. We validate the effectiveness of our approach on the Microsoft COCO and Visual Genome datasets.

##### Abstract (translated by Google)
我们提出了一个弱监督的方法，以图像 - 句子对作为输入，学习以空间注意力掩模的形式在视觉上研究（即定位）任意的语言短语。具体来说，该模型是用图像及其相关的图像级字幕训练的，没有任何明确的区域到词组的对应注释。为此，我们引入一个端到端的模型，学习两种精心设计的损失函数的短语的视觉基础。除了标准的判别性损失外，还强调了所考虑的图像区域和短语是一致编码的，我们提出了一个新的结构损失，它利用了由句子引起的分析树结构。具体来说，我们确保了与兄弟名词短语相对应的注意掩码和子句和父语短语中的注意掩模的组成性（如句子分析树所定义的）之间的互补性。我们验证了我们的方法在Microsoft COCO和Visual Genome数据集上的有效性。

##### URL
[https://arxiv.org/abs/1705.01371](https://arxiv.org/abs/1705.01371)

##### PDF
[https://arxiv.org/pdf/1705.01371](https://arxiv.org/pdf/1705.01371)

