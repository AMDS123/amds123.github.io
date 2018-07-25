---
layout: post
title: "An argument in favor of strong scaling for deep neural networks with small datasets"
date: 2018-07-24 14:48:19
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning Recommendation
author: Renato L. de F. Cunha, Eduardo R. Rodrigues, Matheus Palhares Viana, Dario Augusto Borges Oliveira
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, with the popularization of deep learning frameworks and large datasets, researchers have started parallelizing their models in order to train faster. This is crucially important, because they typically explore many hyperparameters in order to find the best ones for their applications. This process is time consuming and, consequently, speeding up training improves productivity. One approach to parallelize deep learning models followed by many researchers is based on weak scaling. The minibatches increase in size as new GPUs are added to the system. In addition, new learning rates schedules have been proposed to fix optimization issues that occur with large minibatch sizes. In this paper, however, we show that the recommendations provided by recent work do not apply to models that lack large datasets. In fact, we argument in favor of using strong scaling for achieving reliable performance in such cases. We evaluated our approach with up to 32 GPUs and show that weak scaling not only does not have the same accuracy as the sequential model, it also fails to converge most of time. Meanwhile, strong scaling has good scalability while having exactly the same accuracy of a sequential implementation.

##### Abstract (translated by Google)
近年来，随着深度学习框架和大型数据集的普及，研究人员开始对其模型进行并行化以便更快地进行训练。这一点至关重要，因为它们通常会探索许多超参数，以便为其应用找到最佳的参数。这个过程非常耗时，因此加快培训可以提高生产率。许多研究人员遵循的并行化深度学习模型的一种方法是基于弱缩放。随着新GPU添加到系统中，小型机的尺寸会增加。此外，还提出了新的学习率计划，以修复大型小批量大小时出现的优化问题。然而，在本文中，我们表明最近工作提供的建议不适用于缺乏大数据集的模型。实际上，我们支持使用强扩展来实现这种情况下的可靠性能。我们使用多达32个GPU评估了我们的方法，并表明弱缩放不仅不具有与顺序模型相同的精度，而且大多数时间也无法收敛。同时，强大的扩展具有良好的可扩展性，同时具有与顺序实现完全相同的精度。

##### URL
[https://arxiv.org/abs/1807.09161](https://arxiv.org/abs/1807.09161)

##### PDF
[https://arxiv.org/pdf/1807.09161](https://arxiv.org/pdf/1807.09161)

