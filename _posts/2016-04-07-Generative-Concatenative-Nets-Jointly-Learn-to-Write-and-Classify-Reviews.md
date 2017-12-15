---
layout: post
title: "Generative Concatenative Nets Jointly Learn to Write and Classify Reviews"
date: 2016-04-07 07:08:42
categories: arXiv_CL
tags: arXiv_CL Sentiment Review RNN Recommendation
author: Zachary C. Lipton, Sharad Vikram, Julian McAuley
mathjax: true
---

* content
{:toc}

##### Abstract
A recommender system's basic task is to estimate how users will respond to unseen items. This is typically modeled in terms of how a user might rate a product, but here we aim to extend such approaches to model how a user would write about the product. To do so, we design a character-level Recurrent Neural Network (RNN) that generates personalized product reviews. The network convincingly learns styles and opinions of nearly 1000 distinct authors, using a large corpus of reviews from BeerAdvocate.com. It also tailors reviews to describe specific items, categories, and star ratings. Using a simple input replication strategy, the Generative Concatenative Network (GCN) preserves the signal of static auxiliary inputs across wide sequence intervals. Without any additional training, the generative model can classify reviews, identifying the author of the review, the product category, and the sentiment (rating), with remarkable accuracy. Our evaluation shows the GCN captures complex dynamics in text, such as the effect of negation, misspellings, slang, and large vocabularies gracefully absent any machinery explicitly dedicated to the purpose.

##### Abstract (translated by Google)
推荐系统的基本任务是估计用户将如何响应看不见的项目。这通常是根据用户如何评价产品来建模的，但我们的目标是扩展这种方法来模拟用户如何撰写产品。为此，我们设计了一个人物级的递归神经网络（RNN），可以生成个性化的产品评论。网络使用来自BeerAdvocate.com的大量评论，令人信服地学习了将近1000位不同作者的风格和观点。它也定制评论来描述具体的项目，类别和星级。生成连接网络（GCN）使用简单的输入复制策略，在较宽的序列间隔内保留静态辅助输入的信号。没有任何额外的培训，生成模型可以非常精确地对评论进行分类，识别评论的作者，产品类别和情感（评级）。我们的评估显示，GCN捕捉到文本中的复杂动态，例如否定，拼写错误，俚语和大型词汇的影响，优雅地缺少任何明确致力于此目的的机器。

##### URL
[https://arxiv.org/abs/1511.03683](https://arxiv.org/abs/1511.03683)

##### PDF
[https://arxiv.org/pdf/1511.03683](https://arxiv.org/pdf/1511.03683)

