---
layout: post
title: "Neural Networks for Text Correction and Completion in Keyboard Decoding"
date: 2017-09-19 13:52:28
categories: arXiv_CL
tags: arXiv_CL Attention CNN Inference RNN Deep_Learning Language_Model Prediction
author: Shaona Ghosh, Per Ola Kristensson
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the ubiquity of mobile and wearable text messaging applications, the problem of keyboard text decoding is not tackled sufficiently in the light of the enormous success of the deep learning Recurrent Neural Network (RNN) and Convolutional Neural Networks (CNN) for natural language understanding. In particular, considering that the keyboard decoders should operate on devices with memory and processor resource constraints, makes it challenging to deploy industrial scale deep neural network (DNN) models. This paper proposes a sequence-to-sequence neural attention network system for automatic text correction and completion. Given an erroneous sequence, our model encodes character level hidden representations and then decodes the revised sequence thus enabling auto-correction and completion. We achieve this by a combination of character level CNN and gated recurrent unit (GRU) encoder along with and a word level gated recurrent unit (GRU) attention decoder. Unlike traditional language models that learn from billions of words, our corpus size is only 12 million words; an order of magnitude smaller. The memory footprint of our learnt model for inference and prediction is also an order of magnitude smaller than the conventional language model based text decoders. We report baseline performance for neural keyboard decoders in such limited domain. Our models achieve a word level accuracy of $90\%$ and a character error rate CER of $2.4\%$ over the Twitter typo dataset. We present a novel dataset of noisy to corrected mappings by inducing the noise distribution from the Twitter data over the OpenSubtitles 2009 dataset; on which our model predicts with a word level accuracy of $98\%$ and sequence accuracy of $68.9\%$. In our user study, our model achieved an average CER of $2.6\%$ with the state-of-the-art non-neural touch-screen keyboard decoder at CER of $1.6\%$.

##### Abstract (translated by Google)
尽管无处不在的移动和可穿戴式文本消息应用，但是在深度学习递归神经网络（RNN）和卷积神经网络（CNN）对于自然语言理解的巨大成功的情况下，键盘文本解码的问题还没有得到充分的解决。特别是，考虑到键盘解码器应该在具有存储器和处理器资源限制的设备上操作，使得部署工业规模的深度神经网络（DNN）模型具有挑战性。本文提出了一种自动文本修正和完成的序列到序列神经关注网络系统。给定一个错误的序列，我们的模型编码字符级隐藏表示，然后解码修改后的序列，从而启用自动更正和完成。我们通过字符级CNN和门控回归单元（GRU）编码器以及字级门控回归单元（GRU）注意解码器来实现这一点。与从数十亿字中学习的传统语言模型不同，我们的语料库大小只有1200万字;一个数量级更小。我们学习的推理和预测模型的内存占用量也比传统的基于文本解码器的语言模型小了一个数量级。我们在这个有限的领域报告神经键盘解码器的基线性能。我们的模型在Twitter类型数据集上实现了$ 90 \％$的字级准确度和$ 2.4 \％$的字符错误率CER。我们通过在OpenSubtitles 2009数据集中引入来自Twitter数据的噪声分布来呈现噪声到校正映射的新颖数据集;我们的模型预测的字级精度为$ 98 \％$，序列精度为$ 68.9 \％$。在我们的用户研究中，我们的模型使用最先进的非神经触摸屏键盘解码器，CER达到$ 1.6 \％$，达到了$ 2.6％的平均CER。

##### URL
[https://arxiv.org/abs/1709.06429](https://arxiv.org/abs/1709.06429)

##### PDF
[https://arxiv.org/pdf/1709.06429](https://arxiv.org/pdf/1709.06429)

