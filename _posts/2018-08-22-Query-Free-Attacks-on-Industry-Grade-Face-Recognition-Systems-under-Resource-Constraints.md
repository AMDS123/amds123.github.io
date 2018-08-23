---
layout: post
title: "Query-Free Attacks on Industry-Grade Face Recognition Systems under Resource Constraints"
date: 2018-08-22 13:19:33
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Face Embedding Recognition Face_Recognition
author: Di Tang, XiaoFeng Wang, Kehuan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
To launch black-box attacks against a Deep Neural Network (DNN) based Face Recognition (FR) system, one needs to build \textit{substitute} models to simulate the target model, so the adversarial examples discovered from substitute models could also mislead the target model. Such \textit{transferability} is achieved in recent studies through querying the target model to obtain data for training the substitute models. A real-world target, likes the FR system of law enforcement, however, is less accessible to the adversary. To attack such a system, a substitute model with similar quality as the target model is needed to identify their common defects. This is hard since the adversary often does not have the enough resources to train such a powerful model (hundreds of millions of images and rooms of GPUs are needed to train a commercial FR system). 
 We found in our research, however, that a resource-constrained adversary could still effectively approximate the target model's capability to recognize \textit{specific} individuals, by training \textit{biased} substitute models on additional images of those victims whose identities the attacker want to cover or impersonate. This is made possible by a new property we discovered, called \textit{Nearly Local Linearity} (NLL), which models the observation that an ideal DNN model produces the image representations (embeddings) whose distances among themselves truthfully describe the human perception of the differences among the input images. By simulating this property around the victim's images, we significantly improve the transferability of black-box impersonation attacks by nearly 50\%. Particularly, we successfully attacked a commercial system trained over 20 million images, using 4 million images and 1/5 of the training time but achieving 62\% transferability in an impersonation attack and 89\% in a dodging attack.

##### Abstract (translated by Google)
要针对基于深度神经网络（DNN）的人脸识别（FR）系统启动黑盒攻击，需要构建\ textit {替换}模型来模拟目标模型，因此从替代模型中发现的对抗性示例也可能误导目标模型。在最近的研究中通过查询目标模型以获得用于训练替代模型的数据来实现这种\ textit {可转移性}。然而，现实世界的目标，例如执法的FR系统，对手来说不太容易接近。为了攻击这样的系统，需要具有与目标模型相似质量的替代模型来识别它们的共同缺陷。这很难，因为对手通常没有足够的资源来训练这样一个强大的模型（需要数亿个图像和GPU的房间来训练商业FR系统）。
 然而，我们在我们的研究中发现，资源有限的对手仍然可以有效地近似目标模型识别\ textit {specific}个体的能力，通过训练\ textit {偏向}替代模型来识别攻击者身份的受害者的其他图像想要掩饰或冒充这是通过我们发现的一个新属性来实现的，称为\ textit {Nearly Local Linearity}（NLL），它模拟了理想DNN模型产生图像表示（嵌入）的观察结果，其中它们之间的距离真实地描述了人类对人类的感知。输入图像之间的差异。通过在受害者的图像周围模拟这个属性，我们显着提高了黑盒模拟攻击的可转移性近50％。特别是，我们成功攻击了一个训练超过2000万张图像的商业系统，使用了400万张图像和1/5的训练时间，但在模仿攻击中实现了62％的可转移性，在躲避攻击中实现了89％的可转移性。

##### URL
[http://arxiv.org/abs/1802.09900](http://arxiv.org/abs/1802.09900)

##### PDF
[http://arxiv.org/pdf/1802.09900](http://arxiv.org/pdf/1802.09900)

