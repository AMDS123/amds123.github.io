---
layout: post
title: "Hessian-based Analysis of Large Batch Training and Robustness to Adversaries"
date: 2018-02-22 18:55:00
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Optimization
author: Zhewei Yao, Amir Gholami, Qi Lei, Kurt Keutzer, Michael W. Mahoney
mathjax: true
---

* content
{:toc}

##### Abstract
Large batch size training of Neural Networks has been shown to incur accuracy loss when trained with the current methods. The precise underlying reasons for this are still not completely understood. Here, we study large batch size training through the lens of the Hessian operator and robust optimization. In particular, we perform a Hessian based study to analyze how the landscape of the loss functional is different for large batch size training. We compute the true Hessian spectrum, without approximation, by back-propagating the second derivative. Our results on multiple networks show that, when training at large batch sizes, one tends to stop at points in the parameter space with noticeably higher/larger Hessian spectrum, i.e., where the eigenvalues of the Hessian are much larger. We then study how batch size affects robustness of the model in the face of adversarial attacks. All the results show that models trained with large batches are more susceptible to adversarial attacks, as compared to models trained with small batch sizes. Furthermore, we prove a theoretical result which shows that the problem of finding an adversarial perturbation is a saddle-free optimization problem. Finally, we show empirical results that demonstrate that adversarial training leads to areas with smaller Hessian spectrum. We present detailed experiments with five different network architectures tested on MNIST, CIFAR-10, and CIFAR-100 datasets.

##### Abstract (translated by Google)
已经证明，神经网络的大批量训练在用现有方法进行训练时会导致准确性损失。确切的根本原因还没有完全理解。在这里，我们通过Hessian算子的镜头和强大的优化来研究大批量训练。特别是，我们执行基于Hessian的研究来分析大批量培训中损失函数的景观如何不同。我们通过反向传播二阶导数来计算真实的Hessian谱，无需近似。我们在多个网络上的结果表明，当以大批量训练时，在参数空间中的点处会显着停留在具有明显更高/更大Hessian谱的点上，即Hessian特征值更大的地方。然后我们研究批量大小如何影响模型在对抗性攻击面前的鲁棒性。所有结果都表明，与小批量培训的模型相比，大批量培训的模型更容易受到对抗性攻击。此外，我们证明了一个理论结果表明，发现敌对扰动的问题是一个无鞍优化问题。最后，我们展示的实证结果表明，对抗训练导致具有较小Hessian谱的区域。我们用在MNIST，CIFAR-10和CIFAR-100数据集上测试的五种不同网络体系结构进行了详细的实验。

##### URL
[http://arxiv.org/abs/1802.08241](http://arxiv.org/abs/1802.08241)

##### PDF
[http://arxiv.org/pdf/1802.08241](http://arxiv.org/pdf/1802.08241)

