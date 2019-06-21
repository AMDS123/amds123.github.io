---
layout: post
title: "Spatial Pyramid Encoding with Convex Length Normalization for Text-Independent Speaker Verification"
date: 2019-06-19 20:13:27
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Youngmoon Jung, Younggwan Kim, Hyungjun Lim, Yeunju Choi, Hoirin Kim
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new pooling method called spatial pyramid encoding (SPE) to generate speaker embeddings for text-independent speaker verification. We first partition the output feature maps from a deep residual network (ResNet) into increasingly fine sub-regions and extract speaker embeddings from each sub-region through a learnable dictionary encoding layer. These embeddings are concatenated to obtain the final speaker representation. The SPE layer not only generates a fixed-dimensional speaker embedding for a variable-length speech segment, but also aggregates the information of feature distribution from multi-level temporal bins. Furthermore, we apply deep length normalization by augmenting the loss function with ring loss. By applying ring loss, the network gradually learns to normalize the speaker embeddings using model weights themselves while preserving convexity, leading to more robust speaker embeddings. Experiments on the VoxCeleb1 dataset show that the proposed system using the SPE layer and ring loss-based deep length normalization outperforms both i-vector and d-vector baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08333](http://arxiv.org/abs/1906.08333)

##### PDF
[http://arxiv.org/pdf/1906.08333](http://arxiv.org/pdf/1906.08333)

