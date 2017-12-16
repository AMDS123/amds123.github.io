---
layout: post
title: "Transformation-Grounded Image Generation Network for Novel 3D View Synthesis"
date: 2017-03-08 17:16:15
categories: arXiv_CV
tags: arXiv_CV Adversarial Quantitative
author: Eunbyung Park, Jimei Yang, Ersin Yumer, Duygu Ceylan, Alexander C. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
We present a transformation-grounded image generation network for novel 3D view synthesis from a single image. Instead of taking a 'blank slate' approach, we first explicitly infer the parts of the geometry visible both in the input and novel views and then re-cast the remaining synthesis problem as image completion. Specifically, we both predict a flow to move the pixels from the input to the novel view along with a novel visibility map that helps deal with occulsion/disocculsion. Next, conditioned on those intermediate results, we hallucinate (infer) parts of the object invisible in the input image. In addition to the new network structure, training with a combination of adversarial and perceptual loss results in a reduction in common artifacts of novel view synthesis such as distortions and holes, while successfully generating high frequency details and preserving visual aspects of the input image. We evaluate our approach on a wide range of synthetic and real examples. Both qualitative and quantitative results show our method achieves significantly better results compared to existing methods.

##### Abstract (translated by Google)
我们提出了一个转换为基础的图像生成网络从一个单一的图像新颖的三维视图合成。我们首先明确地推断在输入视图和新视图中都可见的几何部分，然后将剩余的合成问题重新转换为图像完成，而不是采用“空白板岩”方法。具体而言，我们都预测了一个流程，将像素从输入移动到新视图以及一个新的可见性图，帮助处理障碍/ disocculsion。接下来，以这些中间结果为条件，我们幻觉（推断）输入图像中不可见的部分对象。除了新的网络结构之外，对立和感知损失相结合的训练还可以减少失真和空洞等新视点合成的常见伪影，同时成功生成高频细节并保留输入图像的视觉方面。我们通过广泛的综合和实例来评估我们的方法。定性和定量结果显示，与现有方法相比，我们的方法取得了显着更好的结果。

##### URL
[https://arxiv.org/abs/1703.02921](https://arxiv.org/abs/1703.02921)

##### PDF
[https://arxiv.org/pdf/1703.02921](https://arxiv.org/pdf/1703.02921)

