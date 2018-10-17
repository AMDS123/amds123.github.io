---
layout: post
title: "Policy Transfer with Strategy Optimization"
date: 2018-10-12 22:53:30
categories: arXiv_RO
tags: arXiv_RO Transfer_Learning Optimization
author: Wenhao Yu, C. Karen Liu, Greg Turk
mathjax: true
---

* content
{:toc}

##### Abstract
Computer simulation provides an automatic and safe way for training robotic control policies to achieve complex tasks such as locomotion. However, a policy trained in simulation usually does not transfer directly to the real hardware due to the differences between the two environments. Transfer learning using domain randomization is a promising approach, but it usually assumes that the target environment is close to the distribution of the training environments, thus relying heavily on accurate system identification. In this paper, we present a different approach that leverages domain randomization for transferring control policies to unknown environments. The key idea that, instead of learning a single policy in the simulation, we simultaneously learn a family of policies that exhibit different behaviors. When tested in the target environment, we directly search for the best policy in the family based on the task performance, without the need to identify the dynamic parameters. We evaluate our method on five simulated robotic control problems with different discrepancies in the training and testing environment and demonstrate that our method can overcome larger modeling errors compared to training a robust policy or an adaptive policy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05751](https://arxiv.org/abs/1810.05751)

##### PDF
[https://arxiv.org/pdf/1810.05751](https://arxiv.org/pdf/1810.05751)

