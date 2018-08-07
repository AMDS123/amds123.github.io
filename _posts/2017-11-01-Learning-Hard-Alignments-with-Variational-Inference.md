---
layout: post
title: "Learning Hard Alignments with Variational Inference"
date: 2017-11-01 19:08:18
categories: arXiv_CV
tags: arXiv_CV Attention Speech_Recognition Caption Inference Recognition
author: Dieterich Lawson, Chung-Cheng Chiu, George Tucker, Colin Raffel, Kevin Swersky, Navdeep Jaitly
mathjax: true
---

* content
{:toc}

##### Abstract
There has recently been significant interest in hard attention models for tasks such as object recognition, visual captioning and speech recognition. Hard attention can offer benefits over soft attention such as decreased computational cost, but training hard attention models can be difficult because of the discrete latent variables they introduce. Previous work used REINFORCE and Q-learning to approach these issues, but those methods can provide high-variance gradient estimates and be slow to train. In this paper, we tackle the problem of learning hard attention for a sequential task using variational inference methods, specifically the recently introduced VIMCO and NVIL. Furthermore, we propose a novel baseline that adapts VIMCO to this setting. We demonstrate our method on a phoneme recognition task in clean and noisy environments and show that our method outperforms REINFORCE, with the difference being greater for a more complicated task.

##### Abstract (translated by Google)
最近，对于诸如对象识别，视觉字幕和语音识别之类的任务的硬注意模型具有显着的兴趣。如果降低计算成本，硬注意力可以提供优于软注意的益处，但是由于它们引入的离散潜在变量，训练硬注意力模型可能是困难的。以前的工作使用REINFORCE和Q-learning来解决这些问题，但这些方法可以提供高方差梯度估计并且训练缓慢。在本文中，我们使用变分推理方法，特别是最近引入的VIMCO和NVIL，解决了对顺序任务学习重点关注的问题。此外，我们提出了一个新的基线，使VIMCO适应这种环境。我们在干净和嘈杂的环境中演示我们的音素识别任务方法，并证明我们的方法优于REINFORCE，对于更复杂的任务，差异更大。

##### URL
[https://arxiv.org/abs/1705.05524](https://arxiv.org/abs/1705.05524)

##### PDF
[https://arxiv.org/pdf/1705.05524](https://arxiv.org/pdf/1705.05524)

