---
layout: post
title: "RNNFast: An Accelerator for Recurrent Neural Networks Using Domain Wall Memory"
date: 2018-11-07 18:14:50
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition RNN Recognition
author: Mohammad Hossein Samavatian, Anys Bacha, Li Zhou, Radu Teodorescu
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) are an important class of neural networks designed to retain and incorporate context into current decisions. RNNs are particularly well suited for machine learning problems in which context is important, such as speech recognition or language translation. This work presents RNNFast, a hardware accelerator for RNNs that leverages an emerging class of non-volatile memory called domain-wall memory (DWM). We show that DWM is very well suited for RNN acceleration due to its very high density and low read/write energy. At the same time, the sequential nature of input/weight processing of RNNs mitigates one of the downsides of DWM, which is the linear (rather than constant) data access time. RNNFast is very efficient and highly scalable, with flexible mapping of logical neurons to RNN hardware blocks. The basic hardware primitive, the RNN processing element (PE) includes custom DWM-based multiplication, sigmoid and tanh units for high density and low-energy. The accelerator is designed to minimize data movement by closely interleaving DWM storage and computation. We compare our design with a state-of-the-art GPGPU and find 21.8x better performance with 70x lower energy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.07609](https://arxiv.org/abs/1812.07609)

##### PDF
[https://arxiv.org/pdf/1812.07609](https://arxiv.org/pdf/1812.07609)

