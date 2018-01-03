---
layout: post
title: "Domain Adaptation Meets Disentangled Representation Learning and Style Transfer"
date: 2018-01-01 13:32:55
categories: arXiv_CV
tags: arXiv_CV Adversarial Style_Transfer Transfer_Learning Represenation_Learning
author: Hoang Tran Vu, Ching-Chun Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In order to solve the unsupervised domain adaptation problem, some methods based on adversarial learning are proposed recently. These methods greatly attract people's eyes because of the better ability to learn the common representation space so that the feature distributions among many domains are ambiguous and non-discriminative. Although there are many discussions and results, the success of the methods implicitly funds on the assumption that the information of domains are fully transferrable. If the assumption is not satisfied, the influence of negative transfer may degrade domain adaptation. In this paper, we proposed to relieve the negative effects by not only adversarial learning but also disentangled representation learning, and style transfer. In detail, our architecture disentangles the learned features into common parts and specific parts. The common parts represent the transferrable feature space, whereas the specific parts characterize the unique style of each individual domain. Moreover, we proposed to exchange specific feature parts across domains for image style transfer. These designs allow us to introduce five types of novel training objectives to enhance domain adaptation and realize style transfer. In our experiments, we evaluated domain adaptation on two standard digit data sets. The results show that our architecture can be adaptive well to full transfer learning and partial transfer learning. As a side product, the trained network also demonstrates high potential to generate style-transferred images.

##### Abstract (translated by Google)
为了解决无监督领域适应问题，最近提出了一些基于对抗学习的方法。这些方法由于学习共同表示空间的能力较强，因此很大程度上吸引了人们的眼球，使得多个领域间的特征分布模棱两可，无差别。虽然有许多讨论和结果，但方法的成功隐含地基于假设域的信息是完全可转移的资金。如果假设不满意，负转移的影响可能会降低域的适应性。在这篇论文中，我们提出了除了对抗性学习，还有解题表征学习，风格转移等方面的消极作用。详细地说，我们的架构将学习的功能分解成通用部分和特定部分。通用部分表示可传递的特征空间，而具体部分表征每个单独域的独特风格。此外，我们建议在域之间交换特定的功能部件以进行图像样式转换。这些设计使我们能够引入五类新颖的培训目标，以加强领域适应和实现风格转移。在我们的实验中，我们评估了两个标准数字数据集的域适配。结果表明，我们的架构可以很好地适应全迁移学习和部分迁移学习。作为一个副产品，训练有素的网络也显示出产生风格转换图像的巨大潜力。

##### URL
[https://arxiv.org/abs/1712.09025](https://arxiv.org/abs/1712.09025)

##### PDF
[https://arxiv.org/pdf/1712.09025](https://arxiv.org/pdf/1712.09025)

