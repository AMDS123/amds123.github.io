---
layout: post
title: "Understanding Visual Ads by Aligning Symbols and Objects using Co-Attention"
date: 2018-07-04 04:50:09
categories: arXiv_CV
tags: arXiv_CV Attention Embedding Inference
author: Karuna Ahuja, Karan Sikka, Anirban Roy, Ajay Divakaran
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of understanding visual ads where given an ad image, our goal is to rank appropriate human generated statements describing the purpose of the ad. This problem is generally addressed by jointly embedding images and candidate statements to establish correspondence. Decoding a visual ad requires inference of both semantic and symbolic nuances referenced in an image and prior methods may fail to capture such associations especially with weakly annotated symbols. In order to create better embeddings, we leverage an attention mechanism to associate image proposals with symbols and thus effectively aggregate information from aligned multimodal representations. We propose a multihop co-attention mechanism that iteratively refines the attention map to ensure accurate attention estimation. Our attention based embedding model is learned end-to-end guided by a max-margin loss function. We show that our model outperforms other baselines on the benchmark Ad dataset and also show qualitative results to highlight the advantages of using multihop co-attention.

##### Abstract (translated by Google)
我们解决了在给定广告图片的情况下理解视觉广告的问题，我们的目标是对描述广告目的的适当的人工生成的陈述进行排名。通常通过联合嵌入图像和候选语句来建立对应来解决该问题。解码视觉广告需要推断图像中引用的语义和符号细微差别，并且先前的方法可能无法捕获这种关联，尤其是弱注释符号。为了创建更好的嵌入，我们利用注意机制将图像提议与符号相关联，从而有效地聚合来自对齐的多模式表示的信息。我们提出了一种多跳共同关注机制，它迭代地改进注意力图以确保准确的注意力估计。我们基于注意力的嵌入模型是通过最大边际损失函数以端到端的方式学习的。我们表明，我们的模型在基准广告数据集上优于其他基线，并且还显示定性结果，以突出使用多跳共同关注的优势。

##### URL
[http://arxiv.org/abs/1807.01448](http://arxiv.org/abs/1807.01448)

##### PDF
[http://arxiv.org/pdf/1807.01448](http://arxiv.org/pdf/1807.01448)

