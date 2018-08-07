---
layout: post
title: "Multimodal Named Entity Recognition for Short Social Media Posts"
date: 2018-02-22 00:54:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption RNN Recognition
author: Seungwhan Moon, Leonardo Neves, Vitor Carvalho
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new task called Multimodal Named Entity Recognition (MNER) for noisy user-generated data such as tweets or Snapchat captions, which comprise short text with accompanying images. These social media posts often come in inconsistent or incomplete syntax and lexical notations with very limited surrounding textual contexts, bringing significant challenges for NER. To this end, we create a new dataset for MNER called SnapCaptions (Snapchat image-caption pairs submitted to public and crowd-sourced stories with fully annotated named entities). We then build upon the state-of-the-art Bi-LSTM word/character based NER models with 1) a deep image network which incorporates relevant visual context to augment textual information, and 2) a generic modality-attention module which learns to attenuate irrelevant modalities while amplifying the most informative ones to extract contexts from, adaptive to each sample and token. The proposed MNER model with modality attention significantly outperforms the state-of-the-art text-only NER models by successfully leveraging provided visual contexts, opening up potential applications of MNER on myriads of social media platforms.

##### Abstract (translated by Google)
我们引入了一项名为Multimodal Named Entity Recognition（MNER）的新任务，用于嘈杂的用户生成数据，如推文或Snapchat标题，其中包含带有附带图像的短文本。这些社交媒体帖子经常出现不一致或不完整的语法和词汇符号，周围的文本背景非常有限，给NER带来了重大挑战。为此，我们为MNER创建了一个名为SnapCaptions的新数据集（Snapchat图像标题对提交给公共和众包故事，并带有完全注释的命名实体）。然后，我们建立在最先进的Bi-LSTM基于字/字符的NER模型的基础上，1）深度图像网络，其结合相关的视觉上下文以增强文本信息，以及2）通用模态注意模块，其学习到减弱不相关的模态，同时放大信息量最大的模式以提取上下文，适应每个样本和令牌。通过成功利用提供的视觉上下文，MNER在无数社交媒体平台上的潜在应用，提出的具有模态注意力的MNER模型明显优于最先进的纯文本NER模型。

##### URL
[https://arxiv.org/abs/1802.07862](https://arxiv.org/abs/1802.07862)

##### PDF
[https://arxiv.org/pdf/1802.07862](https://arxiv.org/pdf/1802.07862)

