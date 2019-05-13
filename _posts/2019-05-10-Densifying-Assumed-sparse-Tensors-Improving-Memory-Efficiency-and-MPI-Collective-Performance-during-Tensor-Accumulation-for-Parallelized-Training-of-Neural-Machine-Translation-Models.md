---
layout: post
title: "Densifying Assumed-sparse Tensors: Improving Memory Efficiency and MPI Collective Performance during Tensor Accumulation for Parallelized Training of Neural Machine Translation Models"
date: 2019-05-10 09:44:35
categories: arXiv_CL
tags: arXiv_CL Sparse Attention
author: Derya Cavdar, Valeriu Codreanu, Can Karakus, John A. Lockman III, Damian Podareanu, Vikram Saletore, Alexander Sergeev, Don D. Smith II, Victor Suthichai, Quy Ta, Srinivas Varadharajan, Lucas A. Wilson, Rengan Xu, Pei Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation - using neural networks to translate human language - is an area of active research exploring new neuron types and network topologies with the goal of dramatically improving machine translation performance. Current state-of-the-art approaches, such as the multi-head attention-based transformer, require very large translation corpuses and many epochs to produce models of reasonable quality. Recent attempts to parallelize the official TensorFlow "Transformer" model across multiple nodes have hit roadblocks due to excessive memory use and resulting out of memory errors when performing MPI collectives. This paper describes modifications made to the Horovod MPI-based distributed training framework to reduce memory usage for transformer models by converting assumed-sparse tensors to dense tensors, and subsequently replacing sparse gradient gather with dense gradient reduction. The result is a dramatic increase in scale-out capability, with CPU-only scaling tests achieving 91% weak scaling efficiency up to 1200 MPI processes (300 nodes), and up to 65% strong scaling efficiency up to 400 MPI processes (200 nodes) using the Stampede2 supercomputer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04035](http://arxiv.org/abs/1905.04035)

##### PDF
[http://arxiv.org/pdf/1905.04035](http://arxiv.org/pdf/1905.04035)

