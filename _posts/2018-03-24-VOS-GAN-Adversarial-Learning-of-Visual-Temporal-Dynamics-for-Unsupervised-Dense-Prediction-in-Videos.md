---
layout: post
title: "VOS-GAN: Adversarial Learning of Visual-Temporal Dynamics for Unsupervised Dense Prediction in Videos"
date: 2018-03-24 11:17:41
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Action_Recognition RNN Prediction Recognition
author: C. Spampinato, S. Palazzo, P. D'Oro, F. Murabito, D. Giordano, M. Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Recent GAN-based video generation approaches model videos as the combination of a time-independent scene component and a time-varying motion component, thus factorizing the generation problem into generating background and foreground separately. One of the main limitations of current approaches is that both factors are learned by mapping one source latent space to videos, which complicates the generation task as a single data point must be informative of both background and foreground content. In this paper we propose a GAN framework for video generation that, instead, employs two latent spaces in order to structure the generative process in a more natural way: 1) a latent space to generate the static visual content of a scene (background), which remains the same for the whole video, and 2) a latent space where motion is encoded as a trajectory between sampled points and whose dynamics are modeled through an RNN encoder (jointly trained with the generator and the discriminator) and then mapped by the generator to visual objects' motion. Additionally, we extend current video discrimination approaches by incorporating in the learning procedure motion estimation and, leveraging the peculiarity of the generation process, unsupervised pixel-wise dense predictions. Extensive performance evaluation showed that our approach is able to a) synthesize more realistic videos than state-of-the-art methods, b) learn effectively both local and global video dynamics, as demonstrated by the results achieved on a video action recognition task over the UCF-101 dataset, and c) accurately perform unsupervised video object segmentation on standard video benchmarks, such as DAVIS, SegTrack and F4K-Fish.

##### Abstract (translated by Google)
最近的基于GAN的视频生成方法将视频建模为时间独立的场景分量和时变运动分量的组合，从而将生成问题分解为分别生成背景和前景。当前方法的主要限制之一是，通过将一个源潜在空间映射到视频来学习这两个因素，这使得生成任务复杂化，因为单个数据点必须提供背景和前景内容的信息。在本文中，我们提出了一个用于视频生成的GAN框架，相反，它采用两个潜在空间，以更自然的方式构建生成过程：1）生成场景（背景）的静态视觉内容的潜在空间，对于整个视频保持不变，以及2）将运动编码为采样点之间的轨迹的潜在空间，并且其动态特性通过RNN编码器（与发生器和鉴别器联合训练）建模，然后由发生器映射视觉对象的运动。另外，我们通过在学习过程中引入运动估计并利用生成过程的独特性来扩展当前视频歧视方法，无监督像素密集预测。广泛的性能评估表明，我们的方法能够：a）综合比现有技术方法更逼真的视频，b）有效地学习本地和全球视频动态，如通过视频动作识别任务UCF-101数据集，以及c）在标准视频基准（如DAVIS，SegTrack和F4K-Fish）上精确执行无监督视频对象分割。

##### URL
[https://arxiv.org/abs/1803.09092](https://arxiv.org/abs/1803.09092)

##### PDF
[https://arxiv.org/pdf/1803.09092](https://arxiv.org/pdf/1803.09092)

