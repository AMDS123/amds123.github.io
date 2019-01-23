---
layout: post
title: "Energy Confused Adversarial Metric Learning for Zero-Shot Image Retrieval and Clustering"
date: 2019-01-22 04:23:21
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Regularization Adversarial Embedding
author: Binghui Chen, Weihong Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Deep metric learning has been widely applied in many computer vision tasks, and recently, it is more attractive in \emph{zero-shot image retrieval and clustering}(ZSRC) where a good embedding is requested such that the unseen classes can be distinguished well. Most existing works deem this 'good' embedding just to be the discriminative one and thus race to devise powerful metric objectives or hard-sample mining strategies for leaning discriminative embedding. However, in this paper, we first emphasize that the generalization ability is a core ingredient of this 'good' embedding as well and largely affects the metric performance in zero-shot settings as a matter of fact. Then, we propose the Energy Confused Adversarial Metric Learning(ECAML) framework to explicitly optimize a robust metric. It is mainly achieved by introducing an interesting Energy Confusion regularization term, which daringly breaks away from the traditional metric learning idea of discriminative objective devising, and seeks to 'confuse' the learned model so as to encourage its generalization ability by reducing overfitting on the seen classes. We train this confusion term together with the conventional metric objective in an adversarial manner. Although it seems weird to 'confuse' the network, we show that our ECAML indeed serves as an efficient regularization technique for metric learning and is applicable to various conventional metric methods. This paper empirically and experimentally demonstrates the importance of learning embedding with good generalization, achieving state-of-the-art performances on the popular CUB, CARS, Stanford Online Products and In-Shop datasets for ZSRC tasks. \textcolor[rgb]{1, 0, 0}{Code available at <a href="http://www.bhchen.cn/">this http URL</a>}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07169](http://arxiv.org/abs/1901.07169)

##### PDF
[http://arxiv.org/pdf/1901.07169](http://arxiv.org/pdf/1901.07169)

