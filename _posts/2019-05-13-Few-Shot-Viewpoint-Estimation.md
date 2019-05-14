---
layout: post
title: "Few-Shot Viewpoint Estimation"
date: 2019-05-13 10:54:28
categories: arXiv_CV
tags: arXiv_CV
author: Hung-Yu Tseng, Shalini De Mello, Jonathan Tremblay, Sifei Liu, Stan Birchfield, Ming-Hsuan Yang, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Viewpoint estimation for known categories of objects has been improved significantly thanks to deep networks and large datasets, but generalization to unknown categories is still very challenging. With an aim towards improving performance on unknown categories, we introduce the problem of category-level few-shot viewpoint estimation. We design a novel framework to successfully train viewpoint networks for new categories with few examples (10 or less). We formulate the problem as one of learning to estimate category-specific 3D canonical shapes, their associated depth estimates, and semantic 2D keypoints. We apply meta-learning to learn weights for our network that are amenable to category-specific few-shot fine-tuning. Furthermore, we design a flexible meta-Siamese network that maximizes information sharing during meta-learning. Through extensive experimentation on the ObjectNet3D and Pascal3D+ benchmark datasets, we demonstrate that our framework, which we call MetaView, significantly outperforms fine-tuning the state-of-the-art models with few examples, and that the specific architectural innovations of our method are crucial to achieving good performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04957](http://arxiv.org/abs/1905.04957)

##### PDF
[http://arxiv.org/pdf/1905.04957](http://arxiv.org/pdf/1905.04957)

