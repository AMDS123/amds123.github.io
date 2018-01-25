---
layout: post
title: "Improving Review Representations with User Attention and Product Attention for Sentiment Classification"
date: 2018-01-24 05:11:57
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Attention Sentiment_Classification Classification Prediction
author: Zhen Wu, Xin-Yu Dai, Cunyan Yin, Shujian Huang, Jiajun Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network methods have achieved great success in reviews sentiment classification. Recently, some works achieved improvement by incorporating user and product information to generate a review representation. However, in reviews, we observe that some words or sentences show strong user's preference, and some others tend to indicate product's characteristic. The two kinds of information play different roles in determining the sentiment label of a review. Therefore, it is not reasonable to encode user and product information together into one representation. In this paper, we propose a novel framework to encode user and product information. Firstly, we apply two individual hierarchical neural networks to generate two representations, with user attention or with product attention. Then, we design a combined strategy to make full use of the two representations for training and final prediction. The experimental results show that our model obviously outperforms other state-of-the-art methods on IMDB and Yelp datasets. Through the visualization of attention over words related to user or product, we validate our observation mentioned above.

##### Abstract (translated by Google)
神经网络方法在评论情感分类方面取得了很大的成功。最近，一些作品通过结合用户和产品信息来生成评论表示而得到改进。然而，在评论中，我们观察到一些词或句子表现出强烈的用户偏好，而另一些倾向于指示产品的特征。这两种信息在确定评论的情感标签方面起着不同的作用。因此，将用户和产品信息一起编码成一个表示是不合理的。在本文中，我们提出了一个新的框架来编码用户和产品信息。首先，我们应用两个单独的层次神经网络来生成两个表示，用户关注或产品关注。然后，我们设计一个组合策略，充分利用这两个表示进行训练和最终预测。实验结果表明，我们的模型明显优于IMDB和Yelp数据集上的其他最先进的方法。通过关注与用户或产品相关的词汇的可视化，我们验证了上述的观察结果。

##### URL
[http://arxiv.org/abs/1801.07861](http://arxiv.org/abs/1801.07861)

##### PDF
[http://arxiv.org/pdf/1801.07861](http://arxiv.org/pdf/1801.07861)

