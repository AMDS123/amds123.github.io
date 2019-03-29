---
layout: post
title: "Laplace Landmark Localization"
date: 2019-03-27 18:14:50
categories: arXiv_CV
tags: arXiv_CV Adversarial Detection
author: Joseph P Robinson, Yuncheng Li, Ning Zhang, Yun Fu, and Sergey Tulyakov
mathjax: true
---

* content
{:toc}

##### Abstract
Landmark localization in images and videos is a classic problem solved in various ways. Nowadays, with deep networks prevailing throughout machine learning, there are revamped interests in pushing facial landmark detection technologies to handle more challenging data. Most efforts use network objectives based on L1 or L2 norms, which have several disadvantages. First of all, the locations of landmarks are determined from generated heatmaps (i.e., confidence maps) from which predicted landmark locations (i.e., the means) get penalized without accounting for the spread: a high scatter corresponds to low confidence and vice-versa. For this, we introduce a LaplaceKL objective that penalizes for a low confidence. Another issue is a dependency on labeled data, which are expensive to obtain and susceptible to error. To address both issues we propose an adversarial training framework that leverages unlabeled data to improve model performance. Our method claims state-of-the-art on all of the 300W benchmarks and ranks second-to-best on the Annotated Facial Landmarks in the Wild (AFLW) dataset. Furthermore, our model is robust with a reduced size: 1/8 the number of channels (i.e., 0.0398MB) is comparable to state-of-that-art in real-time on CPU. Thus, we show that our method is of high practical value to real-life application.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11633](http://arxiv.org/abs/1903.11633)

##### PDF
[http://arxiv.org/pdf/1903.11633](http://arxiv.org/pdf/1903.11633)

