---
layout: post
title: "Scene Text Recognition from Two-Dimensional Perspective"
date: 2018-09-18 02:34:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Speech_Recognition CNN Semantic_Segmentation Prediction Detection Recognition
author: Minghui Liao, Jian Zhang, Zhaoyi Wan, Fengming Xie, Jiajun Liang, Pengyuan Lyu, Cong Yao, Xiang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by speech recognition, recent state-of-the-art algorithms mostly consider scene text recognition as a sequence prediction problem. Though achieving excellent performance, these methods usually neglect an important fact that text in images are actually distributed in two-dimensional space. It is a nature quite different from that of speech, which is essentially a one-dimensional signal. In principle, directly compressing features of text into a one-dimensional form may lose useful information and introduce extra noise. In this paper, we approach scene text recognition from a two-dimensional perspective. A simple yet effective model, called Character Attention Fully Convolutional Network (CA-FCN), is devised for recognizing text of arbitrary shapes. Scene text recognition is realized with a semantic segmentation network, where an attention mechanism for characters is adopted. Combined with a word formation module, CA-FCN can simultaneously recognize the script and predict the position of each character. Experiments demonstrate that the proposed algorithm outperforms previous methods on both regular and irregular text datasets. Moreover, it is proven to be more robust to imprecise localizations in the text detection phase, which are very common in practice.

##### Abstract (translated by Google)
受语音识别的启发，最新的最先进算法主要将场景文本识别视为序列预测问题。虽然实现了优异的性能，但这些方法通常忽略了一个重要的事实，即图像中的文本实际上是在二维空间中分布的。它的性质与语音完全不同，语音本质上是一维信号。原则上，将文本的特征直接压缩成一维形式可能会丢失有用的信息并引入额外的噪声。在本文中，我们从二维视角处理场景文本识别。一种简单而有效的模型，称为字符注意完全卷积网络（CA-FCN），被设计用于识别任意形状的文本。场景文本识别是通过语义分割网络实现的，其中采用了字符的关注机制。结合单词形成模块，CA-FCN可以同时识别脚本并预测每个字符的位置。实验证明，所提出的算法在常规和不规则文本数据集上优于以前的方法。此外，事实证明，在文本检测阶段对不精确的本地化更加健壮，这在实践中非常普遍。

##### URL
[https://arxiv.org/abs/1809.06508](https://arxiv.org/abs/1809.06508)

##### PDF
[https://arxiv.org/pdf/1809.06508](https://arxiv.org/pdf/1809.06508)

