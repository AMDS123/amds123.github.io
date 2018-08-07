---
layout: post
title: "Phrase-based Image Captioning with Hierarchical LSTM Model"
date: 2017-11-11 10:48:59
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Inference RNN
author: Ying Hua Tan, Chee Seng Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic generation of caption to describe the content of an image has been gaining a lot of research interests recently, where most of the existing works treat the image caption as pure sequential data. Natural language, however possess a temporal hierarchy structure, with complex dependencies between each subsequence. In this paper, we propose a phrase-based hierarchical Long Short-Term Memory (phi-LSTM) model to generate image description. In contrast to the conventional solutions that generate caption in a pure sequential manner, our proposed model decodes image caption from phrase to sentence. It consists of a phrase decoder at the bottom hierarchy to decode noun phrases of variable length, and an abbreviated sentence decoder at the upper hierarchy to decode an abbreviated form of the image description. A complete image caption is formed by combining the generated phrases with sentence during the inference stage. Empirically, our proposed model shows a better or competitive result on the Flickr8k, Flickr30k and MS-COCO datasets in comparison to the state-of-the art models. We also show that our proposed model is able to generate more novel captions (not seen in the training data) which are richer in word contents in all these three datasets.

##### Abstract (translated by Google)
用于描述图像内容的字幕的自动生成最近获得了许多研究兴趣，其中大多数现有作品将图像标题视为纯序列数据。然而，自然语言具有时间层次结构，每个子序列之间具有复杂的依赖性。在本文中，我们提出了一个基于短语的分层长短期记忆（phi-LSTM）模型来生成图像描述。与以纯顺序方式生成标题的传统解决方案相比，我们提出的模型将图像标题从短语解释为句子。它包括底部层次的短语解码器，用于解码可变长度的名词短语，以及在上层次的缩写句子解码器，用于解码图像描述的缩写形式。通过在推理阶段期间将所生成的短语与句子组合来形成完整的图像标题。根据经验，与现有技术模型相比，我们提出的模型在Flickr8k，Flickr30k和MS-COCO数据集上显示出更好或更具竞争力的结果。我们还表明，我们提出的模型能够生成更多新颖的标题（在训练数据中没有看到），这些标题在所有这三个数据集中都有更丰富的单词内容。

##### URL
[https://arxiv.org/abs/1711.05557](https://arxiv.org/abs/1711.05557)

##### PDF
[https://arxiv.org/pdf/1711.05557](https://arxiv.org/pdf/1711.05557)

