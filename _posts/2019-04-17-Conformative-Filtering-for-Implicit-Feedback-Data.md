---
layout: post
title: "Conformative Filtering for Implicit Feedback Data"
date: 2019-04-17 18:17:56
categories: arXiv_AI
tags: arXiv_AI Recommendation
author: Farhan Khawar, Nevin L. Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Implicit feedback is the simplest form of user feedback that can be used for item recommendation. It is easy to collect and is domain independent. However, there is a lack of negative examples. Previous work tackles this problem by assuming that users are not interested or not as much interested in the unconsumed items. Those assumptions are often severely violated since non-consumption can be due to factors like unawareness or lack of resources. Therefore, non-consumption by a user does not always mean disinterest or irrelevance. In this paper, we propose a novel method called Conformative Filtering (CoF) to address the issue. The motivating observation is that if there is a large group of users who share the same taste and none of them have consumed an item before, then it is likely that the item is not of interest to the group. We perform multidimensional clustering on implicit feedback data using hierarchical latent tree analysis (HLTA) to identify user `tastes' groups and make recommendations for a user based on her memberships in the groups and on the past behavior of the groups. Experiments on two real-world datasets from different domains show that CoF has superior performance compared to several common baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1704.01889](http://arxiv.org/abs/1704.01889)

##### PDF
[http://arxiv.org/pdf/1704.01889](http://arxiv.org/pdf/1704.01889)

