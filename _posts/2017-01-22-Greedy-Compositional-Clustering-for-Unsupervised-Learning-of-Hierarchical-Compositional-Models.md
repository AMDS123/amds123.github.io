---
layout: post
title: "Greedy Compositional Clustering for Unsupervised Learning of Hierarchical Compositional Models"
date: 2017-01-22 14:56:31
categories: arXiv_CV
tags: arXiv_CV
author: Adam Kortylewski, Clemens Blumer, Thomas Vetter
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes to integrate a feature pursuit learning process into a greedy bottom-up learning scheme. The algorithm combines the benefits of bottom-up and top-down approaches for learning hierarchical models: It allows to induce the hierarchical structure of objects in an unsupervised manner, while avoiding a hard decision on the activation of parts. We follow the principle of compositionality by assembling higher-order parts from elements of lower layers in the hierarchy. The parts are learned greedily with an EM-type process that iterates between image encoding and part re-learning. The process stops when a candidate part is not able to find a free niche in the image. The algorithm proceeds layer by layer in a bottom-up manner until no further compositions are found. A subsequent top-down process composes the learned hierarchical shape vocabulary into a holistic object model. Experimental evaluation of the approach shows state-of-the-art performance on a domain adaptation task. Moreover, we demonstrate the capability of learning complex, semantically meaningful hierarchical compositional models without supervision.

##### Abstract (translated by Google)
本文提出将特征追踪学习过程整合到一个贪婪的自下而上的学习方案中。该算法结合了自下而上和自上而下的方法学习层次模型的好处：它允许以无监督的方式诱发对象的层次结构，同时避免对部件激活的困难决策。我们遵循组合性的原则，通过组合层次中较低层元素的高阶部分。贪婪地学习零件，在图像编码和零件重新学习之间进行迭代。当候选部分不能在图像中找到空闲位置时，该过程停止。该算法以自下而上的方式逐层进行，直到找不到进一步的组合。随后的自上而下的过程将学习的分层形状词汇组合成整体对象模型。该方法的实验评估显示了领域适应任务的最新性能。此外，我们展示了在没有监督的情况下学习复杂的，语义上有意义的层次组合模型的能力。

##### URL
[https://arxiv.org/abs/1701.06171](https://arxiv.org/abs/1701.06171)

##### PDF
[https://arxiv.org/pdf/1701.06171](https://arxiv.org/pdf/1701.06171)

