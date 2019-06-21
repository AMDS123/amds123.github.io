---
layout: post
title: "The trade-off between long-term memory and smoothness for recurrent networks"
date: 2019-06-20 07:53:31
categories: arXiv_CV
tags: arXiv_CV RNN Gradient_Descent
author: Antônio H. Ribeiro, Koen Tiels, Luis A. Aguirre, Thomas B. Schön
mathjax: true
---

* content
{:toc}

##### Abstract
Training recurrent neural networks (RNNs) that possess long-term memory is challenging. We provide insight into the trade-off between the smoothness of the cost function and the memory retention capabilities of the network. We express both aspects in terms of the Lipschitz constant of the dynamics modeled by the network. This allows us to make a distinction between three types of regions in the parameter space. In the first region, the network experiences problems in retaining long-term information, while at the same time the cost function is smooth and easy for gradient descent to navigate in. In the second region, the amount of stored information increases with time and the cost function is intricate and full of local minima. The third region is in between the two other regions and here the RNN is able to retain long-term information. Based on these theoretical findings we present the hypothesis that good parameter choices for the RNN are located in between the well-behaved and the ill-behaved cost function regions. The concepts presented in the paper are illustrated by artificially generated and real examples.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.08482](https://arxiv.org/abs/1906.08482)

##### PDF
[https://arxiv.org/pdf/1906.08482](https://arxiv.org/pdf/1906.08482)

