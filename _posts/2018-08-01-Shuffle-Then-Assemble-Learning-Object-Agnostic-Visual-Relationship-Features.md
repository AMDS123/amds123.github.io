---
layout: post
title: "Shuffle-Then-Assemble: Learning Object-Agnostic Visual Relationship Features"
date: 2018-08-01 05:20:28
categories: arXiv_CV
tags: arXiv_CV Relation
author: Xu Yang, Hanwang Zhang, Jianfei Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the fact that it is prohibitively expensive to completely annotate visual relationships, i.e., the (obj1, rel, obj2) triplets, relationship models are inevitably biased to object classes of limited pairwise patterns, leading to poor generalization to rare or unseen object combinations. Therefore, we are interested in learning object-agnostic visual features for more generalizable relationship models. By "agnostic", we mean that the feature is less likely biased to the classes of paired objects. To alleviate the bias, we propose a novel \texttt{Shuffle-Then-Assemble} pre-training strategy. First, we discard all the triplet relationship annotations in an image, leaving two unpaired object domains without obj1-obj2 alignment. Then, our feature learning is to recover possible obj1-obj2 pairs. In particular, we design a cycle of residual transformations between the two domains, to capture shared but not object-specific visual patterns. Extensive experiments on two visual relationship benchmarks show that by using our pre-trained features, naive relationship models can be consistently improved and even outperform other state-of-the-art relationship models. Code has been made available at: \url{this https URL}.

##### Abstract (translated by Google)
由于完全注释视觉关系（即obj1，rel，obj2）三元组非常昂贵，因此关系模型不可避免地偏向于有限成对模式的对象类，导致对稀有或看不见的对象组合的泛化不足。因此，我们感兴趣的是学习与对象无关的视觉特征，以获得更广泛的关系模型。通过“不可知”，我们的意思是该特征不太可能偏向于成对对象的类。为了减轻这种偏见，我们提出了一种新颖的\ texttt {Shuffle-Then-Assemble}预训练策略。首先，我们丢弃图像中的所有三元组关系注释，留下两个不成对的对象域，没有obj1-obj2对齐。然后，我们的特征学习是恢复可能的obj1-obj2对。特别是，我们设计了两个域之间的残差变换周期，以捕获共享但不是特定于对象的视觉模式。对两个视觉关系基准的广泛实验表明，通过使用我们预先训练的特征，天真的关系模型可以不断改进，甚至优于其他最先进的关系模型。代码已在以下网址提供：\ url {此https网址}。

##### URL
[https://arxiv.org/abs/1808.00171](https://arxiv.org/abs/1808.00171)

##### PDF
[https://arxiv.org/pdf/1808.00171](https://arxiv.org/pdf/1808.00171)

