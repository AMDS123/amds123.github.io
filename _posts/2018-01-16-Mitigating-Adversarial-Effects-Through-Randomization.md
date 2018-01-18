---
layout: post
title: "Mitigating Adversarial Effects Through Randomization"
date: 2018-01-16 22:45:32
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN
author: Cihang Xie, Jianyu Wang, Zhishuai Zhang, Zhou Ren, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have demonstrated their powerful ability on various tasks in recent years. However, they are extremely vulnerable to adversarial examples. I.e., clean images, with imperceptible perturbations added, can easily cause convolutional neural networks to fail. In this paper, we propose to utilize randomization to mitigate adversarial effects. Specifically, we use two randomization operations: random resizing, which resizes the input images to a random size, and random padding, which pads zeros around the input images in a random manner. Extensive experiments demonstrate that the proposed randomization method is very effective at defending against both single-step and iterative attacks. Our method also enjoys the following advantages: 1) no additional training or fine-tuning, 2) very few additional computations, 3) compatible with other adversarial defense methods. By combining the proposed randomization method with an adversarially trained model, it achieves a normalized score of 0.924 (ranked No.2 among 107 defense teams) in the NIPS 2017 adversarial examples defense challenge, which is far better than using adversarial training alone with a normalized score of 0.773 (ranked No.56). The code is public available at https://github.com/cihangxie/NIPS2017_adv_challenge_defense.

##### Abstract (translated by Google)
卷积神经网络近年来在各种任务中表现出了强大的能力。但是，他们极易受到敌对的例子。也就是说，干净的图像，添加了不可察觉的干扰，很容易导致卷积神经网络失败。在本文中，我们建议利用随机化来缓解敌对效应。具体来说，我们使用两个随机化操作：随机调整大小，将输入图像调整为随机大小;随机填充，以随机方式在输入图像周围填充零。大量的实验表明，所提出的随机化方法在防止单步迭代攻击方面非常有效。我们的方法还具有以下优点：1）不需要额外的训练或微调，2）很少的附加计算，3）与其他对抗防御方法兼容。通过将所提出的随机化方法与对抗训练模型相结合，在NIPS 2017对抗示例防御挑战中，其达到0.924的归一化得分（在107个防守队伍中排名第二），这远远优于单独使用对抗训练得分0.773（排名第56）。该代码公开发布在https://github.com/cihangxie/NIPS2017_adv_challenge_defense。

##### URL
[http://arxiv.org/abs/1711.01991](http://arxiv.org/abs/1711.01991)

##### PDF
[http://arxiv.org/pdf/1711.01991](http://arxiv.org/pdf/1711.01991)

