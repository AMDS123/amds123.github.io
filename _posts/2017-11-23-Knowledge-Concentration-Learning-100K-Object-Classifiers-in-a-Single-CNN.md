---
layout: post
title: "Knowledge Concentration: Learning 100K Object Classifiers in a Single CNN"
date: 2017-11-23 05:30:30
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge Image_Classification Inference Classification
author: Jiyang Gao, Zijian (James)Guo, Zhen Li, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained image labels are desirable for many computer vision applications, such as visual search or mobile AI assistant. These applications rely on image classification models that can produce hundreds of thousands (e.g. 100K) of diversified fine-grained image labels on input images. However, training a network at this vocabulary scale is challenging, and suffers from intolerable large model size and slow training speed, which leads to unsatisfying classification performance. A straightforward solution would be training separate expert networks (specialists), with each specialist focusing on learning one specific vertical (e.g. cars, birds...). However, deploying dozens of expert networks in a practical system would significantly increase system complexity and inference latency, and consumes large amounts of computational resources. To address these challenges, we propose a Knowledge Concentration method, which effectively transfers the knowledge from dozens of specialists (multiple teacher networks) into one single model (one student network) to classify 100K object categories. There are three salient aspects in our method: (1) a multi-teacher single-student knowledge distillation framework; (2) a self-paced learning mechanism to allow the student to learn from different teachers at various paces; (3) structurally connected layers to expand the student network capacity with limited extra parameters. We validate our method on OpenImage and a newly collected dataset, Entity-Foto-Tree (EFT), with 100K categories, and show that the proposed model performs significantly better than the baseline generalist model.

##### Abstract (translated by Google)
对于许多计算机视觉应用来说，细粒度的图像标签是可取的，例如视觉搜索或移动AI助手。这些应用程序依赖图像分类模型，可以在输入图像上生成数十万（例如100K）多样化的细粒度图像标签。然而，在这个词汇量级上训练一个网络是具有挑战性的，并且遭受不可容忍的大模型大小和慢的训练速度，这导致不令人满意的分类性能。一个简单的解决方案将是培训独立的专家网络（专家），每个专家专注于学习一个特定的垂直（例如汽车，鸟类...）。然而，在实际系统中部署数十个专家网络会大大增加系统复杂度和推理延迟，并消耗大量的计算资源。为了应对这些挑战，我们提出了一种知识集中方法，它将来自数十名专家（多个教师网络）的知识有效地转化为一个单一模型（一个学生网络），以对100K个对象类别进行分类。我们的方法有三个突出的方面：（1）多师生单一学生知识蒸馏框架; （2）自学的学习机制，让学生以不同的速度向不同的教师学习; （3）结构上连接的层，以扩大学生网络容量，有限的额外参数。我们验证了我们在OpenImage上的方法和一个新收集的数据集Entity-Foto-Tree（EFT），其中包含了10万个类别，并且表明所提出的模型比基准通用模型的性能要好得多。

##### URL
[https://arxiv.org/abs/1711.07607](https://arxiv.org/abs/1711.07607)

##### PDF
[https://arxiv.org/pdf/1711.07607](https://arxiv.org/pdf/1711.07607)

