---
layout: post
title: "Deep Comparison: Relation Columns for Few-Shot Learning"
date: 2018-11-17 04:46:05
categories: arXiv_CV
tags: arXiv_CV Embedding Deep_Learning Relation Recognition
author: Xueting Zhang, Flood Sung, Yuting Qiang, Yongxin Yang, Timothy M. Hospedales
mathjax: true
---

* content
{:toc}

##### Abstract
Few-shot deep learning is a topical challenge area for scaling visual recognition to open-ended growth in the space of categories to recognise. A promising line work towards realising this vision is deep networks that learn to match queries with stored training images. However, methods in this paradigm usually train a deep embedding followed by a single linear classifier. Our insight is that effective general-purpose matching requires discrimination with regards to features at multiple abstraction levels. We therefore propose a new framework termed \modelnamefull that decomposes embedding learning into a sequence of modules, and pairs each with a relation module. The relation modules compute a non-linear metric to score the match using the corresponding embedding module's representation. To ensure that all embedding module's features are used, the relation modules are deeply supervised. Finally generalisation is further improved by a learned noise regulariser. The resulting network achieves state of the art performance on both miniImageNet and tieredImageNet, while retaining the appealing simplicity and efficiency of deep metric learning approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07100](http://arxiv.org/abs/1811.07100)

##### PDF
[http://arxiv.org/pdf/1811.07100](http://arxiv.org/pdf/1811.07100)

