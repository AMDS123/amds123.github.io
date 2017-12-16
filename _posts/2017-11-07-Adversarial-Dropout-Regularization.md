---
layout: post
title: "Adversarial Dropout Regularization"
date: 2017-11-07 03:21:32
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Segmentation GAN Image_Classification Semantic_Segmentation Classification
author: Kuniaki Saito, Yoshitaka Ushiku, Tatsuya Harada, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for transferring neural representations from label-rich source domains to unlabeled target domains. Recent adversarial methods proposed for this task learn to align features across domains by fooling a special domain critic network. However, a drawback of this approach is that the critic simply labels the generated features as in-domain or not, without considering the boundaries between classes. This can lead to ambiguous features being generated near class boundaries, reducing target classification accuracy. We propose a novel approach, Adversarial Dropout Regularization (ADR), to encourage the generator to output more discriminative features for the target domain. Our key idea is to replace the critic with one that detects non-discriminative features, using dropout on the classifier network. The generator then learns to avoid these areas of the feature space and thus creates better features. We apply our ADR approach to the problem of unsupervised domain adaptation for image classification and semantic segmentation tasks, and demonstrate significant improvement over the state of the art. We also show that our approach can be used to train Generative Adversarial Networks for semi-supervised learning.

##### Abstract (translated by Google)
我们提出了一种方法，用于将标记丰富的源域中的神经表示转移到未标记的目标域。最近针对这一任务提出的对抗性方法学会通过欺骗一个特殊的域评论者网络来跨域调整特征。然而，这种方法的一个缺点是，评论者只是简单地将生成的特征标记为在域中，而不考虑类之间的边界。这可能导致类边界附近产生模糊的特征，降低了目标分类的准确性。我们提出了一种新颖的方法，对抗压差正则化（ADR），以鼓励发生器为目标域输出更多的判别特征。我们的主要想法是用分类器网络上的丢弃来替换那些检测非判别特征的评论者。生成器然后学习以避免特征空间的这些区域，从而创建更好的特征。我们将ADR方法应用于图像分类和语义分割任务的无监督域自适应问题，并展示了对现有技术的显着改进。我们还表明，我们的方法可以用来训练生成敌对网络半监督学习。

##### URL
[https://arxiv.org/abs/1711.01575](https://arxiv.org/abs/1711.01575)

##### PDF
[https://arxiv.org/pdf/1711.01575](https://arxiv.org/pdf/1711.01575)

