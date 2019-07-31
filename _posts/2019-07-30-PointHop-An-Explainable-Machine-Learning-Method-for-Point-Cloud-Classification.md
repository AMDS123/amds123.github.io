---
layout: post
title: "PointHop: An Explainable Machine Learning Method for Point Cloud Classification"
date: 2019-07-30 07:39:40
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Min Zhang, Haoxuan You, Pranav Kadam, Shan Liu, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
An explainable machine learning method for point cloud classification, called the PointHop method, is proposed in this work. The PointHop method consists of two stages: 1) local-to-global attribute building through iterative one-hop information exchange, and 2) classification and ensembles. In the attribute building stage, we address the problem of unordered point cloud data using a space partitioning procedure and developing a robust descriptor that characterizes the relationship between a point and its one-hop neighbor in a PointHop unit. When we put multiple PointHop units in cascade, the attributes of a point will grow by taking its relationship with one-hop neighbor points into account iteratively. Furthermore, to control the rapid dimension growth of the attribute vector associated with a point, we use the Saab transform to reduce the attribute dimension in each PointHop unit. In the classification and ensemble stage, we feed the feature vector obtained from multiple PointHop units to a classifier. We explore ensemble methods to improve the classification performance furthermore. It is shown by experimental results that the PointHop method offers classification performance that is comparable with state-of-the-art methods while demanding much lower training complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12766](http://arxiv.org/abs/1907.12766)

##### PDF
[http://arxiv.org/pdf/1907.12766](http://arxiv.org/pdf/1907.12766)

