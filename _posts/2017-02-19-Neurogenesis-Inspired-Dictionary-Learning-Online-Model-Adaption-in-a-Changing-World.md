---
layout: post
title: "Neurogenesis-Inspired Dictionary Learning: Online Model Adaption in a Changing World"
date: 2017-02-19 08:15:55
categories: arXiv_AI
tags: arXiv_AI Regularization Sparse Represenation_Learning Optimization
author: Sahil Garg, Irina Rish, Guillermo Cecchi, Aurelie Lozano
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on online representation learning in non-stationary environments which may require continuous adaptation of model architecture. We propose a novel online dictionary-learning (sparse-coding) framework which incorporates the addition and deletion of hidden units (dictionary elements), and is inspired by the adult neurogenesis phenomenon in the dentate gyrus of the hippocampus, known to be associated with improved cognitive function and adaptation to new environments. In the online learning setting, where new input instances arrive sequentially in batches, the neuronal-birth is implemented by adding new units with random initial weights (random dictionary elements); the number of new units is determined by the current performance (representation error) of the dictionary, higher error causing an increase in the birth rate. Neuronal-death is implemented by imposing l1/l2-regularization (group sparsity) on the dictionary within the block-coordinate descent optimization at each iteration of our online alternating minimization scheme, which iterates between the code and dictionary updates. Finally, hidden unit connectivity adaptation is facilitated by introducing sparsity in dictionary elements. Our empirical evaluation on several real-life datasets (images and language) as well as on synthetic data demonstrates that the proposed approach can considerably outperform the state-of-art fixed-size (nonadaptive) online sparse coding of Mairal et al. (2009) in the presence of nonstationary data. Moreover, we identify certain properties of the data (e.g., sparse inputs with nearly non-overlapping supports) and of the model (e.g., dictionary sparsity) associated with such improvements.

##### Abstract (translated by Google)
在本文中，我们关注在非静态环境中的在线表示学习，这可能需要模型架构的不断适应。我们提出了一种新的在线字典学习（稀疏编码）框架，其中包含隐藏单元（字典元素）的添加和删除，并且受到海马齿状回中成人神经发生现象的启发，已知与改善认知功能和适应新的环境。在在线学习设置中，新输入实例按批次顺序到达，神经元出生是通过添加具有随机初始权重的新单元（随机字典元素）来实现的。新单位的数量由字典的当前性能（表示错误）决定，导致出生率增加的更高的错误。在我们的在线交替最小化方案的每次迭代中的块坐标下降优化中，通过在字典上施加l1 / l2正则化（群稀疏性）来实现神经元死亡，其在代码和字典更新之间进行迭代。最后，通过在字典元素中引入稀疏来促进隐藏的单元连接适配。我们对几个实际数据集（图像和语言）以及合成数据的实证评估表明，所提出的方法可以显着地胜过Mairal等人的现有技术的固定大小（非适应性）在线稀疏编码。 （2009）存在非稳态数据。此外，我们识别与这些改进相关的数据的某些属性（例如，具有几乎不重叠支持的稀疏输入）和模型（例如，字典稀疏性）。

##### URL
[http://arxiv.org/abs/1701.06106](http://arxiv.org/abs/1701.06106)

##### PDF
[http://arxiv.org/pdf/1701.06106](http://arxiv.org/pdf/1701.06106)

