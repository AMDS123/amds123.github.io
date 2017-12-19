---
layout: post
title: "Approximation-Aware Dependency Parsing by Belief Propagation"
date: 2015-08-10 19:48:33
categories: arXiv_CL
tags: arXiv_CL
author: Matthew R. Gormley, Mark Dredze, Jason Eisner
mathjax: true
---

* content
{:toc}

##### Abstract
We show how to train the fast dependency parser of Smith and Eisner (2008) for improved accuracy. This parser can consider higher-order interactions among edges while retaining O(n^3) runtime. It outputs the parse with maximum expected recall -- but for speed, this expectation is taken under a posterior distribution that is constructed only approximately, using loopy belief propagation through structured factors. We show how to adjust the model parameters to compensate for the errors introduced by this approximation, by following the gradient of the actual loss on training data. We find this gradient by back-propagation. That is, we treat the entire parser (approximations and all) as a differentiable circuit, as Stoyanov et al. (2011) and Domke (2010) did for loopy CRFs. The resulting trained parser obtains higher accuracy with fewer iterations of belief propagation than one trained by conditional log-likelihood.

##### Abstract (translated by Google)
我们展示了如何训练Smith和Eisner（2008）的快速依赖解析器，以提高准确性。这个解析器可以在保持O（n ^ 3）运行时的同时考虑边之间的高阶交互。它输出具有最大期望回忆的解析 - 但是对于速度，这个期望是在仅使用近似构造的后验分布下进行的，使用通过结构化因子的loopy信念传播。我们展示了如何调整模型参数来补偿由这个近似引入的误差，通过跟踪训练数据的实际损失的梯度。我们通过反向传播找到这个梯度。也就是说，我们把整个解析器（近似和全部）看作一个可微的电路，正如Stoyanov等人（2011年）和Domke（2010年）做了CROPs。得到的训练语法分析器通过比条件对数似然训练的信念传播更少的迭代获得更高的准确性。

##### URL
[https://arxiv.org/abs/1508.02375](https://arxiv.org/abs/1508.02375)

##### PDF
[https://arxiv.org/pdf/1508.02375](https://arxiv.org/pdf/1508.02375)

