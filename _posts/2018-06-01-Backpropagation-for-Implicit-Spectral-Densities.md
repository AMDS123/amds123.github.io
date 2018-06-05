---
layout: post
title: "Backpropagation for Implicit Spectral Densities"
date: 2018-06-01 18:28:20
categories: arXiv_AI
tags: arXiv_AI GAN
author: Aditya Ramesh, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
Most successful machine intelligence systems rely on gradient-based learning, which is made possible by backpropagation. Some systems are designed to aid us in interpreting data when explicit goals cannot be provided. These unsupervised systems are commonly trained by backpropagating through a likelihood function. We introduce a tool that allows us to do this even when the likelihood is not explicitly set, by instead using the implicit likelihood of the model. Explicitly defining the likelihood often entails making heavy-handed assumptions that impede our ability to solve challenging tasks. On the other hand, the implicit likelihood of the model is accessible without the need for such assumptions. Our tool, which we call spectral backpropagation, allows us to optimize it in much greater generality than what has been attempted before. GANs can also be viewed as a technique for optimizing implicit likelihoods. We study them using spectral backpropagation in order to demonstrate robustness for high-dimensional problems, and identify two novel properties of the generator G: (1) there exist aberrant, nonsensical outputs to which G assigns very high likelihood, and (2) the eigenvectors of the metric induced by G over latent space correspond to quasi-disentangled explanatory factors.

##### Abstract (translated by Google)
大多数成功的机器智能系统都依赖基于渐变的学习，这是通过反向传播实现的。有些系统旨在帮助我们在无法提供明确目标时解释数据。这些无监督系统通常通过似然函数反向传播进行训练。我们引入了一种工具，即使在没有明确设定可能性的情况下，我们也可以通过使用模型的隐式可能性来做到这一点。明确界定可能性通常需要做出严重的假设，这阻碍了我们解决具有挑战性任务的能力。另一方面，模型的隐含可能性可以在不需要这种假设的情况下获得。我们称之为光谱反向传播的工具，使我们能够比以前尝试的更加普遍地优化它。 GAN也可以被看作是一种优化隐式可能性的技术。我们使用光谱反向传播来研究它们，以证明高维问题的鲁棒性，并确定了生成器G的两个新特性：（1）存在异常的，无意义的输出，G赋予非常高的可能性;（2）特征向量由G引起的潜在空间度量对应于准解开解释因子。

##### URL
[http://arxiv.org/abs/1806.00499](http://arxiv.org/abs/1806.00499)

##### PDF
[http://arxiv.org/pdf/1806.00499](http://arxiv.org/pdf/1806.00499)

