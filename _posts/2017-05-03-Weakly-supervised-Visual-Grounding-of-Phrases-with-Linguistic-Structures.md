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


##### URL
[https://arxiv.org/abs/1705.01371](https://arxiv.org/abs/1705.01371)

##### PDF
[https://arxiv.org/pdf/1705.01371](https://arxiv.org/pdf/1705.01371)

