---
layout: post
title: "A General Decoupled Learning Framework for Parameterized Image Operators"
date: 2019-07-11 00:22:39
categories: arXiv_CV
tags: arXiv_CV
author: Qingnan Fan, Dongdong Chen, Lu Yuan, Gang Hua, Nenghai Yu, Baoquan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Many different deep networks have been used to approximate, accelerate or improve traditional image operators. Among these traditional operators, many contain parameters which need to be tweaked to obtain the satisfactory results, which we refer to as parameterized image operators. However, most existing deep networks trained for these operators are only designed for one specific parameter configuration, which does not meet the needs of real scenarios that usually require flexible parameters settings. To overcome this limitation, we propose a new decoupled learning algorithm to learn from the operator parameters to dynamically adjust the weights of a deep network for image operators, denoted as the base network. The learned algorithm is formed as another network, namely the weight learning network, which can be end-to-end jointly trained with the base network. Experiments demonstrate that the proposed framework can be successfully applied to many traditional parameterized image operators. To accelerate the parameter tuning for practical scenarios, the proposed framework can be further extended to dynamically change the weights of only one single layer of the base network while sharing most computation cost. We demonstrate that this cheap parameter-tuning extension of the proposed decoupled learning framework even outperforms the state-of-the-art alternative approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05852](http://arxiv.org/abs/1907.05852)

##### PDF
[http://arxiv.org/pdf/1907.05852](http://arxiv.org/pdf/1907.05852)

