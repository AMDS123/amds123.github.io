---
layout: post
title: "Style Transfer as Unsupervised Machine Translation"
date: 2018-08-23 18:18:32
categories: arXiv_CL
tags: arXiv_CL Style_Transfer Embedding NMT
author: Zhirui Zhang, Shuo Ren, Shujie Liu, Jianyong Wang, Peng Chen, Mu Li, Ming Zhou, Enhong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Language style transferring rephrases text with specific stylistic attributes while preserving the original attribute-independent content. One main challenge in learning a style transfer system is a lack of parallel data where the source sentence is in one style and the target sentence in another style. With this constraint, in this paper, we adapt unsupervised machine translation methods for the task of automatic style transfer. We first take advantage of style-preference information and word embedding similarity to produce pseudo-parallel data with a statistical machine translation (SMT) framework. Then the iterative back-translation approach is employed to jointly train two neural machine translation (NMT) based transfer systems. To control the noise generated during joint training, a style classifier is introduced to guarantee the accuracy of style transfer and penalize bad candidates in the generated pseudo data. Experiments on benchmark datasets show that our proposed method outperforms previous state-of-the-art models in terms of both accuracy of style transfer and quality of input-output correspondence.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.07894](https://arxiv.org/abs/1808.07894)

##### PDF
[https://arxiv.org/pdf/1808.07894](https://arxiv.org/pdf/1808.07894)

