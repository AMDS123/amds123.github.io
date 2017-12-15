---
layout: post
title: "One-to-many face recognition with bilinear CNNs"
date: 2016-03-28 21:32:33
categories: arXiv_CV
tags: arXiv_CV Face CNN Deep_Learning Detection Face_Detection Recognition Face_Recognition
author: Aruni RoyChowdhury, Tsung-Yu Lin, Subhransu Maji, Erik Learned-Miller
mathjax: true
---

* content
{:toc}

##### Abstract
The recent explosive growth in convolutional neural network (CNN) research has produced a variety of new architectures for deep learning. One intriguing new architecture is the bilinear CNN (B-CNN), which has shown dramatic performance gains on certain fine-grained recognition problems [15]. We apply this new CNN to the challenging new face recognition benchmark, the IARPA Janus Benchmark A (IJB-A) [12]. It features faces from a large number of identities in challenging real-world conditions. Because the face images were not identified automatically using a computerized face detection system, it does not have the bias inherent in such a database. We demonstrate the performance of the B-CNN model beginning from an AlexNet-style network pre-trained on ImageNet. We then show results for fine-tuning using a moderate-sized and public external database, FaceScrub [17]. We also present results with additional fine-tuning on the limited training data provided by the protocol. In each case, the fine-tuned bilinear model shows substantial improvements over the standard CNN. Finally, we demonstrate how a standard CNN pre-trained on a large face database, the recently released VGG-Face model [20], can be converted into a B-CNN without any additional feature training. This B-CNN improves upon the CNN performance on the IJB-A benchmark, achieving 89.5% rank-1 recall.

##### Abstract (translated by Google)
最近卷积神经网络（CNN）研究的爆炸性增长产生了各种新的深度学习架构。一种令人感兴趣的新架构是双线性CNN（B-CNN），它在某些细粒度识别问题上表现出显着的性能增益[15]。我们将这个新的CNN应用于具有挑战性的新面孔识别基准IARPA Janus基准A（IJB-A）[12]。它具有挑战性的现实世界中的大量身份特征。由于使用计算机化的人脸检测系统不能自动识别人脸图像，因此没有这种数据库固有的偏见。我们从在ImageNet上预训练的AlexNet式网络开始，展示了B-CNN模型的性能。然后，我们使用中等规模的公共外部数据库FaceScrub显示微调的结果[17]。我们还提供了对协议提供的有限训练数据进行更多微调的结果。在每种情况下，微调的双线性模型显示出比标准CNN有实质性的改进。最后，我们演示了如何在没有任何额外的特征训练的情况下，将最近发布的VGG-Face模型[20]中的大规模人脸数据库预标准CNN进行预训练，可以转换为B-CNN。这个B-CNN改进了IJB-A基准的CNN表现，一级召回率达到89.5％。

##### URL
[https://arxiv.org/abs/1506.01342](https://arxiv.org/abs/1506.01342)

##### PDF
[https://arxiv.org/pdf/1506.01342](https://arxiv.org/pdf/1506.01342)

