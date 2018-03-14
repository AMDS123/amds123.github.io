---
layout: post
title: "Testing Deep Neural Networks"
date: 2018-03-10 23:19:13
categories: arXiv_CV
tags: arXiv_CV
author: Youcheng Sun, Xiaowei Huang, Daniel Kroening
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have a wide range of applications, and software employing them must be thoroughly tested, especially in safety critical domains. However, traditional software testing methodology, including test coverage criteria and test case generation algorithms, cannot be applied directly to DNNs. This paper bridges this gap. First, inspired by the traditional MC/DC coverage criterion, we propose a set of four test criteria that are tailored to the distinct features of DNNs. Our novel criteria are incomparable and complement each other. Second, for each criterion, we give an algorithm for generating test cases based on linear programming (LP). The algorithms produce a new test case (i.e., an input to the DNN) by perturbing a given one. They encode the test requirement and a fragment of the DNN by fixing the activation pattern obtained from the given input example, and then minimize the difference between the new and the current inputs. Finally, we validate our method on a set of networks trained on the MNIST dataset. The utility of our method is shown experimentally with four objectives: (1)~bug finding; (2)~DNN safety statistics; (3)~testing efficiency and (4)~DNN internal structure analysis.

##### Abstract (translated by Google)
深度神经网络（DNN）具有广泛的应用，并且使用它们的软件必须经过彻底测试，特别是在安全关键领域。但是，传统的软件测试方法（包括测试覆盖标准和测试用例生成算法）不能直接应用于DNN。这篇论文填补了这个空白。首先，受传统MC / DC覆盖标准的启发，我们提出了一组四个测试标准，这些测试标准是针对DNN的不同特征而设计的。我们的新标准无与伦比，相辅相成。其次，对于每个标准，我们给出了一种基于线性规划（LP）生成测试用例的算法。算法通过扰动给定的算法产生新的测试用例（即DNN的输入）。他们通过固定从给定输入示例中获得的激活模式来编码DNN的测试要求和片段，然后最小化新输入和当前输入之间的差异。最后，我们在MNIST数据集上训练的一组网络上验证了我们的方法。我们的方法的实用性通过实验展示了四个目标：（1）发现错误; （2）〜DNN安全统计; （3）〜测试效率和（4）〜DNN内部结构分析。

##### URL
[http://arxiv.org/abs/1803.04792](http://arxiv.org/abs/1803.04792)

##### PDF
[http://arxiv.org/pdf/1803.04792](http://arxiv.org/pdf/1803.04792)

