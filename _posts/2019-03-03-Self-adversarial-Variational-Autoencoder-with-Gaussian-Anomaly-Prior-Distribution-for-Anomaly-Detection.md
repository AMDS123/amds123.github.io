---
layout: post
title: "Self-adversarial Variational Autoencoder with Gaussian Anomaly Prior Distribution for Anomaly Detection"
date: 2019-03-03 13:26:19
categories: arXiv_AI
tags: arXiv_AI Regularization Adversarial Detection
author: Xuhong Wang, Ying Du, Shijie Lin, Ping Cui, Yupu Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep generative models have become increasingly popular in unsupervised anomaly detection. However, deep generative models aim at recovering the data distribution rather than detecting anomalies. Besides, deep generative models have the risk of overfitting training samples, which has disastrous effects on anomaly detection performance. To solve the above two problems, we propose a Self-adversarial Variational Autoencoder with a Gaussian anomaly prior assumption. We assume that both the anomalous and the normal prior distribution are Gaussian and have overlaps in the latent space. Therefore, a Gaussian transformer net T is trained to synthesize anomalous but near-normal latent variables. Keeping the original training objective of Variational Autoencoder, besides, the generator G tries to distinguish between the normal latent variables and the anomalous ones synthesized by T, and the encoder E is trained to discriminate whether the output of G is real. These new objectives we added not only give both G and E the ability to discriminate but also introduce additional regularization to prevent overfitting. Compared with the SOTA baselines, the proposed model achieves significant improvements in extensive experiments. Datasets and our model are available at a Github repository.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00904](http://arxiv.org/abs/1903.00904)

##### PDF
[http://arxiv.org/pdf/1903.00904](http://arxiv.org/pdf/1903.00904)

