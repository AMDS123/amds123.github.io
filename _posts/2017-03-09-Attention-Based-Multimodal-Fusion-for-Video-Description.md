---
layout: post
title: "Attention-Based Multimodal Fusion for Video Description"
date: 2017-03-09 22:57:10
categories: arXiv_SD
tags: arXiv_SD Attention RNN
author: Chiori Hori, Takaaki Hori, Teng-Yok Lee, Kazuhiro Sumi, John R. Hershey, Tim K. Marks
mathjax: true
---

* content
{:toc}

##### Abstract
Currently successful methods for video description are based on encoder-decoder sentence generation using recur-rent neural networks (RNNs). Recent work has shown the advantage of integrating temporal and/or spatial attention mechanisms into these models, in which the decoder net-work predicts each word in the description by selectively giving more weight to encoded features from specific time frames (temporal attention) or to features from specific spatial regions (spatial attention). In this paper, we propose to expand the attention model to selectively attend not just to specific times or spatial regions, but to specific modalities of input such as image features, motion features, and audio features. Our new modality-dependent attention mechanism, which we call multimodal attention, provides a natural way to fuse multimodal information for video description. We evaluate our method on the Youtube2Text dataset, achieving results that are competitive with current state of the art. More importantly, we demonstrate that our model incorporating multimodal attention as well as temporal attention significantly outperforms the model that uses temporal attention alone.

##### Abstract (translated by Google)
目前，视频描述的成功方法是基于使用递归神经网络（RNN）的编码器 - 解码器句子生成。最近的工作已经显示了将时间和/或空间关注机制集成到这些模型中的优点，其中解码器网络通过选择性地给予来自特定时间帧（时间关注）的编码特征的更多权重或者来自特定空间区域的特征（空间关注）。在本文中，我们建议扩大注意模型，选择性地参加不只是特定的时间或空间区域，而是特定的输入模式，如图像特征，运动特征和音频特征。我们称之为多模态注意的新型模态依赖注意机制提供了融合多模态信息进行视频描述的自然方式。我们在Youtube2Text数据集上评估我们的方法，取得了与当前技术水平相竞争的结果。更重要的是，我们证明，我们的模型结合多模态注意力和时间注意力明显优于单独使用时间注意力的模型。

##### URL
[https://arxiv.org/abs/1701.03126](https://arxiv.org/abs/1701.03126)

##### PDF
[https://arxiv.org/pdf/1701.03126](https://arxiv.org/pdf/1701.03126)

