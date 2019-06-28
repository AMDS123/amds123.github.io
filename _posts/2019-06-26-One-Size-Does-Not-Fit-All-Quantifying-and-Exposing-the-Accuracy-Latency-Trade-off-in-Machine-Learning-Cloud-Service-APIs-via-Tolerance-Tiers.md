---
layout: post
title: "One Size Does Not Fit All: Quantifying and Exposing the Accuracy-Latency Trade-off in Machine Learning Cloud Service APIs via Tolerance Tiers"
date: 2019-06-26 19:35:59
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Image_Classification Classification Recognition
author: Matthew Halpern, Behzad Boroujerdian, Todd Mummert, Evelyn Duesterwald, Vijay Janapa Reddi
mathjax: true
---

* content
{:toc}

##### Abstract
Today's cloud service architectures follow a "one size fits all" deployment strategy where the same service version instantiation is provided to the end users. However, consumers are broad and different applications have different accuracy and responsiveness requirements, which as we demonstrate renders the "one size fits all" approach inefficient in practice. We use a production-grade speech recognition engine, which serves several thousands of users, and an open source computer vision based system, to explain our point. To overcome the limitations of the "one size fits all" approach, we recommend Tolerance Tiers where each MLaaS tier exposes an accuracy/responsiveness characteristic, and consumers can programmatically select a tier. We evaluate our proposal on the CPU-based automatic speech recognition (ASR) engine and cutting-edge neural networks for image classification deployed on both CPUs and GPUs. The results show that our proposed approach provides an MLaaS cloud service architecture that can be tuned by the end API user or consumer to outperform the conventional "one size fits all" approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11307](http://arxiv.org/abs/1906.11307)

##### PDF
[http://arxiv.org/pdf/1906.11307](http://arxiv.org/pdf/1906.11307)

