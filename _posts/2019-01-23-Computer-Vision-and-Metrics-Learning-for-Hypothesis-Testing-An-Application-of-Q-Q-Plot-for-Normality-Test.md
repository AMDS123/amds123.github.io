---
layout: post
title: "Computer Vision and Metrics Learning for Hypothesis Testing: An Application of Q-Q Plot for Normality Test"
date: 2019-01-23 12:38:17
categories: arXiv_CV
tags: arXiv_CV
author: Ke-Wei Huang, Mengke Qiao, Xuanqi Liu, Mingxi Dai, Siyuan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new procedure to construct test statistics for hypothesis testing by computer vision and metrics learning. The application highlighted in this paper is applying computer vision on Q-Q plot to construct a new test statistic for normality test. Traditionally, there are two families of approaches for verifying the probability distribution of a random variable. Researchers either subjectively assess the Q-Q plot or objectively use a mathematical formula, such as Kolmogorov-Smirnov test, to formally conduct a normality test. Graphical assessment by human beings is not rigorous whereas normality test statistics may not be accurate enough when the uniformly most powerful test does not exist. It may take tens of years for statistician to develop a new and more powerful test statistic. The first step of the proposed method is to apply computer vision techniques, such as pre-trained ResNet, to convert a Q-Q plot into a numerical vector. Next step is to apply metric learning to find an appropriate distance function between a Q-Q plot and the centroid of all Q-Q plots under the null hypothesis, which assumes the target variable is normally distributed. This distance metric is the new test statistic for normality test. Our experimentation results show that the machine-learning-based test statistics can outperform traditional normality tests in all cases, particularly when the sample size is small. This study provides convincing evidence that the proposed method could objectively create a powerful test statistic based on Q-Q plots and this method could be modified to construct many more powerful test statistics for other applications in the future.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07851](http://arxiv.org/abs/1901.07851)

##### PDF
[http://arxiv.org/pdf/1901.07851](http://arxiv.org/pdf/1901.07851)

