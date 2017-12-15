---
layout: post
title: "Item Recommendation with Evolving User Preferences and Experience"
date: 2017-05-06 19:22:41
categories: arXiv_CL
tags: arXiv_CL Review Face Prediction Recommendation
author: Subhabrata Mukherjee, Hemank Lamba, Gerhard Weikum
mathjax: true
---

* content
{:toc}

##### Abstract
Current recommender systems exploit user and item similarities by collaborative filtering. Some advanced methods also consider the temporal evolution of item ratings as a global background process. However, all prior methods disregard the individual evolution of a user's experience level and how this is expressed in the user's writing in a review community. In this paper, we model the joint evolution of user experience, interest in specific item facets, writing style, and rating behavior. This way we can generate individual recommendations that take into account the user's maturity level (e.g., recommending art movies rather than blockbusters for a cinematography expert). As only item ratings and review texts are observables, we capture the user's experience and interests in a latent model learned from her reviews, vocabulary and writing style. We develop a generative HMM-LDA model to trace user evolution, where the Hidden Markov Model (HMM) traces her latent experience progressing over time -- with solely user reviews and ratings as observables over time. The facets of a user's interest are drawn from a Latent Dirichlet Allocation (LDA) model derived from her reviews, as a function of her (again latent) experience level. In experiments with five real-world datasets, we show that our model improves the rating prediction over state-of-the-art baselines, by a substantial margin. We also show, in a use-case study, that our model performs well in the assessment of user experience levels.

##### Abstract (translated by Google)
目前的推荐系统通过协作过滤来利用用户和项目的相似性。一些先进的方法也考虑到项目评级的时间演变作为全球背景过程。然而，所有先前的方法都忽略了用户体验水平的个体进化，以及用户在评论社区中如何表达。在本文中，我们模拟用户体验的联合演变，对特定项目方面的兴趣，写作风格和评分行为。通过这种方式，我们可以生成考虑到用户成熟度的个人建议（例如，为电影摄影专家推荐艺术电影而不是大片）。由于只有项目评级和评论文本是可观察的，我们从用户的评论，词汇和写作风格中学习了潜在模型中的用户体验和兴趣。我们开发了一个生成的HMM-LDA模型来跟踪用户的进化，隐马尔可夫模型（HMM）跟踪她随着时间的推移的潜在经验 - 随着时间的推移，只有用户评论和评级被视为可观察的。用户兴趣的方面是从她的评论中得出的潜在狄利克雷分配（LDA）模型，作为她（也是潜在的）经验水平的函数。在五个真实世界的数据集的实验中，我们表明，我们的模型提高了对最先进的基线的评级预测，这是相当大的。在一个用例研究中，我们还展示了我们的模型在评估用户体验水平方面表现良好。

##### URL
[https://arxiv.org/abs/1705.02519](https://arxiv.org/abs/1705.02519)

##### PDF
[https://arxiv.org/pdf/1705.02519](https://arxiv.org/pdf/1705.02519)

