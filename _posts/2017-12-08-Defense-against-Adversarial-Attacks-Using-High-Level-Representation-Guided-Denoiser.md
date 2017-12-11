---
layout: post
title: "Defense against Adversarial Attacks Using High-Level Representation Guided Denoiser"
date: 2017-12-08 08:20:45
categories: arXiv_CV
tags: arXiv_CV Adversarial Image_Classification Classification
author: Fangzhou Liao, Ming Liang, Yinpeng Dong, Tianyu Pang, Jun Zhu, Xiaolin Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are vulnerable to adversarial examples. This phenomenon poses a threat to their applications in security-sensitive systems. It is thus important to develop effective defending methods to strengthen the robustness of neural networks to adversarial attacks. Many techniques have been proposed, but only a few of them are validated on large datasets like the ImageNet dataset. We propose high-level representation guided denoiser (HGD) as a defense for image classification. HGD uses a U-net structure to capture multi-scale information. It serves as a preprocessing step to remove the adversarial noise from the input, and feeds its output to the target model. To train the HGD, we define the loss function as the difference of the target model's outputs activated by the clean image and denoised image. Compared with the traditional denoiser that imposes loss function at the pixel-level, HGD is better at suppressing the influence of adversarial noise. Compared with ensemble adversarial training which is the state-of-the-art defending method, HGD has three advantages. First, with HGD as a defense, the target model is more robust to either white-box or black-box adversarial attacks. Second, HGD can be trained on a small subset of the images and generalizes well to other images, which makes the training much easier on large-scale datasets. Third, HGD can be transferred to defend models other than the one guiding it. We further validated the proposed method in NIPS adversarial examples dataset and achieved state-of-the-art result.

##### Abstract (translated by Google)
神经网络容易受到敌对的例子。这种现象对安全敏感的系统中的应用程序构成威胁。因此，开发有效的防御方法来加强神经网络对抗攻击的鲁棒性非常重要。已经提出了许多技术，但是只有少数技术在像ImageNet数据集这样的大数据集上得到验证。我们提出高级表示指导降噪（HGD）作为图像分类的防御。 HGD使用U-net结构来捕获多尺度信息。它作为一个预处理步骤来消除来自输入的对抗噪声，并将其输出馈送到目标模型。为了训练HGD，我们将损失函数定义为由干净图像和去噪图像激活的目标模型输出的差异。与传统的在像素级施加损失函数的降噪器相比，HGD在抑制对抗噪声的影响方面较好。与集成对抗训练相比，HGD具有三大优势。首先，以HGD作为防御，目标模型对于白盒或黑盒对抗攻击更为强大。其次，HGD可以在一小部分图像上进行训练，对其他图像具有良好的泛化能力，这使得大规模数据集的训练变得更容易。第三，HGD可以转移到除引导它的模型之外的模型。我们进一步验证了在NIPS对抗性实例数据集中提出的方法，并取得了最新的结果。

##### URL
[http://arxiv.org/abs/1712.02976](http://arxiv.org/abs/1712.02976)

##### PDF
[http://arxiv.org/pdf/1712.02976](http://arxiv.org/pdf/1712.02976)

