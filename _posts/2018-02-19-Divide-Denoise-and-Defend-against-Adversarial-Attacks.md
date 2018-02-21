---
layout: post
title: "Divide, Denoise, and Defend against Adversarial Attacks"
date: 2018-02-19 19:01:56
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Seyed-Mohsen Moosavi-Dezfooli, Ashish Shrivastava, Oncel Tuzel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks, although shown to be a successful class of machine learning algorithms, are known to be extremely unstable to adversarial perturbations. Improving the robustness of neural networks against these attacks is important, especially for security-critical applications. To defend against such attacks, we propose dividing the input image into multiple patches, denoising each patch independently, and reconstructing the image, without losing significant image content. This proposed defense mechanism is non-differentiable which makes it non-trivial for an adversary to apply gradient-based attacks. Moreover, we do not fine-tune the network with adversarial examples, making it more robust against unknown attacks. We present a thorough analysis of the tradeoff between accuracy and robustness against adversarial attacks. We evaluate our method under black-box, grey-box, and white-box settings. The proposed method outperforms the state-of-the-art by a significant margin on the ImageNet dataset under grey-box attacks while maintaining good accuracy on clean images. We also establish a strong baseline for a novel white-box attack.

##### Abstract (translated by Google)
深度神经网络虽然被证明是一种成功的机器学习算法类，但已知其对对抗性扰动极不稳定。提高神经网络对这些攻击的鲁棒性非常重要，特别是对于安全性至关重要的应用。为了抵御这种攻击，我们建议将输入图像分成多个片，独立地对每个片进行去噪，并重构图像，而不会丢失重要的图像内容。这个提出的防御机制是不可区分的，这使得攻击者应用基于梯度的攻击并不是微不足道的。而且，我们不会用对抗性的例子微调网络，使它对未知的攻击更加强大。我们对准确性和鲁棒性与敌对攻击之间的权衡进行了彻底分析。我们在黑盒，灰盒和白盒设置下评估我们的方法。在灰度箱攻击下，所提出的方法在ImageNet数据集上的性能优于现有技术，同时在干净的图像上保持良好的精度。我们还为新型白盒攻击建立了强大的基准。

##### URL
[http://arxiv.org/abs/1802.06806](http://arxiv.org/abs/1802.06806)

##### PDF
[http://arxiv.org/pdf/1802.06806](http://arxiv.org/pdf/1802.06806)

