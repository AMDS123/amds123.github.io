---
layout: post
title: "Zero-Shot Grounding of Objects from Natural Language Queries"
date: 2019-08-20 02:07:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Classification Detection Relation
author: Arka Sadhu, Kan Chen, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
A phrase grounding system localizes a particular object in an image referred to by a natural language query. In previous work, the phrases were restricted to have nouns that were encountered in training, we extend the task to Zero-Shot Grounding(ZSG) which can include novel, "unseen" nouns. Current phrase grounding systems use an explicit object detection network in a 2-stage framework where one stage generates sparse proposals and the other stage evaluates them. In the ZSG setting, generating appropriate proposals itself becomes an obstacle as the proposal generator is trained on the entities common in the detection and grounding datasets. We propose a new single-stage model called ZSGNet which combines the detector network and the grounding system and predicts classification scores and regression parameters. Evaluation of ZSG system brings additional subtleties due to the influence of the relationship between the query and learned categories; we define four distinct conditions that incorporate different levels of difficulty. We also introduce new datasets, sub-sampled from Flickr30k Entities and Visual Genome, that enable evaluations for the four conditions. Our experiments show that ZSGNet achieves state-of-the-art performance on Flickr30k and ReferIt under the usual "seen" settings and performs significantly better than baseline in the zero-shot setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07129](http://arxiv.org/abs/1908.07129)

##### PDF
[http://arxiv.org/pdf/1908.07129](http://arxiv.org/pdf/1908.07129)

