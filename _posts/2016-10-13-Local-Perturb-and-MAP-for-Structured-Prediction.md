---
layout: post
title: "Local Perturb-and-MAP for Structured Prediction"
date: 2016-10-13 20:32:42
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference Prediction
author: Gedas Bertasius, Qiang Liu, Lorenzo Torresani, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional random fields (CRFs) provide a powerful tool for structured prediction, but cast significant challenges in both the learning and inference steps. Approximation techniques are widely used in both steps, which should be considered jointly to guarantee good performance (a.k.a. "inferning"). Perturb-and-MAP models provide a promising alternative to CRFs, but require global combinatorial optimization and hence they are usable only on specific models. In this work, we present a new Local Perturb-and-MAP (locPMAP) framework that replaces the global optimization with a local optimization by exploiting our observed connection between locPMAP and the pseudolikelihood of the original CRF model. We test our approach on three different vision tasks and show that our method achieves consistently improved performance over other approximate inference techniques optimized to a pseudolikelihood objective. Additionally, we demonstrate that we can integrate our method in the fully convolutional network framework to increase our model's complexity. Finally, our observed connection between locPMAP and the pseudolikelihood leads to a novel perspective for understanding and using pseudolikelihood.

##### Abstract (translated by Google)
条件随机场（CRF）为结构化预测提供了一个强有力的工具，但是在学习和推理步骤上都带来了重大的挑战。近似技术在这两个步骤中被广泛使用，这应当被联合考虑以保证良好的性能（也称为“推断”）。扰动和MAP模型提供了CRF的有希望的替代方案，但是需要全局组合优化，因此它们只能在特定模型上使用。在这项工作中，我们提出了一个新的本地扰动和MAP（LOCPMAP）框架，通过利用我们观察到的locPMAP和原CRF模型的伪似然性之间的连接，用局部优化来代替全局优化。我们测试我们的方法在三个不同的视觉任务，并表明我们的方法实现了优于其他近似推断技术，优化伪观测目标的性能持续改善。此外，我们证明我们可以将我们的方法集成到完全卷积网络框架中来增加模型的复杂性。最后，我们观察到的locPMAP和pseudolikelihood之间的联系导致了理解和使用伪似然的新视角。

##### URL
[https://arxiv.org/abs/1605.07686](https://arxiv.org/abs/1605.07686)

##### PDF
[https://arxiv.org/pdf/1605.07686](https://arxiv.org/pdf/1605.07686)

