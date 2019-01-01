---
layout: post
title: "A Curriculum Domain Adaptation Approach to the Semantic Segmentation of Urban Scenes"
date: 2018-12-28 21:54:02
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction Relation
author: Yang Zhang, Philip David, Hassan Foroosh, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
During the last half decade, convolutional neural networks (CNNs) have triumphed over semantic segmentation, which is one of the core tasks in many applications such as autonomous driving and augmented reality. However, to train CNNs requires a considerable amount of data, which is difficult to collect and laborious to annotate. Recent advances in computer graphics make it possible to train CNNs on photo-realistic synthetic imagery with computer-generated annotations. Despite this, the domain mismatch between the real images and the synthetic data hinders the models' performance. Hence, we propose a curriculum-style learning approach to minimizing the domain gap in urban scene semantic segmentation. The curriculum domain adaptation solves easy tasks first to infer necessary properties about the target domain; in particular, the first task is to learn global label distributions over images and local distributions over landmark superpixels. These are easy to estimate because images of urban scenes have strong idiosyncrasies (e.g., the size and spatial relations of buildings, streets, cars, etc.). We then train a segmentation network, while regularizing its predictions in the target domain to follow those inferred properties. In experiments, our method outperforms the baselines on two datasets and two backbone networks. We also report extensive ablation studies about our approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.09953](https://arxiv.org/abs/1812.09953)

##### PDF
[https://arxiv.org/pdf/1812.09953](https://arxiv.org/pdf/1812.09953)

