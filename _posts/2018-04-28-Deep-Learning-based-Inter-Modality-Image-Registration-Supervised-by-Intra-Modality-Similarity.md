---
layout: post
title: "Deep Learning based Inter-Modality Image Registration Supervised by Intra-Modality Similarity"
date: 2018-04-28 03:53:42
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Xiaohuan Cao, Jianhua Yang, Li Wang, Zhong Xue, Qian Wang, Dinggang Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Non-rigid inter-modality registration can facilitate accurate information fusion from different modalities, but it is challenging due to the very different image appearances across modalities. In this paper, we propose to train a non-rigid inter-modality image registration network, which can directly predict the transformation field from the input multimodal images, such as CT and MR images. In particular, the training of our inter-modality registration network is supervised by intra-modality similarity metric based on the available paired data, which is derived from a pre-aligned CT and MR dataset. Specifically, in the training stage, to register the input CT and MR images, their similarity is evaluated on the warped MR image and the MR image that is paired with the input CT. So that, the intra-modality similarity metric can be directly applied to measure whether the input CT and MR images are well registered. Moreover, we use the idea of dual-modality fashion, in which we measure the similarity on both CT modality and MR modality. In this way, the complementary anatomies in both modalities can be jointly considered to more accurately train the inter-modality registration network. In the testing stage, the trained inter-modality registration network can be directly applied to register the new multimodal images without any paired data. Experimental results have shown that, the proposed method can achieve promising accuracy and efficiency for the challenging non-rigid inter-modality registration task and also outperforms the state-of-the-art approaches.

##### Abstract (translated by Google)
非刚性的模式间注册可以促进来自不同模式的准确信息融合，但由于各种形式的图像外观差异很大，因此具有挑战性。在本文中，我们提出训练一个非刚性的模态图像配准网络，它可以直接预测输入多模态图像如CT和MR图像的变换场。具体而言，我们的模式间注册网络的训练是通过基于可用配对数据的模式内相似性度量来监督的，其来自预先对准的CT和MR数据集。具体而言，在训练阶段，为了注册输入的CT和MR图像，在扭曲的MR图像和与输入CT配对的MR图像上评估它们的相似性。因此，可以直接应用模式内相似性度量来测量输入CT和MR图像是否良好地登记。此外，我们使用双模式时尚的概念，其中我们测量CT模态和MR模态的相似性。通过这种方式，可以共同考虑两种模式中的互补解剖结构，以更准确地训练模式间登记网络。在测试阶段，训练好的多模态注册网络可以直接用于注册新的多模态图像，而不需要任何配对数据。实验结果表明，所提出的方法能够为具有挑战性的非刚性多模间配准任务实现有前途的准确性和效率，并且还优于最先进的方法。

##### URL
[https://arxiv.org/abs/1804.10735](https://arxiv.org/abs/1804.10735)

##### PDF
[https://arxiv.org/pdf/1804.10735](https://arxiv.org/pdf/1804.10735)

