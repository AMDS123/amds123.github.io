---
layout: post
title: "Learning Semantic Concepts and Order for Image and Sentence Matching"
date: 2017-12-06 04:36:40
categories: arXiv_CV
tags: arXiv_CV Image_Caption GAN RNN
author: Yan Huang, Qi Wu, Liang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Image and sentence matching has made great progress recently, but it remains challenging due to the large visual-semantic discrepancy. This mainly arises from that the representation of pixel-level image usually lacks of high-level semantic information as in its matched sentence. In this work, we propose a semantic-enhanced image and sentence matching model, which can improve the image representation by learning semantic concepts and then organizing them in a correct semantic order. Given an image, we first use a multi-regional multi-label CNN to predict its semantic concepts, including objects, properties, actions, etc. Then, considering that different orders of semantic concepts lead to diverse semantic meanings, we use a context-gated sentence generation scheme for semantic order learning. It simultaneously uses the image global context containing concept relations as reference and the groundtruth semantic order in the matched sentence as supervision. After obtaining the improved image representation, we learn the sentence representation with a conventional LSTM, and then jointly perform image and sentence matching and sentence generation for model learning. Extensive experiments demonstrate the effectiveness of our learned semantic concepts and order, by achieving the state-of-the-art results on two public benchmark datasets.

##### Abstract (translated by Google)
图像和句子匹配近来取得了很大的进展，但由于视觉语义差异较大，图像和句子匹配仍然具有挑战性。这主要是由于像素级图像的表示通常缺少高级语义信息，如其匹配的句子。在这项工作中，我们提出了一个语义增强的图像和句子匹配模型，它可以通过学习语义概念，然后以正确的语义顺序组织它们来改善图像表示。给定一幅图像，我们首先使用一个多区域多标签CNN来预测它的语义概念，包括对象，属性，动作等。然后，考虑到语义概念的不同顺序导致不同的语义含义，门控句子生成方案的语义顺序学习。同时使用包含概念关系的图像全局上下文作为参照，将匹配句子中的语义语序作为监督。获得改进的图像表示后，我们学习与传统的LSTM的句子表示，然后联合进行图像和句子匹配和句子生成模型学习。通过在两个公共基准数据集上实现最新的结果，广泛的实验证明了我们学习的语义概念和顺序的有效性。

##### URL
[http://arxiv.org/abs/1712.02036](http://arxiv.org/abs/1712.02036)

##### PDF
[http://arxiv.org/pdf/1712.02036](http://arxiv.org/pdf/1712.02036)

