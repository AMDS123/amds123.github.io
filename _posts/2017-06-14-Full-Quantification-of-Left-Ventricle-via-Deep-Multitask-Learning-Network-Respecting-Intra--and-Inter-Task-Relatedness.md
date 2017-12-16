---
layout: post
title: "Full Quantification of Left Ventricle via Deep Multitask Learning Network Respecting Intra- and Inter-Task Relatedness"
date: 2017-06-14 16:12:49
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding CNN RNN Classification Prediction
author: Wufeng Xue, Andrea Lum, Ashley Mercado, Mark Landis, James Warringto, Shuo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac left ventricle (LV) quantification is among the most clinically important tasks for identification and diagnosis of cardiac diseases, yet still a challenge due to the high variability of cardiac structure and the complexity of temporal dynamics. Full quantification, i.e., to simultaneously quantify all LV indices including two areas (cavity and myocardium), six regional wall thicknesses (RWT), three LV dimensions, and one cardiac phase, is even more challenging since the uncertain relatedness intra and inter each type of indices may hinder the learning procedure from better convergence and generalization. In this paper, we propose a newly-designed multitask learning network (FullLVNet), which is constituted by a deep convolution neural network (CNN) for expressive feature embedding of cardiac structure; two followed parallel recurrent neural network (RNN) modules for temporal dynamic modeling; and four linear models for the final estimation. During the final estimation, both intra- and inter-task relatedness are modeled to enforce improvement of generalization: 1) respecting intra-task relatedness, group lasso is applied to each of the regression tasks for sparse and common feature selection and consistent prediction; 2) respecting inter-task relatedness, three phase-guided constraints are proposed to penalize violation of the temporal behavior of the obtained LV indices. Experiments on MR sequences of 145 subjects show that FullLVNet achieves high accurate prediction with our intra- and inter-task relatedness, leading to MAE of 190mm$^2$, 1.41mm, 2.68mm for average areas, RWT, dimensions and error rate of 10.4\% for the phase classification. This endows our method a great potential in comprehensive clinical assessment of global, regional and dynamic cardiac function.

##### Abstract (translated by Google)
心脏左心室（LV）定量是鉴别和诊断心脏病最重要的临床任务之一，但由于心脏结构的高度可变性和时间动态的复杂性，仍然是一个挑战。全量化，即同时量化包括两个区域（腔和心肌），六个局部壁厚度（RWT），三个LV维度和一个心脏相位的所有LV指标，由于每种类型的内部和内部的不确定性相关性的指标可能会阻碍学习过程的更好的融合和泛化。在本文中，我们提出了一个新的设计的多任务学习网络（FullLVNet），它是由深层卷积神经网络（CNN）构成的表达性的心脏结构特征嵌入;两个随后的并行递归神经网络（RNN）模块用于时间动态建模;和四个线性模型进行最终估计。在最后的估计中，任务内和任务间的相关性都被建模来加强泛化的改进：1）尊重任务内相关性，对每个回归任务应用组套索进行稀疏和共同特征选择和一致性预测; 2）尊重任务间的相关性，提出了三个阶段性的约束条件来惩罚违反获得的LV指数的时间行为。实验结果表明，FullLVNet在任务内部和任务间的相关性达到了很高的预测精度，平均面积为190mm2，平均面积为1.41mm，平均面积为2.68mm，RWT的尺寸和误差率10.4％的相分类。这使我们的方法在整体，局部和动态心脏功能综合临床评估方面具有巨大的潜力。

##### URL
[https://arxiv.org/abs/1706.01912](https://arxiv.org/abs/1706.01912)

##### PDF
[https://arxiv.org/pdf/1706.01912](https://arxiv.org/pdf/1706.01912)

