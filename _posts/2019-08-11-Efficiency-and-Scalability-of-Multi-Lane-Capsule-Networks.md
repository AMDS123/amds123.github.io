---
layout: post
title: "Efficiency and Scalability of Multi-Lane Capsule Networks"
date: 2019-08-11 17:04:14
categories: arXiv_CV
tags: arXiv_CV GAN
author: Vanderson M. do Rosario, Mauricio Breternitz Jr., Edson Borin
mathjax: true
---

* content
{:toc}

##### Abstract
Some Deep Neural Networks (DNN) have what we call lanes, or they can be reorganized as such. Lanes are paths in the network which are data-independent and typically learn different features or add resilience to the network. Given their data-independence, lanes are amenable for parallel processing. The Multi-lane CapsNet (MLCN) is a proposed reorganization of the Capsule Network which is shown to achieve better accuracy while bringing highly-parallel lanes. However, the efficiency and scalability of MLCN had not been systematically examined. In this work, we study the MLCN network with multiple GPUs finding that it is 2x more efficient than the original CapsNet when using model-parallelism. Further, we present the load balancing problem of distributing heterogeneous lanes in homogeneous or heterogeneous accelerators and show that a simple greedy heuristic can be almost 50% faster than a naive random approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03935](https://arxiv.org/abs/1908.03935)

##### PDF
[https://arxiv.org/pdf/1908.03935](https://arxiv.org/pdf/1908.03935)

