---
layout: post
title: "Semantic-guided Encoder Feature Learning for Blurry Boundary Delineation"
date: 2019-06-10 22:31:08
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Dong Nie, Dinggang Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder architectures are widely adopted for medical image segmentation tasks. With the lateral skip connection, the models can obtain and fuse both semantic and resolution information in deep layers to achieve more accurate segmentation performance. However, in many applications (e.g., blurry boundary images), these models often cannot precisely locate complex boundaries and segment tiny isolated parts. To solve this challenging problem, we firstly analyze why simple skip connections are not enough to help accurately locate indistinct boundaries and argue that it is due to the fuzzy information in the skip connection provided in the encoder layers. Then we propose a semantic-guided encoder feature learning strategy to learn both high resolution and rich semantic encoder features so that we can more accurately locate the blurry boundaries, which can also enhance the network by selectively learning discriminative features. Besides, we further propose a soft contour constraint mechanism to model the blurry boundary detection. Experimental results on real clinical datasets show that our proposed method can achieve state-of-the-art segmentation accuracy, especially for the blurry regions. Further analysis also indicates that our proposed network components indeed contribute to the improvement of performance. Experiments on additional datasets validate the generalization ability of our proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04306](http://arxiv.org/abs/1906.04306)

##### PDF
[http://arxiv.org/pdf/1906.04306](http://arxiv.org/pdf/1906.04306)

