---
layout: post
title: "Adversarially-Trained Normalized Noisy-Feature Auto-Encoder for Text Generation"
date: 2018-11-10 06:05:53
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Text_Generation RNN
author: Xiang Zhang, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
This article proposes Adversarially-Trained Normalized Noisy-Feature Auto-Encoder (ATNNFAE) for byte-level text generation. An ATNNFAE consists of an auto-encoder where the internal code is normalized on the unit sphere and corrupted by additive noise. Simultaneously, a replica of the decoder (sharing the same parameters as the AE decoder) is used as the generator and fed with random latent vectors. An adversarial discriminator is trained to distinguish training samples reconstructed from the AE from samples produced through the random-input generator, making the entire generator-discriminator path differentiable for discrete data like text. The combined effect of noise injection in the code and shared weights between the decoder and the generator can prevent the mode collapsing phenomenon commonly observed in GANs. Since perplexity cannot be applied to non-sequential text generation, we propose a new evaluation method using the total variance distance between frequencies of hash-coded byte-level n-grams (NGTVD). NGTVD is a single benchmark that can characterize both the quality and the diversity of the generated texts. Experiments are offered in 6 large-scale datasets in Arabic, Chinese and English, with comparisons against n-gram baselines and recurrent neural networks (RNNs). Ablation study on both the noise level and the discriminator is performed. We find that RNNs have trouble competing with the n-gram baselines, and the ATNNFAE results are generally competitive.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04201](http://arxiv.org/abs/1811.04201)

##### PDF
[http://arxiv.org/pdf/1811.04201](http://arxiv.org/pdf/1811.04201)

