---
layout: post
title: "Attribute And-Or Grammar for Joint Parsing of Human Attributes, Part and Pose"
date: 2016-07-07 20:10:52
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction Detection Relation
author: Seyoung Park, Bruce Xiaohan Nie, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an attribute and-or grammar (A-AOG) model for jointly inferring human body pose and human attributes in a parse graph with attributes augmented to nodes in the hierarchical representation. In contrast to other popular methods in the current literature that train separate classifiers for poses and individual attributes, our method explicitly represents the decomposition and articulation of body parts, and account for the correlations between poses and attributes. The A-AOG model is an amalgamation of three traditional grammar formulations: (i) Phrase structure grammar representing the hierarchical decomposition of the human body from whole to parts; (ii) Dependency grammar modeling the geometric articulation by a kinematic graph of the body pose; and (iii) Attribute grammar accounting for the compatibility relations between different parts in the hierarchy so that their appearances follow a consistent style. The parse graph outputs human detection, pose estimation, and attribute prediction simultaneously, which are intuitive and interpretable. We conduct experiments on two tasks on two datasets, and experimental results demonstrate the advantage of joint modeling in comparison with computing poses and attributes independently. Furthermore, our model obtains better performance over existing methods for both pose estimation and attribute prediction tasks.

##### Abstract (translated by Google)
本文提出了一个属性和语法（A-AOG）模型，用于在一个解析图中联合推断人体姿态和人体属性，属性增加到层次表示中的节点。与当前文献中为姿势和个体属性训练单独分类器的其他流行方法相比，我们的方法明确地表示了身体部位的分解和关联，并且说明了姿势和属性之间的相关性。 A-AOG模型是三种传统语法的组合：（i）短语结构语法，表示人体从整体到部分的分层分解; （ii）依靠身体姿态的运动图形建立几何关节的依赖语法; （3）属性文法考虑层次结构中不同部分之间的兼容性关系，以使其外观遵循一致的风格。解析图同时输出人体检测，姿态估计和属性预测，这些都是直观和可解释的。我们对两个数据集上的两个任务进行了实验，实验结果证明了联合建模与独立计算姿态和属性的优势。此外，我们的模型在姿态估计和属性预测任务方面比现有方法获得更好的性能。

##### URL
[https://arxiv.org/abs/1605.02112](https://arxiv.org/abs/1605.02112)

##### PDF
[https://arxiv.org/pdf/1605.02112](https://arxiv.org/pdf/1605.02112)

