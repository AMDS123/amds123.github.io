---
layout: post
title: "LOGAN: Unpaired Shape Transform in Latent Overcomplete Space"
date: 2019-03-25 08:20:48
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Kangxue Yin, Zhiqin Chen, Hui Huang, Daniel Cohen-Or, Hao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We present LOGAN, a deep neural network aimed at learning generic shape transforms from unpaired domains. The network is trained on two sets of shapes, e.g., tables and chairs, but there is neither a pairing between shapes in the two domains to supervise the shape translation nor any point-wise correspondence between any shapes. Once trained, LOGAN takes a shape from one domain and transforms it into the other. Our network consists of an autoencoder to encode shapes from the two input domains into a common latent space, where the latent codes encode multi-scale shape features in an overcomplete manner. The translator is based on a generative adversarial network (GAN), operating in the latent space, where an adversarial loss enforces cross-domain translation while a feature preservation loss ensures that the right shape features are preserved for a natural shape transform. We conduct various ablation studies to validate each of our key network designs and demonstrate superior capabilities in unpaired shape transforms on a variety of examples over baselines and state-of-the-art approaches. We show that our network is able to learn what shape features to preserve during shape transforms, either local or non-local, whether content or style, etc., depending solely on the input domain pairs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10170](http://arxiv.org/abs/1903.10170)

##### PDF
[http://arxiv.org/pdf/1903.10170](http://arxiv.org/pdf/1903.10170)

