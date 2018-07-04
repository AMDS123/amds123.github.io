---
layout: post
title: "Modular Vehicle Control for Transferring Semantic Information to Unseen Weather Conditions using GANs"
date: 2018-07-03 07:29:19
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Face
author: Patrick Wenzel, Qadeer Khan, Daniel Cremers, Laura Leal-Taixé
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end supervised learning has shown promising results for self-driving cars, particularly under conditions for which it was trained. However, it may not necessarily perform well under unseen conditions. In this paper, we demonstrate how knowledge can be transferred from one weather condition for which semantic labels and steering commands are available to a completely new set of conditions for which we have no access to labeled data. The problem is addressed by dividing the task of vehicle control into independent perception and control modules, such that changing one does not affect the other. We train the control module only on the data for the available condition and keep it fixed even under new conditions. The perception module is then used as an interface between the new weather conditions and this control model. The perception module in turn is trained using semantic labels, which we assume are already available for the same weather condition on which the control model was trained. However, obtaining them for other conditions is a tedious and error-prone process. Therefore, we propose to use a generative adversarial network (GAN)-based model to retrieve the semantic information for the new conditions in an unsupervised manner. We introduce a master-servant architecture, where the master model (semantic labels available) trains the servant model (semantic labels not available). The servant model can then be used for steering the vehicle without retraining the control module.

##### Abstract (translated by Google)
端到端监督学习已经为自动驾驶汽车带来了可喜的结果，特别是在训练条件下。但是，在不可见的条件下，它可能不一定表现良好。在本文中，我们演示了如何将知识从一个可用语义标签和转向命令的天气条件转移到一组我们无法访问标记数据的全新条件。通过将车辆控制的任务划分为独立的感知和控制模块来解决该问题，使得改变一个不影响另一个。我们仅根据可用条件的数据训练控制模块，即使在新条件下也能保持固定。然后将感知模块用作新天气条件和该控制模型之间的接口。反过来使用语义标签训练感知模块，我们假设这些语义标签已经可用于训练控制模型的相同天气条件。但是，为其他条件获取它们是一个单调乏味且容易出错的过程。因此，我们建议使用基于生成对抗网络（GAN）的模型以无监督的方式检索新条件的语义信息。我们引入了一个主服务器架构，其中主模型（可用的语义标签）训练服务方模型（语义标签不可用）。然后可以使用仆人模型来转向车辆而无需重新训练控制模块。

##### URL
[https://arxiv.org/abs/1807.01001](https://arxiv.org/abs/1807.01001)

##### PDF
[https://arxiv.org/pdf/1807.01001](https://arxiv.org/pdf/1807.01001)

