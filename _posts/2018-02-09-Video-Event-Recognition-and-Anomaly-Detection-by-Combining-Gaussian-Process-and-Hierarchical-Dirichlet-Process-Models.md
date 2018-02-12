---
layout: post
title: "Video Event Recognition and Anomaly Detection by Combining Gaussian Process and Hierarchical Dirichlet Process Models"
date: 2018-02-09 13:46:41
categories: arXiv_CV
tags: arXiv_CV Classification Detection Recognition
author: Michael Ying Yang, Wentong Liao, Yanpeng Cao, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an unsupervised learning framework for analyzing activities and interactions in surveillance videos. In our framework, three levels of video events are connected by Hierarchical Dirichlet Process (HDP) model: low-level visual features, simple atomic activities, and multi-agent interactions. Atomic activities are represented as distribution of low-level features, while complicated interactions are represented as distribution of atomic activities. This learning process is unsupervised. Given a training video sequence, low-level visual features are extracted based on optic flow and then clustered into different atomic activities and video clips are clustered into different interactions. The HDP model automatically decide the number of clusters, i.e. the categories of atomic activities and interactions. Based on the learned atomic activities and interactions, a training dataset is generated to train the Gaussian Process (GP) classifier. Then the trained GP models work in newly captured video to classify interactions and detect abnormal events in real time. Furthermore, the temporal dependencies between video events learned by HDP-Hidden Markov Models (HMM) are effectively integrated into GP classifier to enhance the accuracy of the classification in newly captured videos. Our framework couples the benefits of the generative model (HDP) with the discriminant model (GP). We provide detailed experiments showing that our framework enjoys favorable performance in video event classification in real-time in a crowded traffic scene.

##### Abstract (translated by Google)
在本文中，我们提出了一个无监督的学习框架来分析监控视频中的活动和交互。在我们的框架中，三层视频事件通过分层Dirichlet过程（HDP）模型进行连接：低级视觉特征，简单原子活动和多智能体交互。原子活动表示为低层特征的分布，而复杂的相互作用表示为原子活动的分布。这个学习过程是无监督的。给定训练视频序列，基于光流提取低级视觉特征，然后聚集成不同的原子活动，并将视频剪辑聚集成不同的交互。 HDP模型自动决定簇的数量，即原子活动和相互作用的类别。基于学习到的原子活动和相互作用，生成训练数据集以训练高斯过程（GP）分类器。然后，训练的GP模型在新捕​​获的视频中工作，以实时分类交互并检测异常事件。此外，由HDP隐马尔可夫模型（HMM）学习的视频事件之间的时间依赖性被有效地整合到GP分类器中，以提高新捕获视频中分类的准确性。我们的框架将生成模型（HDP）的好处与判别模型（GP）结合起来。我们提供了详细的实验，表明我们的框架在拥挤的交通场景中实时地进行视频事件分类具有良好的性能。

##### URL
[http://arxiv.org/abs/1802.03257](http://arxiv.org/abs/1802.03257)

##### PDF
[http://arxiv.org/pdf/1802.03257](http://arxiv.org/pdf/1802.03257)

