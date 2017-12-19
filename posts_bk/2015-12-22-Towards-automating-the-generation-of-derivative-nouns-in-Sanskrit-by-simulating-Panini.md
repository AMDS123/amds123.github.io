---
layout: post
title: "Towards automating the generation of derivative nouns in Sanskrit by simulating Panini"
date: 2015-12-22 10:07:35
categories: arXiv_CL
tags: arXiv_CL Relation
author: Amrith Krishna, Pawan Goyal
mathjax: true
---

* content
{:toc}

##### Abstract
About 1115 rules in Astadhyayi from A.4.1.76 to A.5.4.160 deal with generation of derivative nouns, making it one of the largest topical sections in Astadhyayi, called as the Taddhita section owing to the head rule A.4.1.76. This section is a systematic arrangement of rules that enumerates various affixes that are used in the derivation under specific semantic relations. We propose a system that automates the process of generation of derivative nouns as per the rules in Astadhyayi. The proposed system follows a completely object oriented approach, that models each rule as a class of its own and then groups them as rule groups. The rule groups are decided on the basis of selective grouping of rules by virtue of anuvrtti. The grouping of rules results in an inheritance network of rules which is a directed acyclic graph. Every rule group has a head rule and the head rule notifies all the direct member rules of the group about the environment which contains all the details about data entities, participating in the derivation process. The system implements this mechanism using multilevel inheritance and observer design patterns. The system focuses not only on generation of the desired final form, but also on the correctness of sequence of rules applied to make sure that the derivation has taken place in strict adherence to Astadhyayi. The proposed system's design allows to incorporate various conflict resolution methods mentioned in authentic texts and hence the effectiveness of those rules can be validated with the results from the system. We also present cases where we have checked the applicability of the system with the rules which are not specifically applicable to derivation of derivative nouns, in order to see the effectiveness of the proposed schema as a generic system for modeling Astadhyayi.

##### Abstract (translated by Google)
在Astadhyayi中，从A.4.1.76到A.5.4.160约1115条规则处理衍生名词的产生，使其成为Astadhyayi中最大的专题章节之一，因头规则A.4.1.76而被称为Taddhita章节。这部分是一个规则的系统安排，列举了在特定语义关系下派生的各种词缀。根据Astadhyayi中的规则，我们提出了一个自动生成派生名词的过程。所提出的系统遵循完全面向对象的方法，其将每个规则建模为它自己的一个类，然后将它们分组为规则组。规则小组是根据anuvrtti选择规则分组的基础上决定的。规则分组产生一个规则的继承网络，它是一个有向无环图。每个规则组都有一个首标规则，首标规​​则通知组中所有关于环境的直接成员规则，其中包含有关数据实体的所有细节，参与推导过程。系统使用多级继承和观察者设计模式来实现这个机制。该系统不仅关注所期望的最终形式的产生，而且关注应用规则的顺序的正确性，以确保推导发生在严格遵守Astadhyayi。所提出的系统的设计允许合并在真实文本中提到的各种冲突解决方法，因此这些规则的有效性可以通过系统的结果来验证。我们还介绍了一些情况，我们已经检查了系统的适用性，这些规则不适用于派生衍生名词，以便将所提出的模式作为一个通用的Astadhyayi建模系统的有效性。

##### URL
[https://arxiv.org/abs/1512.05670](https://arxiv.org/abs/1512.05670)

##### PDF
[https://arxiv.org/pdf/1512.05670](https://arxiv.org/pdf/1512.05670)

