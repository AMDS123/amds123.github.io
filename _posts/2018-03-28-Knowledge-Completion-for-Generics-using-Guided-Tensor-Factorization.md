---
layout: post
title: "Knowledge Completion for Generics using Guided Tensor Factorization"
date: 2018-03-28 18:58:58
categories: arXiv_AI
tags: arXiv_AI Knowledge Relation
author: Hanie Sedghi, Ashish Sabharwal
mathjax: true
---

* content
{:toc}

##### Abstract
Given a knowledge base or KB containing (noisy) facts about common nouns or generics, such as "all trees produce oxygen" or "some animals live in forests", we consider the problem of inferring additional such facts at a precision similar to that of the starting KB. Such KBs capture general knowledge about the world, and are crucial for various applications such as question answering. Different from commonly studied named entity KBs such as Freebase, generics KBs involve quantification, have more complex underlying regularities, tend to be more incomplete, and violate the commonly used locally closed world assumption (LCWA). We show that existing KB completion methods struggle with this new task, and present the first approach that is successful. Our results demonstrate that external information, such as relation schemas and entity taxonomies, if used appropriately, can be a surprisingly powerful tool in this setting. First, our simple yet effective knowledge guided tensor factorization approach achieves state-of-the-art results on two generics KBs (80% precise) for science, doubling their size at 74%-86% precision. Second, our novel taxonomy guided, submodular, active learning method for collecting annotations about rare entities (e.g., oriole, a bird) is 6x more effective at inferring further new facts about them than multiple active learning baselines.

##### Abstract (translated by Google)
鉴于知识库或知识库包含有关普通名词或仿制药的（嘈杂的）事实，如“所有树木都会产生氧气”或“有些动物生活在森林中”，我们认为推断额外的这些事实的问题的准确性与起始KB。这样的知识库捕捉关于世界的一般知识，并且对于各种应用（例如问题回答）至关重要。与通常研究的命名实体KB（如Freebase）不同，泛型KB涉及量化，具有更复杂的基本规律，往往更不完整，并且违反了常用的局部封闭世界假设（LCWA）。我们展示了现有的KB完成方法与这项新任务的斗争，并介绍了第一种成功的方法。我们的研究结果表明，外部信息（如关系模式和实体分类法）如果使用得当，可能会成为这种情况下令人惊讶的强大工具。首先，我们简单而有效的知识导向张量分解方法在科学的两个泛型KB（精确度为80％）上实现了最新的结果，其精度以74％-86％的精度加倍。其次，我们新颖的分类学引导，子模块化，主动学习方法收集有关罕见实体（例如，黄鹂，一只鸟）的注释，在推断有关它们的新事实方面比多个主动学习基线更有效6倍。

##### URL
[http://arxiv.org/abs/1612.03871](http://arxiv.org/abs/1612.03871)

##### PDF
[http://arxiv.org/pdf/1612.03871](http://arxiv.org/pdf/1612.03871)

