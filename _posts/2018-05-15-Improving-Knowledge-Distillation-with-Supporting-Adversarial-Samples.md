---
layout: post
title: "Improving Knowledge Distillation with Supporting Adversarial Samples"
date: 2018-05-15 02:42:40
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge
author: Byeongho Heo, Minsik Lee, Sangdoo Yun, Jin Young Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Many recent works on knowledge distillation have provided ways to transfer the knowledge of a trained network for improving the learning process of a new one, but finding a good technique for knowledge distillation is still an open problem. In this paper, we provide a new perspective based on a decision boundary, which is one of the most important component of a classifier. The generalization performance of a classifier is closely related to the adequacy of its decision boundaries, so a good classifier bears good decision boundaries. Therefore, transferring the boundaries directly can be a good attempt for knowledge distillation. To realize this goal, we utilize an adversarial attack to discover samples supporting the decision boundaries. Based on this idea, to transfer more accurate information about the decision boundaries, the proposed algorithm trains a student classifier based on the adversarial samples supporting the decision boundaries. Alongside, two metrics are proposed to evaluate the similarity between decision boundaries. Experiments show that the proposed method indeed improves knowledge distillation and produces much more similar decision boundaries to the teacher classifier.

##### Abstract (translated by Google)
最近许多关于知识蒸馏的研究提供了转移培训网络的知识以改进新知识的学习过程的方法，但是找到一种用于知识蒸馏的好技术仍然是一个悬而未决的问题。在本文中，我们提供了一个基于决策边界的新观点，决策边界是分类器最重要的组成部分之一。分类器的泛化性能与其决策边界的充分性密切相关，所以好的分类器具有良好的决策边界。因此，直接转移边界可能是知识蒸馏的良好尝试。为了实现这个目标，我们利用敌对攻击来发现支持决策边界的样本。基于这个想法，为了传递更准确的决策边界信息，该算法根据支持决策边界的敌对样本训练学生分类器。除此之外，还提出了两个度量来评估决策边界之间的相似度。实验表明，所提出的方法确实提高了知识的蒸馏，并产生了更多类似于教师分类器的决策边界。

##### URL
[http://arxiv.org/abs/1805.05532](http://arxiv.org/abs/1805.05532)

##### PDF
[http://arxiv.org/pdf/1805.05532](http://arxiv.org/pdf/1805.05532)

