---
layout: post
title: "PiCANet: Learning Pixel-wise Contextual Attention in ConvNets and Its Application in Saliency Detection"
date: 2017-08-21 22:12:45
categories: arXiv_CV
tags: arXiv_CV Salient Attention Detection
author: Nian Liu, Junwei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Context plays an important role in many computer vision tasks. Previous models usually construct contextual information from the whole context region. However, not all context locations are helpful and some of them may be detrimental to the final task. To solve this problem, we propose a novel pixel-wise contextual attention network, i.e., the PiCANet, to learn to selectively attend to informative context locations for each pixel. Specifically, it can generate an attention map over the context region for each pixel, where each attention weight corresponds to the contextual relevance of each context location w.r.t. the specified pixel location. Thus, an attended contextual feature can be constructed by using the attention map to aggregate the contextual features. We formulate PiCANet in a global form and a local form to attend to global contexts and local contexts, respectively. Our designs for the two forms are both fully differentiable. Thus they can be embedded into any CNN architectures for various computer vision tasks in an end-to-end manner. We take saliency detection as an example application to demonstrate the effectiveness of the proposed PiCANets. Specifically, we embed global and local PiCANets into an encoder-decoder Convnet hierarchically. Thorough analyses indicate that the global PiCANet helps to construct global contrast while the local PiCANets help to enhance the feature maps to be more homogenous, thus making saliency detection results more accurate and uniform. As a result, our proposed saliency model achieves state-of-the-art results on 4 benchmark datasets.

##### Abstract (translated by Google)
背景在许多计算机视觉任务中起着重要的作用。以前的模型通常从整个上下文区域构建上下文信息。然而，并非所有的上下文位置都是有用的，其中一些位置对于最终的任务可能是不利的。为了解决这个问题，我们提出了一种新颖的像素式上下文关注网络，即PiCANet，以学习选择性地关注每个像素的信息上下文位置。具体来说，它可以在每个像素的上下文区域上生成关注映射，其中每个关注权重对应于每个上下文位置w.r.t的上下文相关性。指定的像素位置。因此，可以通过使用关注映射来聚合上下文特征来构建出席的上下文特征。我们分别以全球形式和当地形式制定PiCANet，以分别关注全球背景和当地背景。我们的两种形式的设计都是完全可以区分的。因此，它们可以以端到端的方式嵌入到各种计算机视觉任务的CNN体​​系结构中。我们以显着性检测作为示例应用程序来演示提议的PiCANets的有效性。具体而言，我们将全局和本地PiCANets分层嵌入到编码器 - 解码器Convnet中。全面的分析表明，全球PiCANet有助于构建全局对比度，而本地PiCANets有助于增强特征映射的均匀性，从而使显着性检测结果更加准确和统一。因此，我们提出的显着性模型在4个基准数据集上达到了最新的结果。

##### URL
[https://arxiv.org/abs/1708.06433](https://arxiv.org/abs/1708.06433)

##### PDF
[https://arxiv.org/pdf/1708.06433](https://arxiv.org/pdf/1708.06433)

