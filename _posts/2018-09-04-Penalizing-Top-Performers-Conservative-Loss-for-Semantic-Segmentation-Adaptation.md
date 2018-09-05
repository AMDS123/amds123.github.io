---
layout: post
title: "Penalizing Top Performers: Conservative Loss for Semantic Segmentation Adaptation"
date: 2018-09-04 11:50:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Gradient_Descent
author: Xinge Zhu, Hui Zhou, Ceyuan Yang, Jianping Shi, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the expensive and time-consuming annotations (e.g., segmentation) for real-world images, recent works in computer vision resort to synthetic data. However, the performance on the real image often drops significantly because of the domain shift between the synthetic data and the real images. In this setting, domain adaptation brings an appealing option. The effective approaches of domain adaptation shape the representations that (1) are discriminative for the main task and (2) have good generalization capability for domain shift. To this end, we propose a novel loss function, i.e., Conservative Loss, which penalizes the extreme good and bad cases while encouraging the moderate examples. More specifically, it enables the network to learn features that are discriminative by gradient descent and are invariant to the change of domains via gradient ascend method. Extensive experiments on synthetic to real segmentation adaptation show our proposed method achieves state of the art results. Ablation studies give more insights into properties of the Conservative Loss. Exploratory experiments and discussion demonstrate that our Conservative Loss has good flexibility rather than restricting an exact form.

##### Abstract (translated by Google)
由于用于真实世界图像的昂贵且耗时的注释（例如，分割），计算机视觉中的近期工作采用合成数据。然而，由于合成数据和真实图像之间的域移位，实际图像上的性能经常显着下降。在此设置中，域适应带来了吸引人的选择。域自适应的有效方法形成了以下表示：（1）对主要任务具有判别性;（2）具有良好的域移位泛化能力。为此，我们提出了一种新的损失函数，即保守损失，它在惩罚极端好坏的情况下，同时鼓励适度的例子。更具体地说，它使网络能够通过梯度下降来学习通过梯度下降来区分的特征，并且通过梯度上升方法对域的变化是不变的。对合成到真实分割自适应的广泛实验表明，我们提出的方法实现了最先进的结果。消融研究可以更深入地了解保守治疗损失的特征。探索性实验和讨论表明，我们的保守损失具有良好的灵活性，而不是限制一个确切的形式。

##### URL
[http://arxiv.org/abs/1809.00903](http://arxiv.org/abs/1809.00903)

##### PDF
[http://arxiv.org/pdf/1809.00903](http://arxiv.org/pdf/1809.00903)

