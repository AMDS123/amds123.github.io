---
layout: post
title: "TransRev: Modeling Reviews as Translations from Users to Items"
date: 2018-01-30 17:01:01
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Embedding Prediction Relation Recommendation
author: Alberto Garcia-Duran, Roberto Gonzalez, Daniel Onoro-Rubio, Mathias Niepert, Hui Li
mathjax: true
---

* content
{:toc}

##### Abstract
The text of a review expresses the sentiment a customer has towards a particular product. This is exploited in sentiment analysis where machine learning models are used to predict the review score from the text of the review. Furthermore, the products costumers have purchased in the past are indicative of the products they will purchase in the future. This is what recommender systems exploit by learning models from purchase information to predict the items a customer might be interested in. We propose TransRev, an approach to the product recommendation problem that integrates ideas from recommender systems, sentiment analysis, and multi-relational learning into a joint learning objective. 
 TransRev learns vector representations for users, items, and reviews. The embedding of a review is learned such that (a) it performs well as input feature of a regression model for sentiment prediction; and (b) it always translates the reviewer embedding to the embedding of the reviewed items. This allows TransRev to approximate a review embedding at test time as the difference of the embedding of each item and the user embedding. The approximated review embedding is then used with the regression model to predict the review score for each item. TransRev outperforms state of the art recommender systems on a large number of benchmark data sets. Moreover, it is able to retrieve, for each user and item, the review text from the training set whose embedding is most similar to the approximated review embedding.

##### Abstract (translated by Google)
评论的文字表达了顾客对特定产品的情感。这在情感分析中被利用，其中使用机器学习模型来预测来自评论文本的评论分数。此外，过去购买的产品服务人员指示将来要购买的产品。这就是推荐系统通过从购买信息中学习模型来预测客户可能感兴趣的项目而利用的推荐系统。我们提出TransRev，这是一种将推荐系统，情感分析和多关系学习的想法集成到产品推荐问题的方法，共同的学习目标。
 TransRev学习用户，项目和评论的矢量表示。 （a）作为情感预测回归模型的输入特征，表现良好; （b）它总是将审阅者嵌入翻译成嵌入审阅项目。这允许TransRev在测试时间近似评论嵌入，作为每个项目的嵌入和用户嵌入的差异。然后使用近似的评论嵌入与回归模型来预测每个项目的评论分数。 TransRev在大量基准数据集上优于现有技术的推荐系统。而且，对于每个用户和项目，能够从其嵌入与近似评论嵌入最相似的训练集合中检索评论文本。

##### URL
[http://arxiv.org/abs/1801.10095](http://arxiv.org/abs/1801.10095)

##### PDF
[http://arxiv.org/pdf/1801.10095](http://arxiv.org/pdf/1801.10095)

