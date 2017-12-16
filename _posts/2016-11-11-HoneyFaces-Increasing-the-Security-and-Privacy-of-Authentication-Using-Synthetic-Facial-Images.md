---
layout: post
title: "HoneyFaces: Increasing the Security and Privacy of Authentication Using Synthetic Facial Images"
date: 2016-11-11 18:40:32
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Mor Ohana, Orr Dunkelman, Stuart Gibson, Margarita Osadchy
mathjax: true
---

* content
{:toc}

##### Abstract
One of the main challenges faced by Biometric-based authentication systems is the need to offer secure authentication while maintaining the privacy of the biometric data. Previous solutions, such as Secure Sketch and Fuzzy Extractors, rely on assumptions that cannot be guaranteed in practice, and often affect the authentication accuracy. In this paper, we introduce HoneyFaces: the concept of adding a large set of synthetic faces (indistinguishable from real) into the biometric "password file". This password inflation protects the privacy of users and increases the security of the system without affecting the accuracy of the authentication. In particular, privacy for the real users is provided by "hiding" them among a large number of fake users (as the distributions of synthetic and real faces are equal). In addition to maintaining the authentication accuracy, and thus not affecting the security of the authentication process, HoneyFaces offer several security improvements: increased exfiltration hardness, improved leakage detection, and the ability to use a Two-server setting like in HoneyWords. Finally, HoneyFaces can be combined with other security and privacy mechanisms for biometric data. We implemented the HoneyFaces system and tested it with a password file composed of 270 real users. The "password file" was then inflated to accommodate up to $2^{36.5}$ users (resulting in a 56.6 TB "password file"). At the same time, the inclusion of additional faces does not affect the true acceptance rate or false acceptance rate which were 93.33\% and 0.01\%, respectively.

##### Abstract (translated by Google)
基于生物识别的认证系统面临的主要挑战之一是需要提供安全的认证，同时保持生物识别数据的隐私。以前的解决方案（如安全草图和模糊提取器）依赖于在实践中无法保证的假设，并经常影响验证的准确性。在本文中，我们介绍HoneyFaces：将大量合成人脸添加到生物特征“密码文件”中的概念（与真实不可区分）。这种密码膨胀保护了用户的隐私，增加了系统的安全性，而不影响认证的准确性。特别是，真实用户的隐私是通过将他们“隐藏”在大量假用户之间来提供的（因为合成和真实脸部的分布是相同的）。除了保持身份验证的准确性，从而不影响身份验证过程的安全性，HoneyFaces还提供了一些安全方面的改进：增加渗出硬度，改善泄漏检测，以及像HoneyWords一样使用双服务器设置的能力。最后，HoneyFaces可以与生物识别数据的其他安全和隐私机制相结合。我们实现了HoneyFaces系统，并使用由270个真实用户组成的密码文件对其进行了测试。然后“密码文件”被充值以容纳高达$ 2 ^ {36.5} $的用户（导致56.6TB的“密码文件”）。同时，增加面值不影响真实验收率和错误接受率分别为93.33％和0.01％。

##### URL
[https://arxiv.org/abs/1611.03811](https://arxiv.org/abs/1611.03811)

##### PDF
[https://arxiv.org/pdf/1611.03811](https://arxiv.org/pdf/1611.03811)

