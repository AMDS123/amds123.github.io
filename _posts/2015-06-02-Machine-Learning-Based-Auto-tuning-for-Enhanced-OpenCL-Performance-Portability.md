---
layout: post
title: "Machine Learning Based Auto-tuning for Enhanced OpenCL Performance Portability"
date: 2015-06-02 11:19:56
categories: arXiv_CV
tags: arXiv_CV
author: Thomas L. Falch, Anne C. Elster
mathjax: true
---

* content
{:toc}

##### Abstract
Heterogeneous computing, which combines devices with different architectures, is rising in popularity, and promises increased performance combined with reduced energy consumption. OpenCL has been proposed as a standard for programing such systems, and offers functional portability. It does, however, suffer from poor performance portability, code tuned for one device must be re-tuned to achieve good performance on another device. In this paper, we use machine learning-based auto-tuning to address this problem. Benchmarks are run on a random subset of the entire tuning parameter configuration space, and the results are used to build an artificial neural network based model. The model can then be used to find interesting parts of the parameter space for further search. We evaluate our method with different benchmarks, on several devices, including an Intel i7 3770 CPU, an Nvidia K40 GPU and an AMD Radeon HD 7970 GPU. Our model achieves a mean relative error as low as 6.1%, and is able to find configurations as little as 1.3% worse than the global minimum.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1506.00842](https://arxiv.org/abs/1506.00842)

##### PDF
[https://arxiv.org/pdf/1506.00842](https://arxiv.org/pdf/1506.00842)

