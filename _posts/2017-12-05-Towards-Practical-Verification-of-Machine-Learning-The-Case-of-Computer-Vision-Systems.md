---
layout: post
title: "Towards Practical Verification of Machine Learning: The Case of Computer Vision Systems"
date: 2017-12-05 17:49:18
categories: arXiv_CV
tags: arXiv_CV
author: Kexin Pei, Yinzhi Cao, Junfeng Yang, Suman Jana
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the increasing usage of machine learning (ML) techniques in security- and safety-critical domains, such as autonomous systems and medical diagnosis, ensuring correct behavior of ML systems, especially for different corner cases, is of growing importance. In this paper, we propose a generic framework for evaluating security and robustness of ML systems using different real-world safety properties. We further design, implement and evaluate VeriVis, a scalable methodology that can verify a diverse set of safety properties for state-of-the-art computer vision systems with only blackbox access. VeriVis leverage different input space reduction techniques for efficient verification of different safety properties. VeriVis is able to find thousands of safety violations in fifteen state-of-the-art computer vision systems including ten Deep Neural Networks (DNNs) such as Inception-v3 and Nvidia's Dave self-driving system with thousands of neurons as well as five commercial third-party vision APIs including Google vision and Clarifai for twelve different safety properties. Furthermore, VeriVis can successfully verify local safety properties, on average, for around 31.7% of the test images. VeriVis finds up to 64.8x more violations than existing gradient-based methods that, unlike VeriVis, cannot ensure non-existence of any violations. Finally, we show that retraining using the safety violations detected by VeriVis can reduce the average number of violations up to 60.2%.

##### Abstract (translated by Google)
由于机器学习（ML）技术在诸如自治系统和医疗诊断等安全和安全关键领域的使用日益增多，确保ML系统的正确行为，特别是对于不同的角落情况，正变得越来越重要。在本文中，我们提出了一个通用框架，用于评估使用不同实际安全属性的ML系统的安全性和健壮性。我们进一步设计，实施和评估VeriVis，这是一种可扩展的方法，可以验证只有黑匣子访问的最先进的计算机视觉系统的多种安全属性。 VeriVis利用不同的输入空间缩减技术来有效验证不同的安全属性。 VeriVis能够在15个最先进的计算机视觉系统中发现数以千计的安全违规行为，其中包括10个深度神经网络（DNN），例如Inception-v3和Nvidia的Dave自驱动系统，数千个神经元以及五个商业包括谷歌愿景和Clarifai在内的第三方视觉API，提供十二种不同的安全属性。而且，VeriVis平均可以成功地验证当地的安全属性，大约有31.7％的测试图像。与VeriVis不同的是，VeriVis比现有的基于渐变的方法发现多达64.8倍的违规，不能确保不存在任何违规。最后，我们显示，使用VeriVis检测到的安全违规进行再培训可以将平均违规数降低到60.2％。

##### URL
[http://arxiv.org/abs/1712.01785](http://arxiv.org/abs/1712.01785)

##### PDF
[http://arxiv.org/pdf/1712.01785](http://arxiv.org/pdf/1712.01785)

