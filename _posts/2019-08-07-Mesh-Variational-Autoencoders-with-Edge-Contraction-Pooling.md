---
layout: post
title: "Mesh Variational Autoencoders with Edge Contraction Pooling"
date: 2019-08-07 09:59:08
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN Deep_Learning
author: Yu-Jie Yuan, Yu-Kun Lai, Jie Yang, Hongbo Fu, Lin Gao
mathjax: true
---

* content
{:toc}

##### Abstract
3D shape analysis is an important research topic in computer vision and graphics. While existing methods have generalized image-based deep learning to meshes using graph-based convolutions, the lack of an effective pooling operation restricts the learning capability of their networks. In this paper, we propose a novel pooling operation for mesh datasets with the same connectivity but different geometry, by building a mesh hierarchy using mesh simplification. For this purpose, we develop a modified mesh simplification method to avoid generating highly irregularly sized triangles. Our pooling operation effectively encodes the correspondence between coarser and finer meshes in the hierarchy. We then present a variational auto-encoder structure with the edge contraction pooling and graph-based convolutions, to explore probability latent spaces of 3D surfaces. Our network requires far fewer parameters than the original mesh VAE and thus can handle denser models thanks to our new pooling operation and convolutional kernels. Our evaluation also shows that our method has better generalization ability and is more reliable in various applications, including shape generation, shape interpolation and shape embedding.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02507](http://arxiv.org/abs/1908.02507)

##### PDF
[http://arxiv.org/pdf/1908.02507](http://arxiv.org/pdf/1908.02507)

