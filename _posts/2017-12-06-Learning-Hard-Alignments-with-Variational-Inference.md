---
layout: post
title: 'Learning Hard Alignments with Variational Inference'
date: 2017-12-06 07:46:36
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Caption Recognition
author: Dieterich Lawson, Chung-Cheng Chiu, George Tucker, Colin Raffel, Kevin Swersky, Navdeep Jaitly
---

* content
{:toc}

##### Abstract
There has recently been significant interest in hard attention models for tasks such as object recognition, visual captioning and speech recognition. Hard attention can offer benefits over soft attention such as decreased computational cost, but training hard attention models can be difficult because of the discrete latent variables they introduce. Previous work used REINFORCE and Q-learning to approach these issues, but those methods can provide high-variance gradient estimates and be slow to train. In this paper, we tackle the problem of learning hard attention for a sequential task using variational inference methods, specifically the recently introduced VIMCO and NVIL. Furthermore, we propose a novel baseline that adapts VIMCO to this setting. We demonstrate our method on a phoneme recognition task in clean and noisy environments and show that our method outperforms REINFORCE, with the difference being greater for a more complicated task.

##### Abstract (translated by Google)
近来，人们对诸如对象识别，视觉字幕和语音识别等任务的硬注意模型产生了极大的兴趣。注意力的提高可以带来诸如降低计算成本等软注意力的好处，但是由于它们引入的离散的潜变量，难以训练难以关注的模型。以前的工作使用了增强和Q学习来处理这些问题，但是这些方法可以提供高方差梯度估计并且训练缓慢。在本文中，我们利用变分推理方法，特别是最近引入的VIMCO和NVIL，解决了顺序任务学习困难的问题。此外，我们提出了一个新的基准，使VIMCO适应这个设置。我们在干净和嘈杂的环境中演示我们的方法在音素识别任务，并表明我们的方法胜过增强，差异更大的一个更复杂的任务。

##### URL
[https://arxiv.org/abs/1705.05524](https://arxiv.org/abs/1705.05524)

