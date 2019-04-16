---
layout: post
title: "'Factual' or 'Emotional': Stylized Image Captioning with Adaptive Learning and Attention"
date: 2018-07-29 22:01:26
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


##### URL
[https://arxiv.org/abs/1807.03871](https://arxiv.org/abs/1807.03871)

##### PDF
[https://arxiv.org/pdf/1807.03871](https://arxiv.org/pdf/1807.03871)

