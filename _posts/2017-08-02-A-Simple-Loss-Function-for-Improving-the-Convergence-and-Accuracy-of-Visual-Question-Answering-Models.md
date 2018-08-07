---
layout: post
title: "A Simple Loss Function for Improving the Convergence and Accuracy of Visual Question Answering Models"
date: 2017-08-02 02:51:32
categories: arXiv_CV
tags: arXiv_CV QA Attention Deep_Learning VQA
author: Ilija Ilievski, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Visual question answering as recently proposed multimodal learning task has enjoyed wide attention from the deep learning community. Lately, the focus was on developing new representation fusion methods and attention mechanisms to achieve superior performance. On the other hand, very little focus has been put on the models' loss function, arguably one of the most important aspects of training deep learning models. The prevailing practice is to use cross entropy loss function that penalizes the probability given to all the answers in the vocabulary except the single most common answer for the particular question. However, the VQA evaluation function compares the predicted answer with all the ground-truth answers for the given question and if there is a matching, a partial point is given. This causes a discrepancy between the model's cross entropy loss and the model's accuracy as calculated by the VQA evaluation function. In this work, we propose a novel loss, termed as soft cross entropy, that considers all ground-truth answers and thus reduces the loss-accuracy discrepancy. The proposed loss leads to an improved training convergence of VQA models and an increase in accuracy as much as 1.6%.

##### Abstract (translated by Google)
作为最近提出的多模式学习任务的视觉问题回答受到深度学习社区的广泛关注。最近，重点是开发新的表征融合方法和注意机制，以实现卓越的性能。另一方面，很少关注模型的损失函数，可以说是培养深度学习模型最重要的方面之一。流行的做法是使用交叉熵损失函数，该函数惩罚给予词汇表中所有答案的概率，除了针对特定问题的单个最常见答案。但是，VQA评估函数将预测答案与给定问题的所有真实答案进行比较，如果存在匹配，则给出部分点。这导致模型的交叉熵损失与由VQA评估函数计算的模型精度之间的差异。在这项工作中，我们提出了一种新的损失，称为软交叉熵，它考虑了所有地面实况的答案，从而降低了损失准确度的差异。建议的损失导致VQA模型的训练收敛性提高，准确度提高1.6％。

##### URL
[https://arxiv.org/abs/1708.00584](https://arxiv.org/abs/1708.00584)

##### PDF
[https://arxiv.org/pdf/1708.00584](https://arxiv.org/pdf/1708.00584)

