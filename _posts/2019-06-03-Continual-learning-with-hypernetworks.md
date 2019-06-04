---
layout: post
title: "Continual learning with hypernetworks"
date: 2019-06-03 10:45:08
categories: arXiv_AI
tags: arXiv_AI Embedding Transfer_Learning Relation
author: Johannes von Oswald, Christian Henning, Jo&#xe3;o Sacramento, Benjamin F. Grewe
mathjax: true
---

* content
{:toc}

##### Abstract
Artificial neural networks suffer from catastrophic forgetting when they are sequentially trained on multiple tasks. To overcome this problem, we present a novel approach based on task-conditioned hypernetworks, i.e., networks that generate the weights of a target model based on task identity. Continual learning (CL) is less difficult for this class of models thanks to a simple key observation: instead of relying on recalling the input-output relations of all previously seen data, task-conditioned hypernetworks only require rehearsing previous weight realizations, which can be maintained in memory using a simple regularizer. Besides achieving good performance on standard CL benchmarks, additional experiments on long task sequences reveal that task-conditioned hypernetworks display an unprecedented capacity to retain previous memories. Notably, such long memory lifetimes are achieved in a compressive regime, when the number of trainable weights is comparable or smaller than target network size. We provide insight into the structure of low-dimensional task embedding spaces (the input space of the hypernetwork) and show that task-conditioned hypernetworks demonstrate transfer learning properties. Finally, forward information transfer is further supported by empirical results on a challenging CL benchmark based on the CIFAR-10/100 image datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00695](http://arxiv.org/abs/1906.00695)

##### PDF
[http://arxiv.org/pdf/1906.00695](http://arxiv.org/pdf/1906.00695)

