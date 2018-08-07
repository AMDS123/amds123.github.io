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
我们提出了一种弱监督方法，该方法将图像 - 句子对作为输入，并以空间注意掩模的形式学习视觉地（即，本地化）任意语言短语。具体而言，模型使用图像及其相关的图像级别字幕进行训练，而没有任何明确的区域到短语对应注释。为此，我们引入了一个端到端模型，该模型通过两种精心设计的损失函数来学习短语的视觉基础。除了标准的判别性损失之外，我们提出了一种新的结构性损失，它利用了由句子引起的解析树结构。特别地，我们确保对应于兄弟名词短语的注意掩模之间的互补性，以及由句子分析树定义的儿童和父母短语之间的注意掩模的组合性。我们验证了我们的方法在Microsoft COCO和Visual Genome数据集上的有效性。

##### URL
[https://arxiv.org/abs/1705.01371](https://arxiv.org/abs/1705.01371)

##### PDF
[https://arxiv.org/pdf/1705.01371](https://arxiv.org/pdf/1705.01371)

