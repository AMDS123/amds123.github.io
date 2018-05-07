---
layout: post
title: "Beyond the Click-Through Rate: Web Link Selection with Multi-level Feedback"
date: 2018-05-04 10:37:27
categories: arXiv_AI
tags: arXiv_AI Recommendation
author: Kun Chen, Kechao Cai, Longbo Huang, John C.S. Lui
mathjax: true
---

* content
{:toc}

##### Abstract
The web link selection problem is to select a small subset of web links from a large web link pool, and to place the selected links on a web page that can only accommodate a limited number of links, e.g., advertisements, recommendations, or news feeds. Despite the long concerned click-through rate which reflects the attractiveness of the link itself, the revenue can only be obtained from user actions after clicks, e.g., purchasing after being directed to the product pages by recommendation links. Thus, the web links have an intrinsic \emph{multi-level feedback structure}. With this observation, we consider the context-free web link selection problem, where the objective is to maximize revenue while ensuring that the attractiveness is no less than a preset threshold. The key challenge of the problem is that each link's multi-level feedbacks are stochastic, and unobservable unless the link is selected. We model this problem with a constrained stochastic multi-armed bandit formulation, and design an efficient link selection algorithm, called Constrained Upper Confidence Bound algorithm (\textbf{Con-UCB}), and prove $O(\sqrt{T\ln T})$ bounds on both the regret and the violation of the attractiveness constraint. We conduct extensive experiments on three real-world datasets, and show that \textbf{Con-UCB} outperforms state-of-the-art context-free bandit algorithms concerning the multi-level feedback structure.

##### Abstract (translated by Google)
网络链接选择问题是从大型网络链接池中选择一小部分网络链接，并将选定的链接放在只能容纳有限数量链接的网页上，例如广告，推荐或新闻提要。尽管长期关注的点击率反映了链接本身的吸引力，但收入只能通过点击后的用户操作获得，例如通过推荐链接指向产品页面后购买。因此，网络链接具有内在的“多层次反馈结构”。有了这个观察，我们考虑了上下文无关的网络链接选择问题，其目标是在确保吸引力不低于预设阈值的同时使收入最大化。问题的关键挑战是每条链路的多级反馈都是随机的，除非选择链路，否则不可观测。我们用一个受约束的随机多臂强盗公式对这个问题进行建模，并设计一个有效的链接选择算法，称为约束上置信区间算法（\ textbf {Con-UCB}），并证明$ O（\ sqrt {T \ ln T }）$既有遗憾又有违反吸引力约束的限制。我们对三个真实世界的数据集进行了广泛的实验，并且证明\ textbf {Con-UCB}优于关于多级反馈结构的最先进的上下文无关的bandit算法。

##### URL
[http://arxiv.org/abs/1805.01702](http://arxiv.org/abs/1805.01702)

##### PDF
[http://arxiv.org/pdf/1805.01702](http://arxiv.org/pdf/1805.01702)

