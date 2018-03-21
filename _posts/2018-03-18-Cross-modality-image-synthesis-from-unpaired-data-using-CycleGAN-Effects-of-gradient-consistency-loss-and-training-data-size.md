---
layout: post
title: "Cross-modality image synthesis from unpaired data using CycleGAN: Effects of gradient consistency loss and training data size"
date: 2018-03-18 09:13:51
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Yuta Hiasa, Yoshito Otake, Masaki Takao, Takumi Matsuoka, Kazuma Takashima, Jerry L. Prince, Nobuhiko Sugano, Yoshinobu Sato
mathjax: true
---

* content
{:toc}

##### Abstract
CT is commonly used in orthopedic procedures. MRI is used along with CT to identify muscle structures and diagnose osteonecrosis due to its superior soft tissue contrast. However, MRI has poor contrast for bone structures. Clearly, it would be helpful if a corresponding CT were available, as bone boundaries are more clearly seen and CT has standardized (i.e., Hounsfield) units. Therefore, we aim at MR-to-CT synthesis. The CycleGAN was successfully applied to unpaired CT and MR images of the head, these images do not have as much variation of intensity pairs as do images in the pelvic region due to the presence of joints and muscles. In this paper, we extended the CycleGAN approach by adding the gradient consistency loss to improve the accuracy at the boundaries. We conducted two experiments. To evaluate image synthesis, we investigated dependency of image synthesis accuracy on 1) the number of training data and 2) the gradient consistency loss. To demonstrate the applicability of our method, we also investigated a segmentation accuracy on synthesized images.

##### Abstract (translated by Google)
CT常用于矫形手术。由于其优越的软组织对比度，MRI与CT一起用于识别肌肉结构并诊断骨坏死。然而，MRI对骨结构的对比度差。显然，如果有相应的CT可用，这将是有益的，因为更清楚地看到骨界限并且CT已经标准化（即，Hounsfield）单位。因此，我们的目标是MR-to-CT综合。 CycleGAN成功应用于头部不成对的CT和MR图像，由于关节和肌肉的存在，这些图像没有像骨盆区域中的图像那样的强度对的变化。在本文中，我们通过添加梯度一致性损失来扩展CycleGAN方法，以提高边界的精度。我们进行了两个实验。为了评估图像合成，我们研究了图像合成精度对1）训练数据的数量和2）梯度一致性损失的依赖性。为了证明我们方法的适用性，我们还研究了合成图像的分割准确性。

##### URL
[https://arxiv.org/abs/1803.06629](https://arxiv.org/abs/1803.06629)

##### PDF
[https://arxiv.org/pdf/1803.06629](https://arxiv.org/pdf/1803.06629)

