---
layout: post
title: "Online Adaptation of Convolutional Neural Networks for Video Object Segmentation"
date: 2017-08-01 15:18:18
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Paul Voigtlaender, Bastian Leibe
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the task of semi-supervised video object segmentation, i.e. segmenting the pixels belonging to an object in the video using the ground truth pixel mask for the first frame. We build on the recently introduced one-shot video object segmentation (OSVOS) approach which uses a pretrained network and fine-tunes it on the first frame. While achieving impressive performance, at test time OSVOS uses the fine-tuned network in unchanged form and is not able to adapt to large changes in object appearance. To overcome this limitation, we propose Online Adaptive Video Object Segmentation (OnAVOS) which updates the network online using training examples selected based on the confidence of the network and the spatial configuration. Additionally, we add a pretraining step based on objectness, which is learned on PASCAL. Our experiments show that both extensions are highly effective and improve the state of the art on DAVIS to an intersection-over-union score of 85.7%.

##### Abstract (translated by Google)
我们处理半监督视频对象分割的任务，即使用第一帧的地面真实像素掩模分割属于视频中的对象的像素。我们建立在最近引入的一次性视频对象分割（OSVOS）方法上，该方法使用预训练网络，并在第一帧对其进行微调。在测试时间，OSVOS以不变的形式使用精细调整的网络，并且无法适应对象外观的巨大变化，同时取得了令人印象深刻的性能。为了克服这个限制，我们提出了在线自适应视频对象分割（OnAVOS），它使用基于网络的可信度和空间配置选择的训练样例在线更新网络。另外，我们在PASCAL上增加一个基于对象的预训练步骤。我们的实验表明，这两个扩展都是非常有效的，并将DAVIS的最新技术水平提高到了85.7％的交集。

##### URL
[https://arxiv.org/abs/1706.09364](https://arxiv.org/abs/1706.09364)

##### PDF
[https://arxiv.org/pdf/1706.09364](https://arxiv.org/pdf/1706.09364)

