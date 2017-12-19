---
layout: post
title: "EventNet: A Large Scale Structured Concept Library for Complex Event Detection in Video"
date: 2015-08-17 17:13:23
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Ontology CNN Deep_Learning Detection
author: Guangnan Ye, Yitong Li, Hongliang Xu, Dong Liu, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Event-specific concepts are the semantic concepts designed for the events of interest, which can be used as a mid-level representation of complex events in videos. Existing methods only focus on defining event-specific concepts for a small number of predefined events, but cannot handle novel unseen events. This motivates us to build a large scale event-specific concept library that covers as many real-world events and their concepts as possible. Specifically, we choose WikiHow, an online forum containing a large number of how-to articles on human daily life events. We perform a coarse-to-fine event discovery process and discover 500 events from WikiHow articles. Then we use each event name as query to search YouTube and discover event-specific concepts from the tags of returned videos. After an automatic filter process, we end up with 95,321 videos and 4,490 concepts. We train a Convolutional Neural Network (CNN) model on the 95,321 videos over the 500 events, and use the model to extract deep learning feature from video content. With the learned deep learning feature, we train 4,490 binary SVM classifiers as the event-specific concept library. The concepts and events are further organized in a hierarchical structure defined by WikiHow, and the resultant concept library is called EventNet. Finally, the EventNet concept library is used to generate concept based representation of event videos. To the best of our knowledge, EventNet represents the first video event ontology that organizes events and their concepts into a semantic structure. It offers great potential for event retrieval and browsing. Extensive experiments over the zero-shot event retrieval task when no training samples are available show that the EventNet concept library consistently and significantly outperforms the state-of-the-art (such as the 20K ImageNet concepts trained with CNN) by a large margin up to 207%.

##### Abstract (translated by Google)
特定于事件的概念是为感兴趣的事件设计的语义概念，可以用作视频中复杂事件的中间级别表示。现有的方法只关注为少量预定义的事件定义特定于事件的概念，但不能处理新的看不见的事件。这激励我们建立一个大型的事件特定的概念库，涵盖尽可能多的现实世界事件及其概念。具体而言，我们选择WikiHow，一个包含大量关于人类日常生活事件的指导性文章的在线论坛。我们执行从粗到细的事件发现过程，并从WikiHow文章中发现500个事件。然后，我们使用每个事件名称作为查询来搜索YouTube，并从返回的视频标签中发现特定于事件的概念。经过一个自动过滤程序，我们最终得到95,321个视频和4,490个概念。我们在500个事件上的95,321个视频上训练了一个卷积神经网络（CNN）模型，并使用该模型从视频内容中提取深度学习特征。通过学习深度学习功能，我们训练了4,490个二进制SVM分类器作为事件特定的概念库。这些概念和事件进一步按照WikiHow定义的层次结构进行组织，所得到的概念库称为EventNet。最后，EventNet概念库用于生成事件视频的基于概念的表示。据我们所知，EventNet代表了第一个将事件及其概念组织成一个语义结构的视频事件本体。它为事件检索和浏览提供了巨大的潜力。在没有训练样本可用的情况下，对零点事件检索任务进行的大量实验表明，EventNet概念库一直大大优于最先进的技术（比如用CNN培训的20K ImageNet概念）到207％。

##### URL
[https://arxiv.org/abs/1506.02328](https://arxiv.org/abs/1506.02328)

##### PDF
[https://arxiv.org/pdf/1506.02328](https://arxiv.org/pdf/1506.02328)

