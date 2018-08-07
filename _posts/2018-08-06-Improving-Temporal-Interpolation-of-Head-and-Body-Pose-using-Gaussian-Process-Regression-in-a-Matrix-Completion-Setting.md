---
layout: post
title: "Improving Temporal Interpolation of Head and Body Pose using Gaussian Process Regression in a Matrix Completion Setting"
date: 2018-08-06 12:05:53
categories: arXiv_CV
tags: arXiv_CV Sparse Pose_Estimation
author: Stephanie Tan, Hayley Hung
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a model for head and body pose estimation (HBPE) when labelled samples are highly sparse. The current state-of-the-art multimodal approach to HBPE utilizes the matrix completion method in a transductive setting to predict pose labels for unobserved samples. Based on this approach, the proposed method tackles HBPE when manually annotated ground truth labels are temporally sparse. We posit that the current state of the art approach oversimplifies the temporal sparsity assumption by using Laplacian smoothing. Our final solution uses: i) Gaussian process regression in place of Laplacian smoothing, ii) head and body coupling, and iii) nuclear norm minimization in the matrix completion setting. The model is applied to the challenging SALSA dataset for benchmark against the state-of-the-art method. Our presented formulation outperforms the state-of-the-art significantly in this particular setting, e.g. at 5% ground truth labels as training data, head pose accuracy and body pose accuracy is approximately 62% and 70%, respectively. As well as fitting a more flexible model to missing labels in time, we posit that our approach also loosens the head and body coupling constraint, allowing for a more expressive model of the head and body pose typically seen during conversational interaction in groups. This provides a new baseline to improve upon for future integration of multimodal sensor data for the purpose of HBPE.

##### Abstract (translated by Google)
本文提出了标记样本高度稀疏时头部和身体姿态估计（HBPE）的模型。目前最先进的HBPE多模态方法利用转换设置中的矩阵完成方法来预测未观察样本的姿势标记。基于这种方法，当手动注释的地面实况标签在时间上稀疏时，所提出的方法处理HBPE。我们假设当前的现有技术方法通过使用拉普拉斯平滑来过度简化时间稀疏性假设。我们的最终解决方案使用：i）高斯过程回归代替拉普拉斯平滑，ii）头部和身体耦合，以及iii）矩阵完成设置中的核范数最小化。该模型应用于具有挑战性的SALSA数据集，以针对最先进的方法进行基准测试。我们提出的公式在这个特定的环境中显着优于现有技术，例如：在5％地面实况标签作为训练数据时，头部姿势准确度和身体姿势准确度分别约为62％和70％。除了及时地为缺失的标签拟合更灵活的模型之外，我们假设我们的方法也放松了头部和身体耦合约束，允许在群体中的对话交互期间通常看到的头部和身体姿势的更具表现力的模型。这提供了一个新的基线，以便为将来用于HBPE目的的多模态传感器数据的集成进行改进。

##### URL
[https://arxiv.org/abs/1808.01837](https://arxiv.org/abs/1808.01837)

##### PDF
[https://arxiv.org/pdf/1808.01837](https://arxiv.org/pdf/1808.01837)

