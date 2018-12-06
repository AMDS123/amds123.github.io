---
layout: post
title: "Dynamic Spatio-temporal Graph-based CNNs for Traffic Prediction"
date: 2018-12-05 14:34:10
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Relation
author: Menglin Wang, Baisheng Lai, Xiaojin Gong, Xiansheng Hua, Jianqiang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate traffic forecast is a challenging problem due to the large-scale problem size, as well as the complex and dynamic nature of spatio-temporal dependency of traffic flow. Most existing graph-based CNNs attempt to capture the static relations while largely neglecting the dynamics underlying sequential data. In this paper, we present dynamic spatio-temporal graph-based CNNs (DST-GCNNs) by learning expressive features to represent spatio-temporal structures and predict future traffic from historical traffic flow. In particular, DST-GCNN is a two stream network. In the flow prediction stream, we present a novel graph-based spatio-temporal convolutional layer to extract features from a graph representation of traffic flow. Then several such layers are stacked together to predict future traffic over time. Meanwhile, the proximity relations between nodes in the graph are often time variant as the traffic condition changes over time. To capture the graph dynamics, we use the graph prediction stream to predict the dynamic graph structures, and the predicted structures are fed into the flow prediction stream. Experiments on real traffic datasets demonstrate that the proposed model achieves competitive performances compared with the other state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02019](http://arxiv.org/abs/1812.02019)

##### PDF
[http://arxiv.org/pdf/1812.02019](http://arxiv.org/pdf/1812.02019)

