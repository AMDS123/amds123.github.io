---
layout: post
title: "Ranking for Relevance and Display Preferences in Complex Presentation Layouts"
date: 2018-05-07 08:48:18
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Harrie Oosterhuis, Maarten de Rijke
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to Rank has traditionally considered settings where given the relevance information of objects, the desired order in which to rank the objects is clear. However, with today's large variety of users and layouts this is not always the case. In this paper, we consider so-called complex ranking settings where it is not clear what should be displayed, that is, what the relevant items are, and how they should be displayed, that is, where the most relevant items should be placed. These ranking settings are complex as they involve both traditional ranking and inferring the best display order. Existing learning to rank methods cannot handle such complex ranking settings as they assume that the display order is known beforehand. To address this gap we introduce a novel Deep Reinforcement Learning method that is capable of learning complex rankings, both the layout and the best ranking given the layout, from weak reward signals. Our proposed method does so by selecting documents and positions sequentially, hence it ranks both the documents and positions, which is why we call it the Double-Rank Model (DRM). Our experiments show that DRM outperforms all existing methods in complex ranking settings, thus it leads to substantial ranking improvements in cases where the display order is not known a priori.

##### Abstract (translated by Google)
学习排名传统上考虑设置，在给定了对象的相关性信息的情况下，排列对象的期望顺序是清楚的。但是，对于今天的各种用户和布局，情况并非总是如此。在本文中，我们考虑所谓的复杂排名设置，其中不清楚应该显示什么，即相关项目是什么，以及应该如何显示它们，也就是说，应该放置最相关的项目的位置。这些排名设置很复杂，因为它们涉及传统排名和推断最佳显示顺序。现有的学习排名方法不能处理如此复杂的排名设置，因为他们认为显示顺序是事先知道的。为了弥补这种差距，我们引入了一种新型的Deep Reinforcement Learning方法，该方法能够从弱报酬信号中学习复杂的排名，布局和给定布局的最佳排名。我们提出的方法是通过顺序选择文档和位置来完成的，因此它将文档和位置进行排序，这就是为什么我们将其称为双排序模型（DRM）的原因。我们的实验表明，DRM在复杂的排名设置中胜过所有现有的方法，因此在显示顺序未知的情况下，它可以显着提高排名。

##### URL
[https://arxiv.org/abs/1805.02404](https://arxiv.org/abs/1805.02404)

##### PDF
[https://arxiv.org/pdf/1805.02404](https://arxiv.org/pdf/1805.02404)

