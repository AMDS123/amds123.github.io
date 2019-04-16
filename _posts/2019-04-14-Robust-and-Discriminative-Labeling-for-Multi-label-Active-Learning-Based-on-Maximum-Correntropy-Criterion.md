---
layout: post
title: "Robust and Discriminative Labeling for Multi-label Active Learning Based on Maximum Correntropy Criterion"
date: 2019-04-14 12:53:57
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction
author: Bo Du, Zengmao Wang, Lefei Zhang, Liangpei Zhang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-label learning draws great interests in many real world applications. It is a highly costly task to assign many labels by the oracle for one instance. Meanwhile, it is also hard to build a good model without diagnosing discriminative labels. Can we reduce the label costs and improve the ability to train a good model for multi-label learning simultaneously? 
 Active learning addresses the less training samples problem by querying the most valuable samples to achieve a better performance with little costs. In multi-label active learning, some researches have been done for querying the relevant labels with less training samples or querying all labels without diagnosing the discriminative information. They all cannot effectively handle the outlier labels for the measurement of uncertainty. Since Maximum Correntropy Criterion (MCC) provides a robust analysis for outliers in many machine learning and data mining algorithms, in this paper, we derive a robust multi-label active learning algorithm based on MCC by merging uncertainty and representativeness, and propose an efficient alternating optimization method to solve it. With MCC, our method can eliminate the influence of outlier labels that are not discriminative to measure the uncertainty. To make further improvement on the ability of information measurement, we merge uncertainty and representativeness with the prediction labels of unknown data. It can not only enhance the uncertainty but also improve the similarity measurement of multi-label data with labels information. Experiments on benchmark multi-label data sets have shown a superior performance than the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06689](http://arxiv.org/abs/1904.06689)

##### PDF
[http://arxiv.org/pdf/1904.06689](http://arxiv.org/pdf/1904.06689)

