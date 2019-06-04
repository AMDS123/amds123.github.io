---
layout: post
title: "Rethinking Loss Design for Large-scale 3D Shape Retrieval"
date: 2019-06-03 03:17:22
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Zhaoqun Li, Cheng Xu, Biao Leng
mathjax: true
---

* content
{:toc}

##### Abstract
Learning discriminative shape representations is a crucial issue for large-scale 3D shape retrieval. In this paper, we propose the Collaborative Inner Product Loss (CIP Loss) to obtain ideal shape embedding that discriminative among different categories and clustered within the same class. Utilizing simple inner product operation, CIP loss explicitly enforces the features of the same class to be clustered in a linear subspace, while inter-class subspaces are constrained to be at least orthogonal. Compared to previous metric loss functions, CIP loss could provide more clear geometric interpretation for the embedding than Euclidean margin, and is easy to implement without normalization operation referring to cosine margin. Moreover, our proposed loss term can combine with other commonly used loss functions and can be easily plugged into existing off-the-shelf architectures. Extensive experiments conducted on the two public 3D object retrieval datasets, ModelNet and ShapeNetCore 55, demonstrate the effectiveness of our proposal, and our method has achieved state-of-the-art results on both datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00546](http://arxiv.org/abs/1906.00546)

##### PDF
[http://arxiv.org/pdf/1906.00546](http://arxiv.org/pdf/1906.00546)

