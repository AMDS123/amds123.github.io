---
layout: post
title: "A Learning and Masking Approach to Secure Learning"
date: 2017-11-22 04:52:45
categories: arXiv_CV
tags: arXiv_CV Adversarial Recognition
author: Linh Nguyen, Arunesh Sinha
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have been shown to be vulnerable against adversarial examples, which are data points cleverly constructed to fool the classifier. Such attacks can be devastating in practice, especially as DNNs are being applied to ever increasing critical tasks like image recognition in autonomous driving. In this paper, we introduce a new perspective on the problem. We do so by first defining robustness of a classifier to adversarial exploitation. Next, we show that the problem of adversarial example generation can be posed as learning problem. We also categorize attacks in literature into high and low perturbation attacks; well-known attacks like fast-gradient sign method (FGSM) and our attack produce higher perturbation adversarial examples while the more potent but computationally inefficient Carlini-Wagner (CW) attack is low perturbation. Next, we show that the dual approach of the attack learning problem can be used as a defensive technique that is effective against high perturbation attacks. Finally, we show that a classifier masking method achieved by adding noise to the a neural network's logit output protects against low distortion attacks such as the CW attack. We also show that both our learning and masking defense can work simultaneously to protect against multiple attacks. We demonstrate the efficacy of our techniques by experimenting with the MNIST and CIFAR-10 datasets.

##### Abstract (translated by Google)
深度神经网络（DNNs）已经被证明是脆弱的对立的例子，这是数据点聪明地构建来欺骗分类器。这种攻击在实践中可能是毁灭性的，特别是随着DNN被应用于不断增加的关键任务，如自主驾驶中的图像识别。在本文中，我们对这个问题提出了一个新的观点。我们首先定义了分类器的对抗性开发的鲁棒性。接下来，我们展示了对抗性例子生成的问题可以被认为是学习问题。我们还将文学攻击归类为高低扰动攻击;像快速梯度符号法（FGSM）这样的众所周知的攻击和我们的攻击产生更高的扰动对抗性例子，而更有效但计算效率低的Carlini-Wagner（CW）攻击是低扰动。接下来，我们证明攻击学习问题的对偶方法可以用作对高扰动攻击有效的防御技术。最后，我们展示了通过将噪声添加到神经网络的logit输出而实现的分类掩蔽方法防止诸如CW攻击的低失真攻击。我们还表明，我们的学习和掩蔽防御可以同时工作，以防止多重攻击。我们通过用MNIST和CIFAR-10数据集进行实验来证明我们的技术的有效性。

##### URL
[https://arxiv.org/abs/1709.04447](https://arxiv.org/abs/1709.04447)

##### PDF
[https://arxiv.org/pdf/1709.04447](https://arxiv.org/pdf/1709.04447)

