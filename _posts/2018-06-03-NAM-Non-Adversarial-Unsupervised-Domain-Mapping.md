---
layout: post
title: "NAM: Non-Adversarial Unsupervised Domain Mapping"
date: 2018-06-03 14:53:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Relation
author: Yedid Hoshen, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
Several methods were recently proposed for the task of translating images between domains without prior knowledge in the form of correspondences. The existing methods apply adversarial learning to ensure that the distribution of the mapped source domain is indistinguishable from the target domain, which suffers from known stability issues. In addition, most methods rely heavily on "cycle" relationships between the domains, which enforce a one-to-one mapping. In this work, we introduce an alternative method: Non-Adversarial Mapping (NAM), which separates the task of target domain generative modeling from the cross-domain mapping task. NAM relies on a pre-trained generative model of the target domain, and aligns each source image with an image synthesized from the target domain, while jointly optimizing the domain mapping function. It has several key advantages: higher quality and resolution image translations, simpler and more stable training and reusable target models. Extensive experiments are presented validating the advantages of our method.

##### Abstract (translated by Google)
最近提出了几种方法来完成域之间的图像翻译任务，而事先不了解信函的形式。现有的方法应用敌对学习来确保映射源域的分布与目标域的分布不可区分，而目标域存在已知的稳定性问题。另外，大多数方法严重依赖于域之间的“循环”关系，这实现了一对一的映射。在这项工作中，我们引入了另一种方法：非对抗映射（NAM），它将目标域生成建模的任务从跨域映射任务中分离出来。 NAM依赖于目标域的预先训练的生成模型，并将每个源图像与从目标域合成的图像对齐，同时联合优化域映射功能。它有几个关键优势：更高质量和更高分辨率的图像翻译，更简单，更稳定的培训和可重复使用的目标模型。提出了大量的实验来验证我们方法的优点。

##### URL
[http://arxiv.org/abs/1806.00804](http://arxiv.org/abs/1806.00804)

##### PDF
[http://arxiv.org/pdf/1806.00804](http://arxiv.org/pdf/1806.00804)

