---
layout: post
title: "Predicting Organic Reaction Outcomes with Weisfeiler-Lehman Network"
date: 2017-12-29 16:31:51
categories: arXiv_AI
tags: arXiv_AI GAN Prediction
author: Wengong Jin, Connor W. Coley, Regina Barzilay, Tommi Jaakkola
mathjax: true
---

* content
{:toc}

##### Abstract
The prediction of organic reaction outcomes is a fundamental problem in computational chemistry. Since a reaction may involve hundreds of atoms, fully exploring the space of possible transformations is intractable. The current solution utilizes reaction templates to limit the space, but it suffers from coverage and efficiency issues. In this paper, we propose a template-free approach to efficiently explore the space of product molecules by first pinpointing the reaction center -- the set of nodes and edges where graph edits occur. Since only a small number of atoms contribute to reaction center, we can directly enumerate candidate products. The generated candidates are scored by a Weisfeiler-Lehman Difference Network that models high-order interactions between changes occurring at nodes across the molecule. Our framework outperforms the top-performing template-based approach with a 10\% margin, while running orders of magnitude faster. Finally, we demonstrate that the model accuracy rivals the performance of domain experts.

##### Abstract (translated by Google)
有机反应结果的预测是计算化学中的一个基本问题。由于反应可能涉及数百个原子，因此充分探索可能的转换空间是棘手的。目前的解决方案利用反应模板来限制空间，但是其受到覆盖和效率问题的影响。在本文中，我们提出了一种无模板方法，通过首先确定反应中心 - 图形编辑发生的节点和边缘集合，有效地探索产品分子的空间。由于只有少量的原子参与反应中心，所以可以直接列举候选产物。所产生的候选者通过Weisfeiler-Lehman差异网络进行评分，该差异网络对在分子上的节点处发生的变化之间的高阶相互作用进行建模。我们的框架优于基于模板的性能最高的方法，并且运行速度提高了10％。最后，我们证明模型的准确性可以与领域专家的表现相媲美。

##### URL
[http://arxiv.org/abs/1709.04555](http://arxiv.org/abs/1709.04555)

##### PDF
[http://arxiv.org/pdf/1709.04555](http://arxiv.org/pdf/1709.04555)

