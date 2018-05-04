---
layout: post
title: "Open Set Domain Adaptation by Backpropagation"
date: 2018-04-27 10:16:15
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge
author: Kuniaki Saito, Shohei Yamamoto, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Numerous algorithms have been proposed for transferring knowledge from a label-rich domain (source) to a label-scarce domain (target). Almost all of them are proposed for a closed-set scenario, where the source and the target domain completely share the class of their samples. We call the shared class the \doublequote{known class.} However, in practice, when samples in target domain are not labeled, we cannot know whether the domains share the class. A target domain can contain samples of classes that are not shared by the source domain. We call such classes the \doublequote{unknown class} and algorithms that work well in the open set situation are very practical. However, most existing distribution matching methods for domain adaptation do not work well in this setting because unknown target samples should not be aligned with the source. In this paper, we propose a method for an open set domain adaptation scenario which utilizes adversarial training. A classifier is trained to make a boundary between the source and the target samples whereas a generator is trained to make target samples far from the boundary. Thus, we assign two options to the feature generator: aligning them with source known samples or rejecting them as unknown target samples. This approach allows extracting features that separate unknown target samples from known target samples. Our method was extensively evaluated in domain adaptation setting and outperformed other methods with a large margin in most settings.

##### Abstract (translated by Google)
已经提出了许多用于将知识从标签丰富的域（源）转移到标签稀缺域（目标）的算法。几乎所有这些都是针对封闭场景提出的，其中源域和目标域完全共享样本类。我们称共享类为\ doublequote {known class。}然而，实际上，当目标域中的样本未标记时，我们无法知道域是否共享类。目标域可以包含不由源域共享的类的样本。我们称这样的类为\ doublequote {未知类}，并且在开放设置情况下运行良好的算法非常实用。然而，大多数现有的域匹配分布匹配方法在这种设置下效果不好，因为未知的目标样本不应该与源对齐。在本文中，我们提出了一种利用对抗训练的开放式域名自适应方案。训练分类器以在源样本和目标样本之间建立边界，而训练发生器以使目标样本远离边界。因此，我们为特征生成器分配两个选项：将它们与源已知样本对齐或拒绝它们作为未知目标样本。这种方法允许从已知目标样本中提取分离未知目标样本的特征。我们的方法在领域适应环境中进行了广泛的评估，并且在大多数环境中都优于其他方法。

##### URL
[https://arxiv.org/abs/1804.10427](https://arxiv.org/abs/1804.10427)

##### PDF
[https://arxiv.org/pdf/1804.10427](https://arxiv.org/pdf/1804.10427)

