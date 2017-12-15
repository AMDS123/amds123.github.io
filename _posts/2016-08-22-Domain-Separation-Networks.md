---
layout: post
title: "Domain Separation Networks"
date: 2016-08-22 00:12:27
categories: arXiv_CV
tags: arXiv_CV Image_Caption
author: Konstantinos Bousmalis, George Trigeorgis, Nathan Silberman, Dilip Krishnan, Dumitru Erhan
mathjax: true
---

* content
{:toc}

##### Abstract
The cost of large scale data collection and annotation often makes the application of machine learning algorithms to new tasks or datasets prohibitively expensive. One approach circumventing this cost is training models on synthetic data where annotations are provided automatically. Despite their appeal, such models often fail to generalize from synthetic to real images, necessitating domain adaptation algorithms to manipulate these models before they can be successfully applied. Existing approaches focus either on mapping representations from one domain to the other, or on learning to extract features that are invariant to the domain from which they were extracted. However, by focusing only on creating a mapping or shared representation between the two domains, they ignore the individual characteristics of each domain. We suggest that explicitly modeling what is unique to each domain can improve a model's ability to extract domain-invariant features. Inspired by work on private-shared component analysis, we explicitly learn to extract image representations that are partitioned into two subspaces: one component which is private to each domain and one which is shared across domains. Our model is trained not only to perform the task we care about in the source domain, but also to use the partitioned representation to reconstruct the images from both domains. Our novel architecture results in a model that outperforms the state-of-the-art on a range of unsupervised domain adaptation scenarios and additionally produces visualizations of the private and shared representations enabling interpretation of the domain adaptation process.

##### Abstract (translated by Google)
大规模数据收集和注释的成本通常使得机器学习算法在新任务或数据集上的应用过于昂贵。避免这种成本的一种方法是在合成数据上自动提供注释的训练模型。尽管它们具有吸引力，但是这些模型往往不能从综合到现实的图像进行概括，需要域适应算法来处理这些模型，然后才能成功应用。现有方法的重点是将表示从一个域映射到另一个域，或者学习提取对提取域不变的特征。然而，通过只关注在两个域之间创建映射或共享表示，他们忽略了每个域的个体特征。我们建议明确建模每个域的独特性可以提高模型提取域不变特征的能力。受私人共享组件分析工作的启发，我们明确地学习提取图像表示，这些图像表示被划分为两个子空间：一个是每个域专用的组件，另一个是跨域共享的组件。我们的模型不仅被训练来执行我们在源域中关心的任务，而且还使用分区表示重构来自两个域的图像。我们的新颖架构产生的模型在一系列无监督的域适应场景中胜过最先进的技术，并且还生成私有和共享表示的可视化，从而能够解释域适应过程。

##### URL
[https://arxiv.org/abs/1608.06019](https://arxiv.org/abs/1608.06019)

##### PDF
[https://arxiv.org/pdf/1608.06019](https://arxiv.org/pdf/1608.06019)

