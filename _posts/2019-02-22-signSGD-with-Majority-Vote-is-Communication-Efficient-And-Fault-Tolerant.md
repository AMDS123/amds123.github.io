---
layout: post
title: "signSGD with Majority Vote is Communication Efficient And Fault Tolerant"
date: 2019-02-22 19:55:48
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Jeremy Bernstein, Jiawei Zhao, Kamyar Azizzadenesheli, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Training neural networks on large datasets can be accelerated by distributing the workload over a network of machines. As datasets grow ever larger, networks of hundreds or thousands of machines become economically viable. The time cost of communicating gradients limits the effectiveness of using such large machine counts, as may the increased chance of network faults. We explore a particularly simple algorithm for robust, communication-efficient learning---signSGD. Workers transmit only the sign of their gradient vector to a server, and the overall update is decided by a majority vote. This algorithm uses $32\times$ less communication per iteration than full-precision, distributed SGD. Under natural conditions verified by experiment, we prove that signSGD converges in the large and mini-batch settings, establishing convergence for a parameter regime of Adam as a byproduct. Aggregating sign gradients by majority vote means that no individual worker has too much power. We prove that unlike SGD, majority vote is robust when up to 50% of workers behave adversarially. The class of adversaries we consider includes as special cases those that invert or randomise their gradient estimate. On the practical side, we built our distributed training system in Pytorch. Benchmarking against the state of the art collective communications library (NCCL), our framework---with the parameter server housed entirely on one machine---led to a 25% reduction in time for training resnet50 on Imagenet when using 15 AWS p3.2xlarge machines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.05291](http://arxiv.org/abs/1810.05291)

##### PDF
[http://arxiv.org/pdf/1810.05291](http://arxiv.org/pdf/1810.05291)

