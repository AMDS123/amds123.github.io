---
layout: post
title: "Approximate Distribution Matching for Sequence-to-Sequence Learning"
date: 2018-09-02 04:38:56
categories: arXiv_CV
tags: arXiv_CV Image_Caption Summarization Caption Optimization RNN Prediction
author: Wenhu Chen, Guanlin Li, Shujie Liu, Zhirui Zhang, Mu Li, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-Sequence models were introduced to tackle many real-life problems like machine translation, summarization, image captioning, etc. The standard optimization algorithms are mainly based on example-to-example matching like maximum likelihood estimation, which is known to suffer from data sparsity problem. Here we present an alternate view to explain sequence-to-sequence learning as a distribution matching problem, where each source or target example is viewed to represent a local latent distribution in the source or target domain. Then, we interpret sequence-to-sequence learning as learning a transductive model to transform the source local latent distributions to match their corresponding target distributions. In our framework, we approximate both the source and target latent distributions with recurrent neural networks (augmenter). During training, the parallel augmenters learn to better approximate the local latent distributions, while the sequence prediction model learns to minimize the KL-divergence of the transformed source distributions and the approximated target distributions. This algorithm can alleviate the data sparsity issues in sequence learning by locally augmenting more unseen data pairs and increasing the model's robustness. Experiments conducted on machine translation and image captioning consistently demonstrate the superiority of our proposed algorithm over the other competing algorithms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.08003](https://arxiv.org/abs/1808.08003)

##### PDF
[https://arxiv.org/pdf/1808.08003](https://arxiv.org/pdf/1808.08003)

