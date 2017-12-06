---
layout: post
title: "Watch What You Just Said: Image Captioning with Text-Conditional Attention"
date: 2016-11-24 04:36:42
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Luowei Zhou, Chenliang Xu, Parker Koch, Jason J. Corso
---

* content
{:toc}

##### Abstract
Attention mechanisms have attracted considerable interest in image captioning due to its powerful performance. However, existing methods use only visual content as attention and whether textual context can improve attention in image captioning remains unsolved. To explore this problem, we propose a novel attention mechanism, called \textit{text-conditional attention}, which allows the caption generator to focus on certain image features given previously generated text. To obtain text-related image features for our attention model, we adopt the guiding Long Short-Term Memory (gLSTM) captioning architecture with CNN fine-tuning. Our proposed method allows joint learning of the image embedding, text embedding, text-conditional attention and language model with one network architecture in an end-to-end manner. We perform extensive experiments on the MS-COCO dataset. The experimental results show that our method outperforms state-of-the-art captioning methods on various quantitative metrics as well as in human evaluation, which supports the use of our text-conditional attention in image captioning.

##### Abstract (translated by Google)
由于其强大的性能，注意机制已经引起了人们对图像字幕的极大兴趣。然而，现有的方法只使用视觉内容作为注意力，文字上下文是否能提高图像字幕的注意力仍然没有解决。为了探索这个问题，我们提出了一种新的注意机制，叫做\ textit {text-conditional attention}，它允许字幕生成器把焦点放在给定的图像特征上。为了获得我们关注模型中与文本相关的图像特征，我们采用了带有CNN微调的指导性长短期记忆（gLSTM）字幕体系结构。我们提出的方法允许以一种网络架构以端到端的方式联合学习图像嵌入，文本嵌入，文本条件注意和语言模型。我们在MS-COCO数据集上进行了大量的实验。实验结果表明，我们的方法在各种定量指标和人体评价方面都优于现有技术的字幕方法，从而支持在图像字幕中使用文本条件注意。

##### URL
[https://arxiv.org/abs/1606.04621](https://arxiv.org/abs/1606.04621)

