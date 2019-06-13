---
layout: post
title: "Suppressing Model Overfitting for Image Super-Resolution Networks"
date: 2019-06-11 20:41:49
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Ruicheng Feng, Jinjin Gu, Yu Qiao, Chao Dong
mathjax: true
---

* content
{:toc}

##### Abstract
Large deep networks have demonstrated competitive performance in single image super-resolution (SISR), with a huge volume of data involved. However, in real-world scenarios, due to the limited accessible training pairs, large models exhibit undesirable behaviors such as overfitting and memorization. To suppress model overfitting and further enjoy the merits of large model capacity, we thoroughly investigate generic approaches for supplying additional training data pairs. In particular, we introduce a simple learning principle MixUp to train networks on interpolations of sample pairs, which encourages networks to support linear behavior in-between training samples. In addition, we propose a data synthesis method with learned degradation, enabling models to use extra high-quality images with higher content diversity. This strategy proves to be successful in reducing biases of data. By combining these components -- MixUp and synthetic training data, large models can be trained without overfitting under very limited data samples and achieve satisfactory generalization performance. Our method won the second place in NTIRE2019 Real SR Challenge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04809](http://arxiv.org/abs/1906.04809)

##### PDF
[http://arxiv.org/pdf/1906.04809](http://arxiv.org/pdf/1906.04809)

