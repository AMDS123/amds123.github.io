---
layout: post
title: 'Unifying Visual-Semantic Embeddings with Multimodal Neural Language Models'
date: 2017-12-06 09:15:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Caption CNN RNN Detection
author: Ryan Kiros, Ruslan Salakhutdinov, Richard S. Zemel
---

* content
{:toc}

##### Abstract
Inspired by recent advances in multimodal learning and machine translation, we introduce an encoder-decoder pipeline that learns (a): a multimodal joint embedding space with images and text and (b): a novel language model for decoding distributed representations from our space. Our pipeline effectively unifies joint image-text embedding models with multimodal neural language models. We introduce the structure-content neural language model that disentangles the structure of a sentence to its content, conditioned on representations produced by the encoder. The encoder allows one to rank images and sentences while the decoder can generate novel descriptions from scratch. Using LSTM to encode sentences, we match the state-of-the-art performance on Flickr8K and Flickr30K without using object detections. We also set new best results when using the 19-layer Oxford convolutional network. Furthermore we show that with linear encoders, the learned embedding space captures multimodal regularities in terms of vector space arithmetic e.g. *image of a blue car* - "blue" + "red" is near images of red cars. Sample captions generated for 800 images are made available for comparison.

##### Abstract (translated by Google)
受到多模式学习和机器翻译方面的最新进展的启发，我们引入了一个编码器 - 解码器流水线，它学习（a）：图像和文本的多模式联合嵌入空间和（b）：从我们的空间解码分布式表示的新型语言模型。我们的流程有效地将联合图像文本嵌入模型与多模式神经语言模型相结合。我们引入结构 - 内容神经语言模型，将句子的结构解开为其内容，以编码器产生的表示为条件。编码器允许人们排列图像和句子，而解码器可以从头开始产生新的描述。使用LSTM对句子进行编码，我们无需使用对象检测就可以匹配Flickr8K和Flickr30K上的最新性能。当使用19层牛津卷积网络时，我们也创造了新的最佳结果。此外，我们表明，利用线性编码器，学习的嵌入空间以矢量空间运算的形式捕获多模态规则。 *蓝色车的图像*  - “蓝色”+“红色”是红色车的图像。为800幅图像生成的样本标题可用于比较。

##### URL
[https://arxiv.org/abs/1411.2539](https://arxiv.org/abs/1411.2539)

