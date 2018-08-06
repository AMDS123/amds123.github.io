---
layout: post
title: "SWDE : A Sub-Word And Document Embedding Based Engine for Clickbait Detection"
date: 2018-08-02 09:02:00
categories: arXiv_CL
tags: arXiv_CL Attention Embedding CNN RNN Detection
author: Vaibhav Kumar, Mrinal Dhar, Dhruv Khattar, Yash Kumar Lal, Abhimanshu Mishra, Manish Shrivastava, Vasudeva Varma
mathjax: true
---

* content
{:toc}

##### Abstract
In order to expand their reach and increase website ad revenue, media outlets have started using clickbait techniques to lure readers to click on articles on their digital platform. Having successfully enticed the user to open the article, the article fails to satiate his curiosity serving only to boost click-through rates. Initial methods for this task were dependent on feature engineering, which varies with each dataset. Industry systems have relied on an exhaustive set of rules to get the job done. Neural networks have barely been explored to perform this task. We propose a novel approach considering different textual embeddings of a news headline and the related article. We generate sub-word level embeddings of the title using Convolutional Neural Networks and use them to train a bidirectional LSTM architecture. An attention layer allows for calculation of significance of each term towards the nature of the post. We also generate Doc2Vec embeddings of the title and article text and model how they interact, following which it is concatenated with the output of the previous component. Finally, this representation is passed through a neural network to obtain a score for the headline. We test our model over 2538 posts (having trained it on 17000 records) and achieve an accuracy of 83.49% outscoring previous state-of-the-art approaches.

##### Abstract (translated by Google)
为了扩大影响范围并增加网站广告收入，媒体机构已开始使用clickbait技术吸引读者点击其数字平台上的文章。成功吸引用户打开文章后，该文章无法满足他的好奇心，只是为了提高点击率。此任务的初始方法取决于特征工程，该特征工程随每个数据集而变化。行业系统依赖于一套详尽的规则来完成工作。几乎没有探索过神经网络来执行这项任务。我们提出了一种考虑新闻标题和相关文章的不同文本嵌入的新方法。我们使用卷积神经网络生成标题的子词级嵌入，并使用它们来训练双向LSTM架构。注意层允许计算每个术语对于帖子性质的重要性。我们还生成标题和文章文本的Doc2Vec嵌入，并模拟它们如何交互，然后将它与前一个组件的输出连接起来。最后，该表示通过神经网络传递以获得标题的分数。我们测试了我们的模型超过2538个帖子（已经在17000条记录上进行了训练）并且达到了83.49％的准确度，超过了以前最先进的方法。

##### URL
[https://arxiv.org/abs/1808.00957](https://arxiv.org/abs/1808.00957)

##### PDF
[https://arxiv.org/pdf/1808.00957](https://arxiv.org/pdf/1808.00957)

