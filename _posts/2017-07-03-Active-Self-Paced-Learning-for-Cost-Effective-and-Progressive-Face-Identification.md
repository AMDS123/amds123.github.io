---
layout: post
title: "Active Self-Paced Learning for Cost-Effective and Progressive Face Identification"
date: 2017-07-03 02:18:47
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Prediction
author: Liang Lin, Keze Wang, Deyu Meng, Wangmeng Zuo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to develop a novel cost-effective framework for face identification, which progressively maintains a batch of classifiers with the increasing face images of different individuals. By naturally combining two recently rising techniques: active learning (AL) and self-paced learning (SPL), our framework is capable of automatically annotating new instances and incorporating them into training under weak expert re-certification. We first initialize the classifier using a few annotated samples for each individual, and extract image features using the convolutional neural nets. Then, a number of candidates are selected from the unannotated samples for classifier updating, in which we apply the current classifiers ranking the samples by the prediction confidence. In particular, our approach utilizes the high-confidence and low-confidence samples in the self-paced and the active user-query way, respectively. The neural nets are later fine-tuned based on the updated classifiers. Such heuristic implementation is formulated as solving a concise active SPL optimization problem, which also advances the SPL development by supplementing a rational dynamic curriculum constraint. The new model finely accords with the "instructor-student-collaborative" learning mode in human education. The advantages of this proposed framework are two-folds: i) The required number of annotated samples is significantly decreased while the comparable performance is guaranteed. A dramatic reduction of user effort is also achieved over other state-of-the-art active learning techniques. ii) The mixture of SPL and AL effectively improves not only the classifier accuracy compared to existing AL/SPL methods but also the robustness against noisy data. We evaluate our framework on two challenging datasets, and demonstrate very promising results. (this http URL)

##### Abstract (translated by Google)
本文旨在为人脸识别开发一种新的经济有效的框架，逐步维护一批不同人脸图像的分类器。通过自然结合最近兴起的两种技术：主动学习（AL）和自主学习（SPL），我们的框架能够自动注释新实例并将其纳入弱专家重新认证的培训中。我们首先使用几个注释样本对每个个体初始化分类器，并使用卷积神经网络提取图像特征。然后，从未注释的样本中选择多个候选用于分类器更新，其中我们通过预测置信度应用排序样本的当前分类器。具体来说，我们的方法分别利用了自信和活跃的用户查询方式的高置信度和低置信度的样本。稍后基于更新的分类器对神经网络进行微调。这样的启发式实现被形成为解决一个简洁的主动SPL优化问题，这也通过补充合理的动态课程约束来推动SPL的发展。新模式与人教学中的“师生协作”学习模式相得益彰。这个建议框架的优点是双重的：i）所需数量的注释样本大大减少，同时性能得到保证。与其他最先进的主动学习技术相比，用户努力的显着降低也得以实现。 ii）与现有的AL / SPL方法相比，SPL和AL的混合物不仅有效地改善了分类器的准确性，而且有效地提高了对噪声数据的鲁棒性。我们评估我们的框架在两个具有挑战性的数据集，并展示非常有前途的结果（这个http URL）

##### URL
[https://arxiv.org/abs/1701.03555](https://arxiv.org/abs/1701.03555)

##### PDF
[https://arxiv.org/pdf/1701.03555](https://arxiv.org/pdf/1701.03555)

