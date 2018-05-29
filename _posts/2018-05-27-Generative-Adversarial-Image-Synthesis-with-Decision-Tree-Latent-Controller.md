---
layout: post
title: "Generative Adversarial Image Synthesis with Decision Tree Latent Controller"
date: 2018-05-27 10:56:02
categories: arXiv_CV
tags: arXiv_CV Regularization Salient Adversarial Weakly_Supervised GAN Face Represenation_Learning
author: Takuhiro Kaneko, Kaoru Hiramatsu, Kunio Kashino
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes the decision tree latent controller generative adversarial network (DTLC-GAN), an extension of a GAN that can learn hierarchically interpretable representations without relying on detailed supervision. To impose a hierarchical inclusion structure on latent variables, we incorporate a new architecture called the DTLC into the generator input. The DTLC has a multiple-layer tree structure in which the ON or OFF of the child node codes is controlled by the parent node codes. By using this architecture hierarchically, we can obtain the latent space in which the lower layer codes are selectively used depending on the higher layer ones. To make the latent codes capture salient semantic features of images in a hierarchically disentangled manner in the DTLC, we also propose a hierarchical conditional mutual information regularization and optimize it with a newly defined curriculum learning method that we propose as well. This makes it possible to discover hierarchically interpretable representations in a layer-by-layer manner on the basis of information gain by only using a single DTLC-GAN model. We evaluated the DTLC-GAN on various datasets, i.e., MNIST, CIFAR-10, Tiny ImageNet, 3D Faces, and CelebA, and confirmed that the DTLC-GAN can learn hierarchically interpretable representations with either unsupervised or weakly supervised settings. Furthermore, we applied the DTLC-GAN to image-retrieval tasks and showed its effectiveness in representation learning.

##### Abstract (translated by Google)
本文提出了决策树潜在控制器生成对抗网络（DTLC-GAN），它是一个GAN的扩展，可以在不依赖详细监督的情况下学习分层解释表示。为了在潜在变量上实施分层包含结构，我们将一种称为DTLC的新架构纳入生成器输入中。 DTLC具有多层树结构，其中子节点代码的ON或OFF由父节点代码控制。通过分层次使用这种体系结构，我们可以根据高层应用程序获得选择使用低层代码的潜在空间。为了使潜在的代码在DTLC中以层次分解的方式捕捉图像的显着语义特征，我们还提出了一种分层的条件互信息正则化，并用我们提出的新定义的课程学习方法对其进行优化。这使得有可能通过仅使用单个DTLC-GAN模型的信息增益基于逐层方式来发现分层可解释的表示。我们评估了各种数据集上的DTLC-GAN，即MNIST，CIFAR-10，Tiny ImageNet，3D Faces和CelebA，并证实DTLC-GAN可以通过无监督或弱监督设置学习分层可解释的表示。此外，我们将DTLC-GAN应用于图像检索任务，并表现出其在表示学习中的有效性。

##### URL
[http://arxiv.org/abs/1805.10603](http://arxiv.org/abs/1805.10603)

##### PDF
[http://arxiv.org/pdf/1805.10603](http://arxiv.org/pdf/1805.10603)

