---
layout: post
title: "NPA: Neural News Recommendation with Personalized Attention"
date: 2019-07-12 03:11:14
categories: arXiv_CL
tags: arXiv_CL Attention Embedding Recommendation
author: Chuhan Wu, Fangzhao Wu, Mingxiao An, Jianqiang Huang, Yongfeng Huang, Xing Xie
mathjax: true
---

* content
{:toc}

##### Abstract
News recommendation is very important to help users find interested news and alleviate information overload. Different users usually have different interests and the same user may have various interests. Thus, different users may click the same news article with attention on different aspects. In this paper, we propose a neural news recommendation model with personalized attention (NPA). The core of our approach is a news representation model and a user representation model. In the news representation model we use a CNN network to learn hidden representations of news articles based on their titles. In the user representation model we learn the representations of users based on the representations of their clicked news articles. Since different words and different news articles may have different informativeness for representing news and users, we propose to apply both word- and news-level attention mechanism to help our model attend to important words and news articles. In addition, the same news article and the same word may have different informativeness for different users. Thus, we propose a personalized attention network which exploits the embedding of user ID to generate the query vector for the word- and news-level attentions. Extensive experiments are conducted on a real-world news recommendation dataset collected from MSN news, and the results validate the effectiveness of our approach on news recommendation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05559](http://arxiv.org/abs/1907.05559)

##### PDF
[http://arxiv.org/pdf/1907.05559](http://arxiv.org/pdf/1907.05559)

