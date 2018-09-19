---
layout: post
title: "In-Session Personalization for Talent Search"
date: 2018-09-18 00:24:23
categories: arXiv_AI
tags: arXiv_AI Recommendation
author: Sahin Cem Geyik, Vijay Dialani, Meng Meng, Ryan Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Previous efforts in recommendation of candidates for talent search followed the general pattern of receiving an initial search criteria and generating a set of candidates utilizing a pre-trained model. Traditionally, the generated recommendations are final, that is, the list of potential candidates is not modified unless the user explicitly changes his/her search criteria. In this paper, we are proposing a candidate recommendation model which takes into account the immediate feedback of the user, and updates the candidate recommendations at each step. This setting also allows for very uninformative initial search queries, since we pinpoint the user's intent due to the feedback during the search session. To achieve our goal, we employ an intent clustering method based on topic modeling which separates the candidate space into meaningful, possibly overlapping, subsets (which we call intent clusters) for each position. On top of the candidate segments, we apply a multi-armed bandit approach to choose which intent cluster is more appropriate for the current session. We also present an online learning scheme which updates the intent clusters within the session, due to user feedback, to achieve further personalization. Our offline experiments as well as the results from the online deployment of our solution demonstrate the benefits of our proposed methodology.

##### Abstract (translated by Google)
以前在人才搜索候选人推荐方面的努力遵循一般模式，即接收初始搜索标准并利用预先训练的模型生成一组候选人。传统上，生成的推荐是最终的，即，除非用户明确地改变他/她的搜索标准，否则不会修改潜在候选者的列表。在本文中，我们提出了一个候选推荐模型，该模型考虑了用户的即时反馈，并在每个步骤更新候选推荐。此设置还允许非常无法提供信息的初始搜索查询，因为我们会在搜索会话期间根据反馈确定用户的意图。为了实现我们的目标，我们采用基于主题建模的意图聚类方法，该方法将候选空间分离为每个位置的有意义的，可能重叠的子集（我们称之为意图聚类）。在候选区段之上，我们应用多臂强盗方法来选择哪个意图集群更适合当前会话。我们还提供了一种在线学习方案，该方案由于用户反馈而更新会话中的意图聚类，以实现进一步的个性化。我们的离线实验以及在线部署解决方案的结果证明了我们提出的方法的好处。

##### URL
[https://arxiv.org/abs/1809.06488](https://arxiv.org/abs/1809.06488)

##### PDF
[https://arxiv.org/pdf/1809.06488](https://arxiv.org/pdf/1809.06488)

