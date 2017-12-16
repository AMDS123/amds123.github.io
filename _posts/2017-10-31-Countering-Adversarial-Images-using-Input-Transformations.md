---
layout: post
title: "Countering Adversarial Images using Input Transformations"
date: 2017-10-31 21:22:16
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification
author: Chuan Guo, Mayank Rana, Moustapha Cisse, Laurens van der Maaten
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates strategies that defend against adversarial-example attacks on image-classification systems by transforming the inputs before feeding them to the system. Specifically, we study applying image transformations such as bit-depth reduction, JPEG compression, total variance minimization, and image quilting before feeding the image to a convolutional network classifier. Our experiments on ImageNet show that total variance minimization and image quilting are very effective defenses in practice, in particular, when the network is trained on transformed images. The strength of those defenses lies in their non-differentiable nature and their inherent randomness, which makes it difficult for an adversary to circumvent the defenses. Our best defense eliminates 60% of strong white-box and 90% of strong black-box attacks by a variety of major attack methods

##### Abstract (translated by Google)
本文研究了在图像分类系统上进行对抗性攻击的攻击策略，即在将输入提交给系统之前对其进行转换。具体而言，我们研究了在将图像馈送到卷积网络分类器之前，应用比特深度缩减，JPEG压缩，总方差最小化和图像绗缝之类的图像变换。我们在ImageNet上的实验表明，总的方差最小化和图像绗缝在实践中是非常有效的防御，特别是当网络在变换图像上训练时。这些防御的力量在于它们的不可区分性和固有的随机性，这使对手难以规避防御。我们最好的防御措施是通过各种主要的攻击手段来消除60％的强大的白盒子和90％的强大的黑盒子攻击

##### URL
[https://arxiv.org/abs/1711.00117](https://arxiv.org/abs/1711.00117)

##### PDF
[https://arxiv.org/pdf/1711.00117](https://arxiv.org/pdf/1711.00117)

