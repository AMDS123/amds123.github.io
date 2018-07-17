---
layout: post
title: "3D Hand Pose Estimation using Simulation and Partial-Supervision with a Shared Latent Space"
date: 2018-07-14 11:26:19
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction
author: Masoud Abdi, Ehsan Abbasnejad, Chee Peng Lim, Saeid Nahavandi
mathjax: true
---

* content
{:toc}

##### Abstract
Tremendous amounts of expensive annotated data are a vital ingredient for state-of-the-art 3d hand pose estimation. Therefore, synthetic data has been popularized as annotations are automatically available. However, models trained only with synthetic samples do not generalize to real data, mainly due to the gap between the distribution of synthetic and real data. In this paper, we propose a novel method that seeks to predict the 3d position of the hand using both synthetic and partially-labeled real data. Accordingly, we form a shared latent space between three modalities: synthetic depth image, real depth image, and pose. We demonstrate that by carefully learning the shared latent space, we can find a regression model that is able to generalize to real data. As such, we show that our method produces accurate predictions in both semi-supervised and unsupervised settings. Additionally, the proposed model is capable of generating novel, meaningful, and consistent samples from all of the three domains. We evaluate our method qualitatively and quantitively on two highly competitive benchmarks (i.e., NYU and ICVL) and demonstrate its superiority over the state-of-the-art methods. The source code will be made available at https://github.com/masabdi/LSPS.

##### Abstract (translated by Google)
大量昂贵的注释数据是最先进的3D手姿态估计的重要组成部分。因此，随着注释自动可用，合成数据已经普及。然而，仅使用合成样本训练的模型不能推广到实际数据，这主要是由于合成数据和实际数据的分布之间的差距。在本文中，我们提出了一种新方法，该方法试图使用合成和部分标记的真实数据来预测手的3d位置。因此，我们在三种模态之间形成共享的潜在空间：合成深度图像，真实深度图像和姿势。我们通过仔细学习共享潜在空间来证明，我们可以找到一个能够推广到实际数据的回归模型。因此，我们表明我们的方法在半监督和无监督设置中产生准确的预测。此外，所提出的模型能够从所有三个域生成新颖，有意义且一致的样本。我们在两个竞争激烈的基准（即纽约大学和ICVL）上定性和定量地评估我们的方法，并证明其优于最先进的方法。源代码将在https://github.com/masabdi/LSPS上提供。

##### URL
[http://arxiv.org/abs/1807.05380](http://arxiv.org/abs/1807.05380)

##### PDF
[http://arxiv.org/pdf/1807.05380](http://arxiv.org/pdf/1807.05380)

