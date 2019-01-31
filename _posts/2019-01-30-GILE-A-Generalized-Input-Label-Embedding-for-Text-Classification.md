---
layout: post
title: "GILE: A Generalized Input-Label Embedding for Text Classification"
date: 2019-01-30 18:33:05
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification Relation
author: Nikolaos Pappas, James Henderson
mathjax: true
---

* content
{:toc}

##### Abstract
Neural text classification models typically treat output labels as categorical variables which lack description and semantics. This forces their parametrization to be dependent on the label set size, and, hence, they are unable to scale to large label sets and generalize to unseen ones. Existing joint input-label text models overcome these issues by exploiting label descriptions, but they are unable to capture complex label relationships, have rigid parametrization, and their gains on unseen labels happen often at the expense of weak performance on the labels seen during training. In this paper, we propose a new input-label model which generalizes over previous such models, addresses their limitations and does not compromise performance on seen labels. The model consists of a joint non-linear input-label embedding with controllable capacity and a joint-space-dependent classification unit which is trained with cross-entropy loss to optimize classification performance. We evaluate models on full-resource and low- or zero-resource text classification of multilingual news and biomedical text with a large label set. Our model outperforms monolingual and multilingual models which do not leverage label semantics and previous joint input-label space models in both scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.06219](http://arxiv.org/abs/1806.06219)

##### PDF
[http://arxiv.org/pdf/1806.06219](http://arxiv.org/pdf/1806.06219)

