---
layout: post
title: "Toward Open-Set Face Recognition"
date: 2017-05-19 00:24:43
categories: arXiv_CV
tags: arXiv_CV Face Recognition Face_Recognition
author: Manuel Günther, Steve Cruz, Ethan M. Rudd, Terrance E. Boult
mathjax: true
---

* content
{:toc}

##### Abstract
Much research has been conducted on both face identification and face verification, with greater focus on the latter. Research on face identification has mostly focused on using closed-set protocols, which assume that all probe images used in evaluation contain identities of subjects that are enrolled in the gallery. Real systems, however, where only a fraction of probe sample identities are enrolled in the gallery, cannot make this closed-set assumption. Instead, they must assume an open set of probe samples and be able to reject/ignore those that correspond to unknown identities. In this paper, we address the widespread misconception that thresholding verification-like scores is a good way to solve the open-set face identification problem, by formulating an open-set face identification protocol and evaluating different strategies for assessing similarity. Our open-set identification protocol is based on the canonical labeled faces in the wild (LFW) dataset. Additionally to the known identities, we introduce the concepts of known unknowns (known, but uninteresting persons) and unknown unknowns (people never seen before) to the biometric community. We compare three algorithms for assessing similarity in a deep feature space under an open-set protocol: thresholded verification-like scores, linear discriminant analysis (LDA) scores, and an extreme value machine (EVM) probabilities. Our findings suggest that thresholding EVM probabilities, which are open-set by design, outperforms thresholding verification-like scores.

##### Abstract (translated by Google)
对人脸识别和人脸验证进行了大量的研究，重点关注后者。关于人脸识别的研究主要集中在使用封闭协议，这些协议假设所有用于评估的探测图像都包含在图库中注册的主体的身份。真正的系统，但是，只有一小部分的探针样本身份登记在画廊，不能做这个封闭的假设。相反，他们必须假设一组开放的探针样本，并能够拒绝/忽略那些与未知身份相对应的样本。在本文中，我们解决普遍的错误认识，即通过制定开放式人脸识别协议和评估不同策略来评估相似性，阈值化验证分数是解决开放式人脸识别问题的好方法。我们的开放式身份识别协议基于野外标准人脸（LFW）数据集。除了已知的身份之外，我们还介绍了已知的未知数（已知但无趣的人）和未知的未知数（以前从未见过的人）到生物识别界的概念。我们比较了在开放协议下评估深特征空间中的相似性的三种算法：阈值验证样分数，线性判别分析（LDA）分数和极值机（EVM）概率。我们的研究结果表明，阈值EVM概率，这是设计开放，胜过阈值验证的分数。

##### URL
[https://arxiv.org/abs/1705.01567](https://arxiv.org/abs/1705.01567)

##### PDF
[https://arxiv.org/pdf/1705.01567](https://arxiv.org/pdf/1705.01567)

