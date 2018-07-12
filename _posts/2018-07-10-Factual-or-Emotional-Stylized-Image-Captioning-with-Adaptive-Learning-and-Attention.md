---
layout: post
title: "'Factual' or 'Emotional': Stylized Image Captioning with Adaptive Learning and Attention"
date: 2018-07-10 21:33:22
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge Attention Caption RNN
author: Tianlang Chen, Zhongping Zhang, Quanzeng You, Chen Fang, Zhaowen Wang, Hailin Jin, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Generating stylized captions for an image is an emerging topic in image captioning. Given an image as input, it requires the system to generate a caption that has a specific style (e.g., humorous, romantic, positive, and negative) while describing the image content semantically accurately. In this paper, we propose a novel stylized image captioning model that effectively takes both requirements into consideration. To this end, we first devise a new variant of LSTM, named style-factual LSTM, as the building block of our model. It uses two groups of matrices to capture the factual and stylized knowledge, respectively, and automatically learns the word-level weights of the two groups based on previous context. In addition, when we train the model to capture stylized elements, we propose an adaptive learning approach based on a reference factual model, it provides factual knowledge to the model as the model learns from stylized caption labels, and can adaptively compute how much information to supply at each time step. We evaluate our model on two stylized image captioning datasets, which contain humorous/romantic captions and positive/negative captions, respectively. Experiments shows that our proposed model outperforms the state-of-the-art approaches, without using extra ground truth supervision.

##### Abstract (translated by Google)
为图像生成风格化标题是图像标题中的新兴主题。给定图像作为输入，它要求系统生成具有特定样式（例如，幽默，浪漫，积极和消极）的标题，同时在语义上准确地描述图像内容。在本文中，我们提出了一种新颖的程式化图像字幕模型，它有效地考虑了这两个要求。为此，我们首先设计了一种新的LSTM变体，命名为style-factual LSTM，作为我们模型的构建块。它使用两组矩阵分别捕获事实和程式化的知识，并根据先前的上下文自动学习两组的单词级权重。此外，当我们训练模型来捕捉风格化元素时，我们提出了一种基于参考事实模型的自适应学习方法，当模型从风格化标题标签中学习时，它为模型提供事实知识，并且可以自适应地计算多少信息到每个时间步供应。我们在两个风格化的图像字幕数据集上评估我们的模型，这些数据集分别包含幽默/浪漫字幕和正/负字幕。实验表明，我们提出的模型优于最先进的方法，而不使用额外的地面实况监督。

##### URL
[http://arxiv.org/abs/1807.03871](http://arxiv.org/abs/1807.03871)

##### PDF
[http://arxiv.org/pdf/1807.03871](http://arxiv.org/pdf/1807.03871)

