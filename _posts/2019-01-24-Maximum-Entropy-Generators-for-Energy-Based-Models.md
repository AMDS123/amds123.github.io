---
layout: post
title: "Maximum Entropy Generators for Energy-Based Models"
date: 2019-01-24 17:03:41
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Detection
author: Rithesh Kumar, Anirudh Goyal, Aaron Courville, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised learning is about capturing dependencies between variables and is driven by the contrast between the probable vs. improbable configurations of these variables, often either via a generative model that only samples probable ones or with an energy function (unnormalized log-density) that is low for probable ones and high for improbable ones. Here, we consider learning both an energy function and an efficient approximate sampling mechanism. Whereas the discriminator in generative adversarial networks (GANs) learns to separate data and generator samples, introducing an entropy maximization regularizer on the generator can turn the interpretation of the critic into an energy function, which separates the training distribution from everything else, and thus can be used for tasks like anomaly or novelty detection. Then, we show how Markov Chain Monte Carlo can be done in the generator latent space whose samples can be mapped to data space, producing better samples. These samples are used for the negative phase gradient required to estimate the log-likelihood gradient of the data space energy function. To maximize entropy at the output of the generator, we take advantage of recently introduced neural estimators of mutual information. We find that in addition to producing a useful scoring function for anomaly detection, the resulting approach produces sharp samples while covering the modes well, leading to high Inception and Frechet scores.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08508](http://arxiv.org/abs/1901.08508)

##### PDF
[http://arxiv.org/pdf/1901.08508](http://arxiv.org/pdf/1901.08508)

