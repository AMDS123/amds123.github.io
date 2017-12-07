---
layout: post
title: "Video Paragraph Captioning Using Hierarchical Recurrent Neural Networks"
date: 2016-04-06 02:24:35
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption RNN
author: Haonan Yu, Jiang Wang, Zhiheng Huang, Yi Yang, Wei Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach that exploits hierarchical Recurrent Neural Networks (RNNs) to tackle the video captioning problem, i.e., generating one or multiple sentences to describe a realistic video. Our hierarchical framework contains a sentence generator and a paragraph generator. The sentence generator produces one simple short sentence that describes a specific short video interval. It exploits both temporal- and spatial-attention mechanisms to selectively focus on visual elements during generation. The paragraph generator captures the inter-sentence dependency by taking as input the sentential embedding produced by the sentence generator, combining it with the paragraph history, and outputting the new initial state for the sentence generator. We evaluate our approach on two large-scale benchmark datasets: YouTubeClips and TACoS-MultiLevel. The experiments demonstrate that our approach significantly outperforms the current state-of-the-art methods with BLEU@4 scores 0.499 and 0.305 respectively.

##### Abstract (translated by Google)
我们提出了一种利用递归神经网络（RNNs）来处理视频字幕问题的方法，即生成一个或多个句子来描述一个真实的视频。我们的分层框架包含一个句子生成器和一个段落生成器句子生成器产生一个简单的短句子，描述一个特定的短视频间隔。它利用时间和空间的注意机制来选择性地关注生成过程中的视觉元素。段落生成器通过将由句子生成器生成的句子嵌入作为输入，将其与段落历史相结合，并输出句子生成器的新的初始状态来捕获句间依赖。我们在两个大型基准数据集上评估我们的方法：YouTubeClips和TACoS-MultiLevel。实验证明，我们的方法在BLEU @ 4分数分别为0.499和0.305的情况下明显优于目前最先进的方法。

##### URL
[https://arxiv.org/abs/1510.07712](https://arxiv.org/abs/1510.07712)

##### PDF
[https://arxiv.org/pdf/1510.07712](https://arxiv.org/pdf/1510.07712)

