---
layout: post
title: 'Phrase-based Image Captioning with Hierarchical LSTM Model'
date: 2017-11-11 10:48:59
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Ying Hua Tan, Chee Seng Chan
---

* content
{:toc}

##### Abstract
Automatic generation of caption to describe the content of an image has been gaining a lot of research interests recently, where most of the existing works treat the image caption as pure sequential data. Natural language, however possess a temporal hierarchy structure, with complex dependencies between each subsequence. In this paper, we propose a phrase-based hierarchical Long Short-Term Memory (phi-LSTM) model to generate image description. In contrast to the conventional solutions that generate caption in a pure sequential manner, our proposed model decodes image caption from phrase to sentence. It consists of a phrase decoder at the bottom hierarchy to decode noun phrases of variable length, and an abbreviated sentence decoder at the upper hierarchy to decode an abbreviated form of the image description. A complete image caption is formed by combining the generated phrases with sentence during the inference stage. Empirically, our proposed model shows a better or competitive result on the Flickr8k, Flickr30k and MS-COCO datasets in comparison to the state-of-the art models. We also show that our proposed model is able to generate more novel captions (not seen in the training data) which are richer in word contents in all these three datasets.

##### Abstract (translated by Google)
自动生成字幕来描述图像的内容最近已经获得了很多研究兴趣，大多数现有的作品将图像标题视为纯序列数据。然而，自然语言具有时间层次结构，每个子序列之间具有复杂的相关性。在本文中，我们提出了一种基于短语的分层长短期记忆（phi-LSTM）模型来生成图像描述。与以纯序贯方式生成字幕的传统解决方案相反，我们提出的模型将图像字幕从短语解码为句子。它由底层的短语解码器组成，以解码变长的名词短语和上层的缩写句解码器，以解码缩略形式的图像描述。在推理阶段将生成的短语与句子结合起来形成完整的图像标题。从经验上讲，我们提出的模型与Flickr8k，Flickr30k和MS-COCO数据集相比，在最先进的模型上显示出更好或更具竞争力的结果。我们还表明，我们提出的模型能够产生更多新颖的字幕（在训练数据中看不到），在这三个数据集中的词内容更丰富。

##### URL
[https://arxiv.org/abs/1711.05557](https://arxiv.org/abs/1711.05557)

