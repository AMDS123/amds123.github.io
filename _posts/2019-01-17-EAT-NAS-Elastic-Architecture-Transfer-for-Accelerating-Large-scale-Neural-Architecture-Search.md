---
layout: post
title: "EAT-NAS: Elastic Architecture Transfer for Accelerating Large-scale Neural Architecture Search"
date: 2019-01-17 16:48:12
categories: arXiv_CV
tags: arXiv_CV
author: Jiemin Fang, Yukang Chen, Xinbang Zhang, Qian Zhang, Chang Huang, Gaofeng Meng, Wenyu Liu, Xinggang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture search (NAS) methods have been proposed to release human experts from tedious architecture engineering. However, most current methods are constrained in small-scale search due to the issue of computational resources. Meanwhile, directly applying architectures searched on small datasets to large-scale tasks often bears no performance guarantee. This limitation impedes the wide use of NAS on large-scale tasks. To overcome this obstacle, we propose an elastic architecture transfer mechanism for accelerating large-scale neural architecture search (EAT-NAS). In our implementations, architectures are first searched on a small dataset (the width and depth of architectures are taken into consideration as well), e.g., CIFAR-10, and the best is chosen as the basic architecture. Then the whole architecture is transferred with elasticity. We accelerate the search process on a large-scale dataset, e.g., the whole ImageNet dataset, with the help of the basic architecture. What we propose is not only a NAS method but a mechanism for architecture-level transfer. In our experiments, we obtain two final models EATNet-A and EATNet-B that achieve competitive accuracies, 73.8% and 73.7% on ImageNet, respectively, which also surpass the models searched from scratch on ImageNet under the same settings. For computational cost, EAT-NAS takes only less than 5 days on 8 TITAN X GPUs, which is significantly less than the computational consumption of the state-of-the-art large-scale NAS methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.05884](https://arxiv.org/abs/1901.05884)

##### PDF
[https://arxiv.org/pdf/1901.05884](https://arxiv.org/pdf/1901.05884)

