---
layout: post
title:  'Progressive Neural Architecture Search'
date:   2017-12-05 18:47:33
categories: CV
tags: CV
author: Chenxi Liu, Barret Zoph, Jonathon Shlens, Wei Hua, Li-Jia Li, Li Fei-Fei, Alan Yuille, Jonathan Huang, Kevin Murphy
---

* content
{:toc}

##### Abstract
We propose a method for learning CNN structures that is more efficient than previous approaches: instead of using reinforcement learning (RL) or genetic algorithms (GA), we use a sequential model-based optimization (SMBO) strategy, in which we search for architectures in order of increasing complexity, while simultaneously learning a surrogate function to guide the search, similar to A* search. On the CIFAR-10 dataset, our method finds a CNN structure with the same classification accuracy (3.41% error rate) as the RL method of Zoph et al. (2017), but 2 times faster (in terms of number of models evaluated). It also outperforms the GA method of Liu et al. (2017), which finds a model with worse performance (3.63% error rate), and takes 5 times longer. Finally we show that the model we learned on CIFAR also works well at the task of ImageNet classification. In particular, we match the state-of-the-art performance of 82.9% top-1 and 96.1% top-5 accuracy.

##### Abstract (translated by Google)
我们提出了一种比以前的方法更有效的CNN结构学习方法：我们不是使用强化学习（RL）或遗传算法（GA），而是使用基于序列模型的优化（SMBO）策略，以增加复杂度的顺序，同时学习代理功能来引导搜索，类似于A *搜索。在CIFAR-10数据集上，我们的方法找到了与Zoph等人的RL方法相同的分类准确度（3.41％错误率）的CNN结构。 （2017年），但是速度提高了2倍（以所评估的型号数量计）。它也优于Liu等人的GA方法。 （2017年），发现一个性能较差的模型（错误率为3.63％），需要5倍的时间。最后，我们展示了我们在CIFAR上学习的模型在ImageNet分类的任务中也很有效。尤其是，我们匹配了最高水平的前82.9％和前5名的96.1％的精度。

##### URL
[http://arxiv.org/abs/1712.00559](http://arxiv.org/abs/1712.00559)

