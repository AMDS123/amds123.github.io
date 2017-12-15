---
layout: post
title: "Deep Learning-Based Image Kernel for Inductive Transfer"
date: 2016-02-16 09:51:27
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification Deep_Learning
author: Neeraj Kumar, Animesh Karmakar, Ranti Dev Sharma, Abhinav Mittal, Amit Sethi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method to classify images from target classes with a small number of training examples based on transfer learning from non-target classes. Without using any more information than class labels for samples from non-target classes, we train a Siamese net to estimate the probability of two images to belong to the same class. With some post-processing, output of the Siamese net can be used to form a gram matrix of a Mercer kernel. Coupled with a support vector machine (SVM), such a kernel gave reasonable classification accuracy on target classes without any fine-tuning. When the Siamese net was only partially fine-tuned using a small number of samples from the target classes, the resulting classifier outperformed the state-of-the-art and other alternatives. We share class separation capabilities and insights into the learning process of such a kernel on MNIST, Dogs vs. Cats, and CIFAR-10 datasets.

##### Abstract (translated by Google)
我们提出了一种基于从非目标类转移学习的少量训练实例对来自目标类的图像进行分类的方法。对于非目标类别的样本，如果不使用更多的类别标签信息，我们将训练一个连体网络来估计两个图像属于同一个类别的概率。通过一些后处理，连体网的输出可以用来形成Mercer核的一个gram矩阵。再加上支持向量机（Support Vector Machine，SVM），这样的内核对目标类没有任何微调就能给出合理的分类精度。当连体网仅使用目标类别的少量样本进行部分微调时，所得分类器的性能优于现有技术和其他替代技术。我们在MNIST，Dogs vs. Cats和CIFAR-10数据集上分享了这种内核的学习过程中的班级分离能力和见解。

##### URL
[https://arxiv.org/abs/1512.04086](https://arxiv.org/abs/1512.04086)

##### PDF
[https://arxiv.org/pdf/1512.04086](https://arxiv.org/pdf/1512.04086)

