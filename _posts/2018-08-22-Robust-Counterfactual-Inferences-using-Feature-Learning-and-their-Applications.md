---
layout: post
title: "Robust Counterfactual Inferences using Feature Learning and their Applications"
date: 2018-08-22 21:26:06
categories: arXiv_AI
tags: arXiv_AI Inference
author: Abhimanyu Mitra, Kannan Achan, Sushant Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
In a wide variety of applications, including personalization, we want to measure the difference in outcome due to an intervention and thus have to deal with counterfactual inference. The feedback from a customer in any of these situations is only 'bandit feedback' - that is, a partial feedback based on whether we chose to intervene or not. Typically randomized experiments are carried out to understand whether an intervention is overall better than no intervention. Here we present a feature learning algorithm to learn from a randomized experiment where the intervention in consideration is most effective and where it is least effective rather than only focusing on the overall impact, thus adding a context to our learning mechanism and extract more information. From the randomized experiment, we learn the feature representations which divide the population into subpopulations where we observe statistically significant difference in average customer feedback between those who were subjected to the intervention and those who were not, with a level of significance l, where l is a configurable parameter in our model. We use this information to derive the value of the intervention in consideration for each instance in the population. With experiments, we show that using this additional learning, in future interventions, the context for each instance could be leveraged to decide whether to intervene or not.

##### Abstract (translated by Google)
在各种各样的应用程序中，包括个性化，我们希望衡量由于干预导致的结果差异，因此必须处理反事实推断。在任何这些情况下，客户的反馈只是“强盗反馈” - 即根据我们是否选择干预的部分反馈。通常进行随机实验以了解干预是否总体上优于不干预。在这里，我们提出了一种特征学习算法，可以从随机实验中学习，其中考虑的干预最有效，而且效果最差，而不是只关注整体影响，从而为我们的学习机制添加背景并提取更多信息。从随机实验中，我们学习了将人口划分为亚人群的特征表征，我们观察到受到干预的人与非干预者之间的平均客户反馈的统计学显着差异，具有显着性水平l，其中l是我们模型中的可配置参数。我们使用这些信息来得出干预的价值，并考虑到人口中的每个实例。通过实验，我们展示了使用这种额外的学习，在未来的干预中，可以利用每个实例的背景来决定是否进行干预。

##### URL
[http://arxiv.org/abs/1808.07569](http://arxiv.org/abs/1808.07569)

##### PDF
[http://arxiv.org/pdf/1808.07569](http://arxiv.org/pdf/1808.07569)

