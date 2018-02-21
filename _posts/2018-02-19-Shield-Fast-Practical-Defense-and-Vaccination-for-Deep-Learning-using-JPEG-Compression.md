---
layout: post
title: "Shield: Fast, Practical Defense and Vaccination for Deep Learning using JPEG Compression"
date: 2018-02-19 19:13:42
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge Deep_Learning
author: Nilaksh Das, Madhuri Shanbhogue, Shang-Tse Chen, Fred Hohman, Siwei Li, Li Chen, Michael E. Kounavis, Duen Horng Chau
mathjax: true
---

* content
{:toc}

##### Abstract
The rapidly growing body of research in adversarial machine learning has demonstrated that deep neural networks (DNNs) are highly vulnerable to adversarially generated images. This underscores the urgent need for practical defense that can be readily deployed to combat attacks in real-time. Observing that many attack strategies aim to perturb image pixels in ways that are visually imperceptible, we place JPEG compression at the core of our proposed Shield defense framework, utilizing its capability to effectively "compress away" such pixel manipulation. To immunize a DNN model from artifacts introduced by compression, Shield "vaccinates" a model by re-training it with compressed images, where different compression levels are applied to generate multiple vaccinated models that are ultimately used together in an ensemble defense. On top of that, Shield adds an additional layer of protection by employing randomization at test time that compresses different regions of an image using random compression levels, making it harder for an adversary to estimate the transformation performed. This novel combination of vaccination, ensembling, and randomization makes Shield a fortified multi-pronged protection. We conducted extensive, large-scale experiments using the ImageNet dataset, and show that our approaches eliminate up to 94% of black-box attacks and 98% of gray-box attacks delivered by the recent, strongest attacks, such as Carlini-Wagner's L2 and DeepFool. Our approaches are fast and work without requiring knowledge about the model.

##### Abstract (translated by Google)
敌对机器学习研究的迅速发展表明，深度神经网络（DNNs）极易受到对手生成的图像的影响。这强调了迫切需要实际的防御措施，可以很容易地部署到实时防御攻击。观察到许多攻击策略旨在以视觉上不可察觉的方式干扰图像像素，我们将JPEG压缩放置在我们提出的Shield防御框架的核心，利用其有效“压缩”这种像素操纵的能力。为了从压缩引入的伪像中免疫DNN模型，Shield通过用压缩图像重新训练模型来“接种”模型，其中不同的压缩级别被应用以生成多个最终一起用于集体防御的接种疫苗的模型。最重要的是，Shield通过在测试时使用随机化来增加额外的保护层，该随机化使用随机压缩等级来压缩图像的不同区域，使得攻击者难以估计所执行的转换。这种新型的疫苗接种，组合和随机化组合使得Shield成为强化多方面的保护。我们使用ImageNet数据集进行了广泛的大规模实验，并且表明我们的方法可以消除最近发生的最强攻击（例如Carlini-Wagner的L2）所带来的黑盒攻击的94％和灰盒攻击的98％和DeepFool。我们的方法是快速的，而且不需要关于模型的知识。

##### URL
[http://arxiv.org/abs/1802.06816](http://arxiv.org/abs/1802.06816)

##### PDF
[http://arxiv.org/pdf/1802.06816](http://arxiv.org/pdf/1802.06816)

