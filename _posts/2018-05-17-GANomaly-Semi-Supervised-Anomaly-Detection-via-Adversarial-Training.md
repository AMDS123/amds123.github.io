---
layout: post
title: "GANomaly: Semi-Supervised Anomaly Detection via Adversarial Training"
date: 2018-05-17 12:36:02
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference Detection
author: Samet Akcay, Amir Atapour-Abarghouei, Toby P. Breckon
mathjax: true
---

* content
{:toc}

##### Abstract
Anomaly detection is a classical problem in computer vision, namely the determination of the normal from the abnormal when datasets are highly biased towards one class (normal) due to the insufficient sample size of the other class (abnormal). While this can be addressed as a supervised learning problem, a significantly more challenging problem is that of detecting the unknown/unseen anomaly case that takes us instead into the space of a one-class, semi-supervised learning paradigm. We introduce such a novel anomaly detection model, by using a conditional generative adversarial network that jointly learns the generation of high-dimensional image space and the inference of latent space. Employing encoder-decoder-encoder sub-networks in the generator network enables the model to map the input image to a lower dimension vector, which is then used to reconstruct the generated output image. The use of the additional encoder network maps this generated image to its latent representation. Minimizing the distance between these images and the latent vectors during training aids in learning the data distribution for the normal samples. As a result, a larger distance metric from this learned data distribution at inference time is indicative of an outlier from that distribution - an anomaly. Experimentation over several benchmark datasets, from varying domains, shows the model efficacy and superiority over previous state-of-the-art approaches.

##### Abstract (translated by Google)
异常检测是计算机视觉中的一个经典问题，即由于其他类别的样本量不足（异常）而导致数据集高度偏向一个类别（正常）时，由异常确定正常。虽然这可以作为一个监督学习问题来解决，但一个更具挑战性的问题是检测未知/看不见的异常情况，而不是将这些情况带入一个一类半监督学习范例的空间。我们通过使用联合学习高维图像空间的生成和潜在空间的推理的条件生成对抗网络来引入这种新颖的异常检测模型。在发生器网络中使用编码器 - 解码器 - 编码器子网络使模型能够将输入图像映射到较低维度的矢量，然后用它来重建生成的输出图像。使用附加的编码器网络将该生成的图像映射到其潜在表示。在训练期间最小化这些图像与潜在矢量之间的距离有助于学习正常样本的数据分布。因此，在推断时间与这个学习数据分布相距较远的距离度量指示该分布异常 - 异常。对来自不同领域的几个基准数据集进行的实验显示了模型的效能和优于先前的最新方法的优势。

##### URL
[http://arxiv.org/abs/1805.06725](http://arxiv.org/abs/1805.06725)

##### PDF
[http://arxiv.org/pdf/1805.06725](http://arxiv.org/pdf/1805.06725)

