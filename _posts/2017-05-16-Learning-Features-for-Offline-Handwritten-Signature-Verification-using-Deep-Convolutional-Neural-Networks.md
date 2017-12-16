---
layout: post
title: "Learning Features for Offline Handwritten Signature Verification using Deep Convolutional Neural Networks"
date: 2017-05-16 16:08:09
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN
author: Luiz G. Hafemann, Robert Sabourin, Luiz S. Oliveira
mathjax: true
---

* content
{:toc}

##### Abstract
Verifying the identity of a person using handwritten signatures is challenging in the presence of skilled forgeries, where a forger has access to a person's signature and deliberately attempt to imitate it. In offline (static) signature verification, the dynamic information of the signature writing process is lost, and it is difficult to design good feature extractors that can distinguish genuine signatures and skilled forgeries. This reflects in a relatively poor performance, with verification errors around 7% in the best systems in the literature. To address both the difficulty of obtaining good features, as well as improve system performance, we propose learning the representations from signature images, in a Writer-Independent format, using Convolutional Neural Networks. In particular, we propose a novel formulation of the problem that includes knowledge of skilled forgeries from a subset of users in the feature learning process, that aims to capture visual cues that distinguish genuine signatures and forgeries regardless of the user. Extensive experiments were conducted on four datasets: GPDS, MCYT, CEDAR and Brazilian PUC-PR datasets. On GPDS-160, we obtained a large improvement in state-of-the-art performance, achieving 1.72% Equal Error Rate, compared to 6.97% in the literature. We also verified that the features generalize beyond the GPDS dataset, surpassing the state-of-the-art performance in the other datasets, without requiring the representation to be fine-tuned to each particular dataset.

##### Abstract (translated by Google)
在有技能的伪造者的情况下，使用手写签名来验证一个人的身份是有挑战性的，在伪造者的存在下，伪造者可以访问一个人的签名，并故意试图模仿它。在离线（静态）签名验证中，签名写入过程的动态信息丢失，很难设计出能区分真实签名和熟练伪造的好特征提取器。这反映了相对较差的表现，在文献中最好的系统中验证误差约为7％。为了解决获得良好特征的困难以及改进系统性能，我们提议使用卷积神经网络以独立于Writer的格式学习来自签名图像的表示。特别是，我们提出了一个新的问题的表述，包括在特征学习过程中来自用户子集的熟练伪造者的知识，其旨在捕获区分真实签名和伪造品而不管用户的视觉线索。对四个数据集进行了广泛的实验：GPDS，MCYT，CEDAR和巴西PUC-PR数据集。在GPDS-160上，我们获得了最先进性能的大幅改善，实现了1.72％的等差错率，而在文献中则为6.97％。我们还证实，这些特征在GPDS数据集以外具有普遍性，超过了其他数据集的最新性能，而不需要对每个特定数据集的表示进行微调。

##### URL
[https://arxiv.org/abs/1705.05787](https://arxiv.org/abs/1705.05787)

##### PDF
[https://arxiv.org/pdf/1705.05787](https://arxiv.org/pdf/1705.05787)

