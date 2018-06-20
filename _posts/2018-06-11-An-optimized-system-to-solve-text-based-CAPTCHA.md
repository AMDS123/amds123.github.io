---
layout: post
title: "An optimized system to solve text-based CAPTCHA"
date: 2018-06-11 06:52:19
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Ye Wang, Mi Lu
mathjax: true
---

* content
{:toc}

##### Abstract
CAPTCHA(Completely Automated Public Turing test to Tell Computers and Humans Apart) can be used to protect data from auto bots. Countless kinds of CAPTCHAs are thus designed, while we most frequently utilize text-based scheme because of most convenience and user-friendly way \cite{bursztein2011text}. Currently, various types of CAPTCHAs need corresponding segmentation to identify single character due to the numerous different segmentation ways. Our goal is to defeat the CAPTCHA, thus firstly the CAPTCHAs need to be split into character by character. There isn't a regular segmentation algorithm to obtain the divided characters in all kinds of examples, which means that we have to treat the segmentation individually. In this paper, we build a whole system to defeat the CAPTCHAs as well as achieve state-of-the-art performance. In detail, we present our self-adaptive algorithm to segment different kinds of characters optimally, and then utilize both the existing methods and our own constructed convolutional neural network as an extra classifier. Results are provided showing how our system work well towards defeating these CAPTCHAs.

##### Abstract (translated by Google)
CAPTCHA（完全自动公开的Turing测试，以告诉计算机和人类除外）可用于保护汽车机器人的数据。因此设计了无数类型的验证码，而我们最经常利用基于文本的方案，因为这种方法和用户友好性最强。\ cite {bursztein2011text}。目前，由于众多不同的分割方式，各种类型的验证码需要相应的分割来识别单个字符。我们的目标是击败CAPTCHA，因此首先需要将CAPTCHA逐字分解。没有一个正规的分割算法来获得各种例子中的分割字符，这意味着我们必须单独处理分割。在本文中，我们构建了一个完整的系统来击败CAPTCHA并实现最先进的性能。具体而言，我们提出了我们的自适应算法来优化分割不同种类的字符，然后利用现有的方法和我们自己构建的卷积神经网络作为额外的分类器。结果显示了我们的系统如何很好地打败这些CAPTCHA。

##### URL
[http://arxiv.org/abs/1806.07202](http://arxiv.org/abs/1806.07202)

##### PDF
[http://arxiv.org/pdf/1806.07202](http://arxiv.org/pdf/1806.07202)

