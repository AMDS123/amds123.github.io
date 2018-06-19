---
layout: post
title: "Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention"
date: 2018-06-16 07:02:47
categories: arXiv_CV
tags: arXiv_CV Regularization Salient Adversarial Segmentation Attention Detection
author: Chao Yang, Taehwan Kim, Ruizhe Wang, Hao Peng, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
Image translation between two domains is a class of problems aiming to learn mapping from an input image in the source domain to an output image in the target domain. It has been applied to numerous domains, such as data augmentation, domain adaptation, and unsupervised training. When paired training data is not accessible, image translation becomes an ill-posed problem. We constrain the problem with the assumption that the translated image needs to be perceptually similar to the original image and also appears to be drawn from the new domain, and propose a simple yet effective image translation model consisting of a single generator trained with a self-regularization term and an adversarial term. We further notice that existing image translation techniques are agnostic to the subjects of interest and often introduce unwanted changes or artifacts to the input. Thus we propose to add an attention module to predict an attention map to guide the image translation process. The module learns to attend to key parts of the image while keeping everything else unaltered, essentially avoiding undesired artifacts or changes. The predicted attention map also opens door to applications such as unsupervised segmentation and saliency detection. Extensive experiments and evaluations show that our model while being simpler, achieves significantly better performance than existing image translation methods.

##### Abstract (translated by Google)
两个域之间的图像转换是一类旨在学习从源域中的输入图像到目标域中的输出图像的映射的问题。它已被应用于众多领域，如数据增强，领域适应和无监督培训。当配对的训练数据不可访问时，图像转换成为不适合的问题。我们用这样的假设来约束这个问题，即假设翻译后的图像需要与原始图像在感知上相似，并且似乎是从新域中得出的，并且提出了一个简单而有效的图像转换模型，正则化术语和对抗术语。我们进一步注意到现有的图像翻译技术对于感兴趣的主题是不可知的，并且经常向输入引入不希望的变化或伪像。因此，我们建议添加一个注意模块来预测注意图来指导图像翻译过程。该模块学习如何关注图像的关键部分，同时保持所有其他内容不变，从本质上避免不希望的人为因素或变化。预测的关注图也为诸如无监督分割和显着性检测等应用敞开了大门。大量的实验和评估表明，我们的模型更简单，与现有的图像转换方法相比，性能显着提高。

##### URL
[http://arxiv.org/abs/1806.06195](http://arxiv.org/abs/1806.06195)

##### PDF
[http://arxiv.org/pdf/1806.06195](http://arxiv.org/pdf/1806.06195)

