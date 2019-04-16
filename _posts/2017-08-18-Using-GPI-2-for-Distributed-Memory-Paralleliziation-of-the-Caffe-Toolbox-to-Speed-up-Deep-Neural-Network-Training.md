---
layout: post
title: "Using GPI-2 for Distributed Memory Paralleliziation of the Caffe Toolbox to Speed up Deep Neural Network Training"
date: 2017-08-18 12:24:45
categories: arXiv_CV
tags: arXiv_CV Face
author: Martin Kuehn, Janis Keuper, Franz-Josef Pfreundt
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Network (DNN) are currently of great inter- est in research and application. The training of these net- works is a compute intensive and time consuming task. To reduce training times to a bearable amount at reasonable cost we extend the popular Caffe toolbox for DNN with an efficient distributed memory communication pattern. To achieve good scalability we emphasize the overlap of computation and communication and prefer fine granu- lar synchronization patterns over global barriers. To im- plement these communication patterns we rely on the the Global address space Programming Interface version 2 (GPI-2) communication library. This interface provides a light-weight set of asynchronous one-sided communica- tion primitives supplemented by non-blocking fine gran- ular data synchronization mechanisms. Therefore, Caf- feGPI is the name of our parallel version of Caffe. First benchmarks demonstrate better scaling behavior com- pared with other extensions, e.g., the Intel TM Caffe. Even within a single symmetric multiprocessing machine with four graphics processing units, the CaffeGPI scales bet- ter than the standard Caffe toolbox. These first results demonstrate that the use of standard High Performance Computing (HPC) hardware is a valid cost saving ap- proach to train large DDNs. I/O is an other bottleneck to work with DDNs in a standard parallel HPC setting, which we will consider in more detail in a forthcoming paper.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.00095](https://arxiv.org/abs/1706.00095)

##### PDF
[https://arxiv.org/pdf/1706.00095](https://arxiv.org/pdf/1706.00095)

