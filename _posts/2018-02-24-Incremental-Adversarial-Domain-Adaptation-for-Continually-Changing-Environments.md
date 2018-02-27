---
layout: post
title: "Incremental Adversarial Domain Adaptation for Continually Changing Environments"
date: 2018-02-24 16:05:02
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation
author: Markus Wulfmeier, Alex Bewley, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
Continuous appearance shifts such as changes in weather and lighting conditions can impact the performance of deployed machine learning models. While unsupervised domain adaptation aims to address this challenge, current approaches do not utilise the continuity of the occurring shifts. In particular, many robotics applications exhibit these conditions and thus facilitate the potential to incrementally adapt a learnt model over minor shifts which integrate to massive differences over time. Our work presents an adversarial approach for lifelong, incremental domain adaptation which benefits from unsupervised alignment to a series of intermediate domains which successively diverge from the labelled source domain. We empirically demonstrate that our incremental approach improves handling of large appearance changes, e.g. day to night, on a traversable-path segmentation task compared with a direct, single alignment step approach. Furthermore, by approximating the feature distribution for the source domain with a generative adversarial network, the deployment module can be rendered fully independent of retaining potentially large amounts of the related source training data for only a minor reduction in performance.

##### Abstract (translated by Google)
持续的外观变化，例如天气和照明条件的变化，可能会影响部署的机器学习模型的性能。虽然无监督域适应旨在解决这一挑战，但目前的方法并未利用发生的移位的连续性。特别是，许多机器人应用程序表现出这些条件，因此有助于通过随着时间的推移整合大量差异的小变化来增加适应学习模型的潜力。我们的工作提出了一种针对终身增量领域适应的对抗方法，该方法从无监督对齐到一系列中间领域，这些中间领域与标记的源领域相继出现分歧。我们凭经验证明，我们的渐进式方法改善了对大的外观变化的处理，例如，与直接的单一对齐步骤方法相比，在可穿越路径分割任务上每天到每晚。此外，通过使用生成对抗网络来逼近源域的特征分布，可以使得部署模块完全独立于保留可能大量的相关源训练数据而仅仅是性能的轻微降低。

##### URL
[http://arxiv.org/abs/1712.07436](http://arxiv.org/abs/1712.07436)

##### PDF
[http://arxiv.org/pdf/1712.07436](http://arxiv.org/pdf/1712.07436)

