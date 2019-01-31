---
layout: post
title: "Diversity Regularized Adversarial Learning"
date: 2019-01-30 13:44:08
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN
author: Babajide O. Ayinde, Keishin Nishihama, Jacek M. Zurada
mathjax: true
---

* content
{:toc}

##### Abstract
The two key players in Generative Adversarial Networks (GANs), the discriminator and generator, are usually parameterized as deep neural networks (DNNs). On many generative tasks, GANs achieve state-of-the-art performance but are often unstable to train and sometimes miss modes. A typical failure mode is the collapse of the generator to a single parameter configuration where its outputs are identical. When this collapse occurs, the gradient of the discriminator may point in similar directions for many similar points. We hypothesize that some of these shortcomings are in part due to primitive and redundant features extracted by discriminator and this can easily make the training stuck. We present a novel approach for regularizing adversarial models by enforcing diverse feature learning. In order to do this, both generator and discriminator are regularized by penalizing both negatively and positively correlated features according to their differentiation and based on their relative cosine distances. In addition to the gradient information from the adversarial loss made available by the discriminator, diversity regularization also ensures that a more stable gradient is provided to update both the generator and discriminator. Results indicate our regularizer enforces diverse features, stabilizes training, and improves image synthesis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10824](http://arxiv.org/abs/1901.10824)

##### PDF
[http://arxiv.org/pdf/1901.10824](http://arxiv.org/pdf/1901.10824)

