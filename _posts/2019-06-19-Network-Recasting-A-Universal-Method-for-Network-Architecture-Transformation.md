---
layout: post
title: "Network Recasting: A Universal Method for Network Architecture Transformation"
date: 2019-06-19 09:38:15
categories: arXiv_CV
tags: arXiv_CV Inference
author: Joonsang Yu, Sungbum Kang, Kiyoung Choi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes network recasting as a general method for network architecture transformation. The primary goal of this method is to accelerate the inference process through the transformation, but there can be many other practical applications. The method is based on block-wise recasting; it recasts each source block in a pre-trained teacher network to a target block in a student network. For the recasting, a target block is trained such that its output activation approximates that of the source block. Such a block-by-block recasting in a sequential manner transforms the network architecture while preserving the accuracy. This method can be used to transform an arbitrary teacher network type to an arbitrary student network type. It can even generate a mixed-architecture network that consists of two or more types of block. The network recasting can generate a network with fewer parameters and/or activations, which reduce the inference time significantly. Naturally, it can be used for network compression by recasting a trained network into a smaller network of the same type. Our experiments show that it outperforms previous compression approaches in terms of actual speedup on a GPU.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.05262](http://arxiv.org/abs/1809.05262)

##### PDF
[http://arxiv.org/pdf/1809.05262](http://arxiv.org/pdf/1809.05262)

