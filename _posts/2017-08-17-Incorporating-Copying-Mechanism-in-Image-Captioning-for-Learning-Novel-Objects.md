---
layout: post
title: "Incorporating Copying Mechanism in Image Captioning for Learning Novel Objects"
date: 2017-08-17 13:51:39
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN RNN Recognition
author: Ting Yao, Yingwei Pan, Yehao Li, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning often requires a large set of training image-sentence pairs. In practice, however, acquiring sufficient training pairs is always expensive, making the recent captioning models limited in their ability to describe objects outside of training corpora (i.e., novel objects). In this paper, we present Long Short-Term Memory with Copying Mechanism (LSTM-C) --- a new architecture that incorporates copying into the Convolutional Neural Networks (CNN) plus Recurrent Neural Networks (RNN) image captioning framework, for describing novel objects in captions. Specifically, freely available object recognition datasets are leveraged to develop classifiers for novel objects. Our LSTM-C then nicely integrates the standard word-by-word sentence generation by a decoder RNN with copying mechanism which may instead select words from novel objects at proper places in the output sentence. Extensive experiments are conducted on both MSCOCO image captioning and ImageNet datasets, demonstrating the ability of our proposed LSTM-C architecture to describe novel objects. Furthermore, superior results are reported when compared to state-of-the-art deep models.

##### Abstract (translated by Google)
图像字幕通常需要大量的训练图像 - 句子对。然而，在实践中，获取足够的训练对总是昂贵的，使得最近的字幕模型限制了在训练语料库（即新颖的对象）之外描述对象的能力。在本文中，我们提出了具有复制机制的长期短期记忆（LSTM-C） - 一种将复制结合到卷积神经网络（CNN）和递归神经网络（RNN）图像字幕框架的新架构，用于描述小说标题中的对象。具体而言，免费提供的对象识别数据集可用于开发新型对象的分类器。然后，我们的LSTM-C很好地将由解码器RNN生成的标准逐词生成的句子与复制机制完美地结合在一起，而复制机制可以在输出句子中适当的位置选择来自新对象的单词。对MSCOCO图像字幕和ImageNet数据集进行了大量实验，证明了我们提出的LSTM-C体系结构描述新颖物体的能力。此外，与最先进的深度模型相比，报告了优异的结果。

##### URL
[https://arxiv.org/abs/1708.05271](https://arxiv.org/abs/1708.05271)

