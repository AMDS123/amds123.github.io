---
layout: post
title: "Incremental Adversarial Domain Adaptation"
date: 2017-12-20 12:08:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation
author: Markus Wulfmeier, Alex Bewley, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
Continuous appearance shifts such as changes in weather and lighting conditions can impact the performance of deployed machine learning models. Unsupervised domain adaptation aims to address this challenge, though current approaches do not utilise the continuity of the occurring shifts. Many robotic applications exhibit these conditions and thus facilitate the potential to incrementally adapt a learnt model over minor shifts which integrate to massive differences over time. Our work presents an adversarial approach for lifelong, incremental domain adaptation which benefits from unsupervised alignment to a series of sub-domains which successively diverge from the labelled source domain. We demonstrate on a drivable-path segmentation task that our incremental approach can better handle large appearance changes, e.g. day to night, compared with a prior single alignment step approach. Furthermore, by approximating the marginal feature distribution for the source domain with a generative adversarial network, the deployment module can be rendered fully independent of retaining potentially large amounts of the related source training data for only a minor reduction in performance.

##### Abstract (translated by Google)
连续的外观变化，如天气和照明条件的变化，可能会影响部署的机器学习模型的性能。无监督的领域适应旨在解决这一挑战，尽管目前的方法不利用发生的变化的连续性。许多机器人应用程序展现了这些条件，从而有助于通过随着时间的推移整合到巨大差异的小变化而逐渐适应学习模型的潜力。我们的工作提出了一个终身的，增量领域适应的对抗方法，从无监督的对齐到一系列子域，从标记的源域陆续发散。我们在可驱动路径分割任务上展示了我们的增量方法可以更好地处理大的外观变化，例如，与之前的单一对准步骤方法相比，此外，通过使用生成对抗网络来逼近源域的边际特征分布，可以使得部署模块完全独立于保留潜在的大量相关源训练数据，而仅仅使性能略微降低。

##### URL
[https://arxiv.org/abs/1712.07436](https://arxiv.org/abs/1712.07436)

##### PDF
[https://arxiv.org/pdf/1712.07436](https://arxiv.org/pdf/1712.07436)

