---
layout: post
title: "On the Capacity of Face Representation"
date: 2017-09-29 14:47:13
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Recognition Face_Recognition
author: Sixue Gong, Vishnu Naresh Boddeti, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
Face recognition is a widely used technology with numerous large-scale applications, such as surveillance, social media and law enforcement. There has been tremendous progress in face recognition accuracy over the past few decades, much of which can be attributed to deep learning based approaches during the last five years. Indeed, automated face recognition systems are now believed to surpass human performance in some scenarios. Despite this progress, a crucial question still remains unanswered: given a face representation, how many identities can it resolve? In other words, what is the capacity of the face representation? A scientific basis for estimating the capacity of a given face representation will not only benefit the evaluation and comparison of different face representation methods, but will also establish an upper bound on the scalability of an automatic face recognition system. We cast the face capacity estimation problem under the information theoretic framework of capacity of a Gaussian noise channel. By explicitly accounting for two sources of representational noise: epistemic (model) uncertainty and aleatoric (data) variability, our approach is able to estimate the capacity of any given face representation. To demonstrate the efficacy of our approach, we estimate the capacity of a 128-dimensional state-of-the-art deep neural network based face representation, FaceNet. Our numerical experiments indicate that, (a) our capacity estimation model yields a capacity upper bound of $1\times10^{12}$ for the FaceNet representation at a false acceptance rate (FAR) of 5%, (b) the capacity reduces drastically as you lower the desired FAR with an estimate of $2\times10^{7}$ and $6\times10^{3}$ at FAR of 0.1% and 0.001%, respectively), and (c) the performance of the FaceNet representation is significantly below the theoretical limit.

##### Abstract (translated by Google)
人脸识别是一种被广泛使用的技术，具有诸多监控，社交媒体和执法等大规模应用。在过去的几十年里，人脸识别的准确性已经取得了巨大的进步，其中很大一部分可以归因于过去五年的基于深度学习的方法。事实上，自动人脸识别系统现在被认为在某些情况下超过了人的表现。尽管取得了这样的进步，一个至关重要的问题仍然没有得到解答：给予一个面孔代表，可以解决多少身份？换句话说，人脸表征的能力是什么？估计给定人脸表征能力的科学依据不仅有利于不同人脸表征方法的评估和比较，而且还将建立自动人脸识别系统可扩展性的上界。在高斯噪声信道容量的信息理论框架下，我们提出了人脸容量估计问题。通过明确说明表征噪声的两个来源：认知（模型）不确定性和任意（数据）可变性，我们的方法能够估计任何给定人脸表征的能力。为了证明我们的方法的有效性，我们估计了一个128维的最先进的深度神经网络人脸表示FaceNet的能力。我们的数值实验表明，（a）我们的容量估计模型在错误接受率（FAR）为5％的情况下对于FaceNet表示产生容量上限$ 1 \ times10 ^ {12} $，（b）容量急剧下降因为您以FAR为0.1％和0.001％的估计值分别降低了$ 2 \ times10 ^ {7} $和$ 6 \ times10 ^ {3} $的估计FAR），并且（c）FaceNet表示的性能是大大低于理论极限。

##### URL
[https://arxiv.org/abs/1709.10433](https://arxiv.org/abs/1709.10433)

##### PDF
[https://arxiv.org/pdf/1709.10433](https://arxiv.org/pdf/1709.10433)

