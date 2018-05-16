---
layout: post
title: "Knowledge Distillation in Generations: More Tolerant Teachers Educate Better Students"
date: 2018-05-15 03:51:03
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Optimization Classification Recognition
author: Chenglin Yang, Lingxi Xie, Siyuan Qiao, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies teacher-student optimization on neural networks, i.e., adopting the supervision from a trained (teacher) network to optimize another (student) network. Conventional approaches enforced the student to learn from a strict teacher which fit a hard distribution and achieved high recognition accuracy, but we argue that a more tolerant teacher often educate better students. 
 We start with adding an extra loss term to a patriarch network so that it preserves confidence scores on a primary class (the ground-truth) and several visually-similar secondary classes. The patriarch is also known as the first teacher. In each of the following generations, a student learns from the teacher and becomes the new teacher in the next generation. Although the patriarch is less powerful due to ambiguity, the students enjoy a persistent ability growth as we gradually fine-tune them to fit one-hot distributions. We investigate standard image classification tasks (CIFAR100 and ILSVRC2012). Experiments with different network architectures verify the superiority of our approach, either using a single model or an ensemble of models.

##### Abstract (translated by Google)
本文研究了神经网络的师生优化问题，即采用来自训练（教师）网络的监督来优化另一个（学生）网络。传统方法迫使学生从严格的教师那里学习，这种教师的分布很好，并且获得了很高的识别准确度，但是我们认为一个更宽容的教师通常会教育更好的学生。
 我们首先为族长网络增加一个额外的损失项目，这样它就可以保留一个主要类别（地面实况）和几个视觉上相似的中学课程的信心分数。族长也被称为第一位老师。在接下来的每一代中，一名学生从老师那里学习，并成为下一代的新老师。虽然由于模棱两可的原因，这位族长的能力较弱，但随着我们逐渐调整以适应独一无二的分配，学生们的能力持续增长。我们调查标准图像分类任务（CIFAR100和ILSVRC2012）。不同网络体系结构的实验验证了我们方法的优越性，无论是使用单个模型还是使用模型集合。

##### URL
[http://arxiv.org/abs/1805.05551](http://arxiv.org/abs/1805.05551)

##### PDF
[http://arxiv.org/pdf/1805.05551](http://arxiv.org/pdf/1805.05551)

