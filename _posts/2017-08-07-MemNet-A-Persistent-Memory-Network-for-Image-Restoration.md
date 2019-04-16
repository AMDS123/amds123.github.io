---
layout: post
title: "MemNet: A Persistent Memory Network for Image Restoration"
date: 2017-08-07 17:20:58
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Attention CNN
author: Ying Tai, Jian Yang, Xiaoming Liu, Chunyan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, very deep convolutional neural networks (CNNs) have been attracting considerable attention in image restoration. However, as the depth grows, the long-term dependency problem is rarely realized for these very deep models, which results in the prior states/layers having little influence on the subsequent ones. Motivated by the fact that human thoughts have persistency, we propose a very deep persistent memory network (MemNet) that introduces a memory block, consisting of a recursive unit and a gate unit, to explicitly mine persistent memory through an adaptive learning process. The recursive unit learns multi-level representations of the current state under different receptive fields. The representations and the outputs from the previous memory blocks are concatenated and sent to the gate unit, which adaptively controls how much of the previous states should be reserved, and decides how much of the current state should be stored. We apply MemNet to three image restoration tasks, i.e., image denosing, super-resolution and JPEG deblocking. Comprehensive experiments demonstrate the necessity of the MemNet and its unanimous superiority on all three tasks over the state of the arts. Code is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.02209](https://arxiv.org/abs/1708.02209)

##### PDF
[https://arxiv.org/pdf/1708.02209](https://arxiv.org/pdf/1708.02209)

