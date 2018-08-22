---
layout: post
title: "CoT: Cooperative Training for Generative Modeling of Discrete Data"
date: 2018-08-21 05:38:27
categories: arXiv_AI
tags: arXiv_AI
author: Sidi Lu, Lantao Yu, Weinan Zhang, Yong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Cooperative Training (CoT) for training generative models that measure a tractable density for discrete data. CoT coordinately trains a generator $G$ and an auxiliary predictive mediator $M$. The training target of $M$ is to estimate a mixture density of the learned distribution $G$ and the target distribution $P$, and that of $G$ is to minimize the Jensen-Shannon divergence estimated through $M$. CoT achieves independent success without the necessity of pre-training via Maximum Likelihood Estimation or involving high-variance algorithms like REINFORCE. This low-variance algorithm is theoretically proved to be unbiased for both generative and predictive tasks. We also theoretically and empirically show the superiority of CoT over most previous algorithms in terms of generative quality and diversity, predictive generalization ability and computational cost.

##### Abstract (translated by Google)
我们提出合作训练（CoT）来训练生成模型，该模型测量离散数据的易处理密度。 CoT协调训练发电机$ G $和辅助预测调解员$ M $。 $ M $的培训目标是估算学习分布$ G $和目标分配$ P $的混合密度，$ G $的目标是最小化通过$ M $估算的Jensen-Shannon分歧。 CoT实现了独立的成功，无需通过最大似然估计进行预训练或涉及像REINFORCE这样的高方差算法。理论上证明这种低方差算法对于生成和预测任务都是无偏的。我们在理论上和经验上也证明了CoT相对于大多数先前算法在生成质量和多样性，预测泛化能力和计算成本方面的优越性。

##### URL
[http://arxiv.org/abs/1804.03782](http://arxiv.org/abs/1804.03782)

##### PDF
[http://arxiv.org/pdf/1804.03782](http://arxiv.org/pdf/1804.03782)

