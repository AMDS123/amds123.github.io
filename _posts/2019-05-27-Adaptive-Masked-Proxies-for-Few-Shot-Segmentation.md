---
layout: post
title: "Adaptive Masked Proxies for Few-Shot Segmentation"
date: 2019-05-27 22:31:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding Semantic_Segmentation Deep_Learning
author: Mennatullah Siam, Boris Oreshkin, Martin Jagersand
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has thrived by training on large-scale datasets. However, for continual learning in applications such as robotics, it is critical to incrementally update its model in a sample efficient manner. We propose a novel method that constructs the new class weights from few labelled samples in the support set without back-propagation, relying on our adaptive masked proxies approach. It utilizes multi-resolution average pooling on the output embeddings masked with the label to act as a positive proxy for the new class, while fusing it with the previously learned class signatures. Our proposed method is evaluated on PASCAL-$5^i$ dataset and outperforms the state of the art in the 5-shot semantic segmentation. Unlike previous methods, our proposed approach does not require a second branch to estimate parameters or prototypes, which enables it to be used with 2-stream motion and appearance based segmentation networks. The proposed adaptive proxies allow the method to be used with a continuous data stream. Our online adaptation scheme is evaluated on the DAVIS and FBMS video object segmentation benchmark. We further propose a novel setup for evaluating continual learning of object segmentation which we name incremental PASCAL (iPASCAL) where our method has shown to outperform the baseline method. Code is publicly available at https://github.com/MSiam/AdaptiveMaskedProxies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11123](http://arxiv.org/abs/1902.11123)

##### PDF
[http://arxiv.org/pdf/1902.11123](http://arxiv.org/pdf/1902.11123)

