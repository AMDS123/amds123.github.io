---
layout: post
title: "Method to Annotate Arrhythmias by Deep Network"
date: 2018-06-09 00:15:06
categories: arXiv_CV
tags: arXiv_CV Attention RNN
author: Weijia Lu, Jie Shuai, Shuyan Gu, Joel Xue
mathjax: true
---

* content
{:toc}

##### Abstract
This study targets to automatically annotate on arrhythmia by deep network. The investigated types include sinus rhythm, asystole (Asys), supraventricular tachycardia (Tachy), ventricular flutter or fibrillation (VF/VFL), ventricular tachycardia (VT). Methods: 13s limb lead ECG chunks from MIT malignant ventricular arrhythmia database (VFDB) and MIT normal sinus rhythm database were partitioned into subsets for 5-fold cross validation. These signals were resampled to 200Hz, filtered to remove baseline wandering, projected to 2D gray spectrum and then fed into a deep network with brand-new structure. In this network, a feature vector for a single time point was retrieved by residual layers, from which latent representation was extracted by variational autoencoder (VAE). These front portions were trained to meet a certain threshold in loss function, then fixed while training procedure switched to remaining bidirectional recurrent neural network (RNN), the very portions to predict an arrhythmia category. Attention windows were polynomial lumped on RNN outputs for learning from details to outlines. And over sampling was employed for imbalanced data. The trained model was wrapped into docker image for deployment in edge or cloud. Conclusion: Promising sensitivities were achieved in four arrhythmias and good precision rates in two ventricular arrhythmias were also observed. Moreover, it was proven that latent representation by VAE, can significantly boost the speed of convergence and accuracy.

##### Abstract (translated by Google)
本研究的目标是通过深度网络自动标注心律失常。所研究的类型包括窦性心律，心动过速（Asys），室上性心动过速（Tachy），心室扑动或颤动（VF / VFL），室性心动过速（VT）。方法：麻省理工学院恶性室性心律失常数据库（VFDB）和麻省理工学院正常窦性心律数据库的13s肢导联心电图组分为5组进行交叉验证。这些信号被重新采样到200Hz，滤波以消除基线漂移，投影到2D灰度频谱，然后馈入具有全新结构的深度网络。在这个网络中，一个单一时间点的特征向量被剩余层检索出来，潜变量由变量自编码器（VAE）提取。这些前端部分经过训练以在丢失功能中达到一定的阈值，然后在训练过程切换到剩余的双向递归神经网络（RNN）时固定，所述部分用于预测心律失常类别。注意窗口是RNN输出上的多项式集合，用于从细节到轮廓的学习。过度采样用于不平衡的数据。训练好的模型被包装到码头图像中以便在边缘或云中部署。结论：在4种心律失常中获得了有前景的敏感性，并且还观察到了两种室性心律失常的良好精确度。此外，事实证明，VAE的潜在表现能够显着提高收敛速度和准确性。

##### URL
[http://arxiv.org/abs/1806.07715](http://arxiv.org/abs/1806.07715)

##### PDF
[http://arxiv.org/pdf/1806.07715](http://arxiv.org/pdf/1806.07715)

