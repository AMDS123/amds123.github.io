---
layout: post
title: "Visual Representations for Semantic Target Driven Navigation"
date: 2018-05-15 23:26:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Arsalan Mousavian, Alexander Toshev, Marek Fiser, Jana Kosecka, James Davidson
mathjax: true
---

* content
{:toc}

##### Abstract
What is a good visual representation for autonomous agents? We address this question in the context of semantic visual navigation, which is the problem of a robot finding its way through a complex environment to a target object, e.g. go to the refrigerator. Instead of acquiring a metric semantic map of an environment and using planning for navigation, our approach learns navigation policies on top of representations that capture spatial layout and semantic contextual cues. We propose to using high level semantic and contextual features including segmentation and detection masks obtained by off-the-shelf state-of- the-art vision as observations and use deep network to learn the navigation policy. This choice allows using additional data, from orthogonal sources, to better train different parts of the model the representation extraction is trained on large standard vision datasets while the navigation component leverages large synthetic environments for training. This combination of real and synthetic is possible because equitable feature representations are available in both (e.g., segmentation and detection masks), which alleviates the need for domain adaptation. Both the representation and the navigation policy can be readily applied to real non-synthetic environments as demonstrated on the Active Vision Dataset [1]. Our approach gets successfully to the target in 54% of the cases in unexplored environments, compared to 46% for non-learning based approach, and 28% for the learning-based baseline.

##### Abstract (translated by Google)
什么是自主代理的良好视觉表示？我们在语义视觉导航的背景下解决了这个问题，这是机器人在复杂环境中找到目标对象的问题，例如，去冰箱。我们的方法不是获取环境的度量语义映射并使用导航规划，而是在捕获空间布局和语义上下文线索的表示之上学习导航策略。我们建议使用高级语义和上下文特征，包括通过现成的最新视觉获得的分割和检测掩模作为观察，并使用深度网络来学习导航策略。这种选择允许使用来自正交源的附加数据来更好地训练模型的不同部分，表征提取在大标准视觉数据集上训练，而导航组件利用大型合成环境进行训练。真正的和合成的这种组合是可能的，因为公平的特征表示在两个（例如分割和检测掩码）中都是可用的，这减轻了域适应的需要。表示和导航策略都可以很容易地应用到真实的非合成环境中，如Active Vision Dataset [1]所示。我们的方法在未开发环境中成功达到54％的目标，而非基于非学习方法的为46％，基于学习的基线为28％。

##### URL
[http://arxiv.org/abs/1805.06066](http://arxiv.org/abs/1805.06066)

##### PDF
[http://arxiv.org/pdf/1805.06066](http://arxiv.org/pdf/1805.06066)

