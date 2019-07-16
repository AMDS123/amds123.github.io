---
layout: post
title: "Feature Learning for Fault Detection in High-Dimensional Condition-Monitoring Signals"
date: 2019-07-15 09:52:44
categories: arXiv_AI
tags: arXiv_AI Classification Detection
author: Gabriel Michau, Yang Hu, Thomas Palm&#xe9;, Olga Fink
mathjax: true
---

* content
{:toc}

##### Abstract
Complex industrial systems are continuously monitored by a large number of heterogeneous sensors. The diversity of their operating conditions and the possible fault types make it impossible to collect enough data for learning all the possible fault patterns. The paper proposes an integrated automatic unsupervised feature learning and one-class classification for fault detection that uses data on healthy conditions only for its training. The approach is based on stacked Extreme Learning Machines (namely Hierarchical, or HELM) and comprises an autoencoder, performing unsupervised feature learning, stacked with a one-class classifier monitoring the distance of the test data to the training healthy class, thereby assessing the health of the system. 
 This study provides a comprehensive evaluation of HELM fault detection capability compared to other machine learning approaches, such as stand-alone one-class classifiers (ELM and SVM), these same one-class classifiers combined with traditional dimensionality reduction methods (PCA) and a Deep Belief Network. The performance is first evaluated on a synthetic dataset that encompasses typical characteristics of condition monitoring data. Subsequently, the approach is evaluated on a real case study of a power plant fault. The proposed algorithm for fault detection, combining feature learning with the one-class classifier, demonstrates a better performance, particularly in cases where condition monitoring data contain several non-informative signals.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.05550](http://arxiv.org/abs/1810.05550)

##### PDF
[http://arxiv.org/pdf/1810.05550](http://arxiv.org/pdf/1810.05550)

