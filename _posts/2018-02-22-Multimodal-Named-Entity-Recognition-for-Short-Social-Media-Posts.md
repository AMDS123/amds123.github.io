---
layout: post
title: "Multimodal Named Entity Recognition for Short Social Media Posts"
date: 2018-02-22 00:54:47
categories: arXiv_CL
tags: arXiv_CL Image_Caption Attention Caption RNN Recognition
author: Seungwhan Moon, Leonardo Neves, Vitor Carvalho
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new task called Multimodal Named Entity Recognition (MNER) for noisy user-generated data such as tweets or Snapchat captions, which comprise short text with accompanying images. These social media posts often come in inconsistent or incomplete syntax and lexical notations with very limited surrounding textual contexts, bringing significant challenges for NER. To this end, we create a new dataset for MNER called SnapCaptions (Snapchat image-caption pairs submitted to public and crowd-sourced stories with fully annotated named entities). We then build upon the state-of-the-art Bi-LSTM word/character based NER models with 1) a deep image network which incorporates relevant visual context to augment textual information, and 2) a generic modality-attention module which learns to attenuate irrelevant modalities while amplifying the most informative ones to extract contexts from, adaptive to each sample and token. The proposed MNER model with modality attention significantly outperforms the state-of-the-art text-only NER models by successfully leveraging provided visual contexts, opening up potential applications of MNER on myriads of social media platforms.

##### Abstract (translated by Google)
我们针对嘈杂的用户生成数据（如tweets或Snapchat标题）引入了一项名为Multimodal Named Entity Recognition（MNER）的新任务，其中包含伴随图像的短文本。这些社交媒体帖子经常出现语法和词汇表达不一致或不完整的情况，而且周围的文本背景非常有限，这给NER带来了重大挑战。为此，我们为MNER创建了一个名为SnapCaptions的新数据集（Snapchat图像标题对提交给公开和众包的故事，并带有完全注释的命名实体）。然后，我们基于最先进的Bi-LSTM基于字/字符的NER模型，其中包括：1）一个深度图像网络，包含相关的视觉环境以增强文本信息; 2）一个通用的模态注意模块，衰减不相关的模态，同时放大最有信息的模式以提取上下文，自适应于每个样本和令牌。所提出的MNER模型具有模态注意力，通过成功利用所提供的视觉背景，显着优于最先进的纯文本NER模型，从而为无数社交媒体平台开启MNER的潜在应用。

##### URL
[http://arxiv.org/abs/1802.07862](http://arxiv.org/abs/1802.07862)

##### PDF
[http://arxiv.org/pdf/1802.07862](http://arxiv.org/pdf/1802.07862)

