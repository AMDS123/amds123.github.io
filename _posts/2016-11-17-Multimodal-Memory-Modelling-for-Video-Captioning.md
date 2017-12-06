---
layout: post
title: "Multimodal Memory Modelling for Video Captioning"
date: 2016-11-17 07:24:03
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption CNN RNN Deep_Learning
author: Junbo Wang, Wei Wang, Yan Huang, Liang Wang, Tieniu Tan
---

* content
{:toc}

##### Abstract
Video captioning which automatically translates video clips into natural language sentences is a very important task in computer vision. By virtue of recent deep learning technologies, e.g., convolutional neural networks (CNNs) and recurrent neural networks (RNNs), video captioning has made great progress. However, learning an effective mapping from visual sequence space to language space is still a challenging problem. In this paper, we propose a Multimodal Memory Model (M3) to describe videos, which builds a visual and textual shared memory to model the long-term visual-textual dependency and further guide global visual attention on described targets. Specifically, the proposed M3 attaches an external memory to store and retrieve both visual and textual contents by interacting with video and sentence with multiple read and write operations. First, text representation in the Long Short-Term Memory (LSTM) based text decoder is written into the memory, and the memory contents will be read out to guide an attention to select related visual targets. Then, the selected visual information is written into the memory, which will be further read out to the text decoder. To evaluate the proposed model, we perform experiments on two publicly benchmark datasets: MSVD and MSR-VTT. The experimental results demonstrate that our method outperforms the state-of-theart methods in terms of BLEU and METEOR.

##### Abstract (translated by Google)
将视频片段自动翻译成自然语言句子的视频字幕是计算机视觉中非常重要的任务。借助于近来的深度学习技术，例如卷积神经网络（CNN）和递归神经网络（RNN），视频字幕已经取得了很大进展。但是，从视觉序列空间到语言空间学习有效的映射仍然是一个具有挑战性的问题。在本文中，我们提出了一个多模态记忆模型（M3）来描述视频，它建立了一个视觉和文本的共享记忆模型的长期视觉文本的依赖，并进一步引导全球视觉注意力描述的目标。具体而言，所提出的M3附加外部存储器以通过与多个读取和写入操作与视频和句子交互来存储和检索视觉和文本内容。首先，基于长短期记忆（LSTM）的文本解码器中的文本表示被写入存储器，并且读出存储器内容以引导注意力来选择相关的可视目标。然后，所选择的视觉信息被写入到存储器中，该信息将被进一步读出到文本解码器。为了评估所提出的模型，我们在两个公开基准数据集上进行实验：MSVD和MSR-VTT。实验结果表明，我们的方法在BLEU和METEOR方面优于现有的方法。

##### URL
[https://arxiv.org/abs/1611.05592](https://arxiv.org/abs/1611.05592)

