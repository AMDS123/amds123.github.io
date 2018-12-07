---
layout: post
title: "DNQ: Dynamic Network Quantization"
date: 2018-12-06 07:06:17
categories: arXiv_CV
tags: arXiv_CV
author: Yuhui Xu, Shuai Zhang, Yingyong Qi, Jiaxian Guo, Weiyao Lin, Hongkai Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Network quantization is an effective method for the deployment of neural networks on memory and energy constrained mobile devices. In this paper, we propose a Dynamic Network Quantization (DNQ) framework which is composed of two modules: a bit-width controller and a quantizer. Unlike most existing quantization methods that use a universal quantization bit-width for the whole network, we utilize policy gradient to train an agent to learn the bit-width of each layer by the bit-width controller. This controller can make a trade-off between accuracy and compression ratio. Given the quantization bit-width sequence, the quantizer adopts the quantization distance as the criterion of the weights importance during quantization. We extensively validate the proposed approach on various main-stream neural networks and obtain impressive results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02375](http://arxiv.org/abs/1812.02375)

##### PDF
[http://arxiv.org/pdf/1812.02375](http://arxiv.org/pdf/1812.02375)

