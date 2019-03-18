---
layout: post
title: "Graph Hierarchical Convolutional Recurrent Neural Network for Vehicle Condition Prediction"
date: 2019-03-12 01:24:47
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction Relation
author: Mingming Lu, Kunfang Zhang, Haiying Liu, Naixue Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
The prediction of urban vehicle flow and speed can greatly facilitate people's travel, and also can provide reasonable advice for the decision-making of relevant government departments. However, due to the spatial, temporal and hierarchy of vehicle flow and many influencing factors such as weather, it is difficult to prediction. Most of the existing research methods are to extract spatial structure information on the road network and extract time series information from the historical data. However, when extracting spatial features, these methods have higher time and space complexity, and incorporate a lot of noise. It is difficult to apply on large graphs, and only considers the influence of surrounding connected road nodes on the central node, ignoring a very important hierarchical relationship, namely, similar information of similar node features and road network structures. In response to these problems, this paper proposes the Graph Hierarchical Convolutional Recurrent Neural Network (GHCRNN) model. The model uses GCN (Graph Convolutional Networks) to extract spatial feature, GRU (Gated Recurrent Units) to extract temporal feature, and uses the learnable Pooling to extract hierarchical information, eliminate redundant information and reduce complexity. Applying this model to the vehicle flow and speed data of Shenzhen and Los Angeles has been well verified, and the time and memory consumption are effectively reduced under the compared precision.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06261](http://arxiv.org/abs/1903.06261)

##### PDF
[http://arxiv.org/pdf/1903.06261](http://arxiv.org/pdf/1903.06261)

