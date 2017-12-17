---
layout: post
title: "Improving the Adversarial Robustness and Interpretability of Deep Neural Networks by Regularizing their Input Gradients"
date: 2017-11-26 15:20:46
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Classification Prediction Relation
author: Andrew Slavin Ross, Finale Doshi-Velez
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have proven remarkably effective at solving many classification problems, but have been criticized recently for two major weaknesses: the reasons behind their predictions are uninterpretable, and the predictions themselves can often be fooled by small adversarial perturbations. These problems pose major obstacles for the adoption of neural networks in domains that require security or transparency. In this work, we evaluate the effectiveness of defenses that differentiably penalize the degree to which small changes in inputs can alter model predictions. Across multiple attacks, architectures, defenses, and datasets, we find that neural networks trained with this input gradient regularization exhibit robustness to transferred adversarial examples generated to fool all of the other models. We also find that adversarial examples generated to fool gradient-regularized models fool all other models equally well, and actually lead to more "legitimate," interpretable misclassifications as rated by people (which we confirm in a human subject experiment). Finally, we demonstrate that regularizing input gradients makes them more naturally interpretable as rationales for model predictions. We conclude by discussing this relationship between interpretability and robustness in deep neural networks.

##### Abstract (translated by Google)
深度神经网络在解决许多分类问题方面已被证明是非常有效的，但最近有两个主要弱点被批评：其预测背后的原因是无法解释的，预测本身常常被小的对抗性扰动愚弄。这些问题在需要安全性或透明度的领域中采用神经网络构成重大障碍。在这项工作中，我们评估防御措施的有效性，可以有差别地惩罚投入品的微小变化可以改变模型预测的程度。在多个攻击，体系结构，防御和数据集中，我们发现使用这个输入梯度正则化训练的神经网络显示出鲁棒性，转移对手生成的例子欺骗所有其他模型。我们还发现，为了欺骗梯度正则化模型而产生的对抗性例子同样欺骗了所有其他模型，并且实际上导致了更多的“合法的”可解释的错误分类（如我们在人类主题实验中所确认的）。最后，我们证明规则化输入梯度使得它们更自然地被解释为模型预测的基本原理。我们通过讨论深层神经网络的可解释性和鲁棒性之间的这种关系来得出结论。

##### URL
[https://arxiv.org/abs/1711.09404](https://arxiv.org/abs/1711.09404)

##### PDF
[https://arxiv.org/pdf/1711.09404](https://arxiv.org/pdf/1711.09404)

