---
layout: post
title: "Learning Student Networks via Feature Embedding"
date: 2018-12-17 03:21:20
categories: arXiv_CV
tags: arXiv_CV Knowledge Embedding CNN
author: Hanting Chen, Yunhe Wang, Chang Xu, Chao Xu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks have been widely used in numerous applications, but their demanding storage and computational resource requirements prevent their applications on mobile devices. Knowledge distillation aims to optimize a portable student network by taking the knowledge from a well-trained heavy teacher network. Traditional teacher-student based methods used to rely on additional fully-connected layers to bridge intermediate layers of teacher and student networks, which brings in a large number of auxiliary parameters. In contrast, this paper aims to propagate information from teacher to student without introducing new variables which need to be optimized. We regard the teacher-student paradigm from a new perspective of feature embedding. By introducing the locality preserving loss, the student network is encouraged to generate the low-dimensional features which could inherit intrinsic properties of their corresponding high-dimensional features from teacher network. The resulting portable network thus can naturally maintain the performance as that of the teacher network. Theoretical analysis is provided to justify the lower computation complexity of the proposed method. Experiments on benchmark datasets and well-trained networks suggest that the proposed algorithm is superior to state-of-the-art teacher-student learning methods in terms of computational and storage complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06597](http://arxiv.org/abs/1812.06597)

##### PDF
[http://arxiv.org/pdf/1812.06597](http://arxiv.org/pdf/1812.06597)

