---
layout: post
title: "Dual Control Memory Augmented Neural Networks for Treatment Recommendations"
date: 2018-02-11 03:50:41
categories: arXiv_CV
tags: arXiv_CV Prediction Recommendation
author: Hung Le, Truyen Tran, Svetha Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
Machine-assisted treatment recommendations hold a promise to reduce physician time and decision errors. We formulate the task as a sequence-to-sequence prediction model that takes the entire time-ordered medical history as input, and predicts a sequence of future clinical procedures and medications. It is built on the premise that an effective treatment plan may have long-term dependencies from previous medical history. We approach the problem by using a memory-augmented neural network, in particular, by leveraging the recent differentiable neural computer that consists of a neural controller and an external memory module. But differing from the original model, we use dual controllers, one for encoding the history followed by another for decoding the treatment sequences. In the encoding phase, the memory is updated as new input is read; at the end of this phase, the memory holds not only the medical history but also the information about the current illness. During the decoding phase, the memory is write-protected. The decoding controller generates a treatment sequence, one treatment option at a time. The resulting dual controller write-protected memory-augmented neural network is demonstrated on the MIMIC-III dataset on two tasks: procedure prediction and medication prescription. The results show improved performance over both traditional bag-of-words and sequence-to-sequence methods.

##### Abstract (translated by Google)
机器辅助治疗建议有望减少医生的时间和决策错误。我们将该任务制定为序列 - 序列预测模型，该模型将整个时间顺序的病史作为输入，并预测未来临床过程和药物的序列。它的基础是有效的治疗计划可能与以前的病史有长期的依赖关系。我们通过使用记忆增强神经网络来解决这个问题，特别是通过利用由神经控制器和外部存储器模块组成的最近的可微分神经计算机。但与原始模型不同，我们使用双控制器，一个用于编码历史，另一个用于解码治疗序列。在编码阶段，随着新输入被读取，存储器被更新;在这个阶段结束时，记忆不仅包含病史，还包含关于当前疾病的信息。在解码阶段，内存被写保护。解码控制器一次生成一个治疗序列，一个治疗选项。由此产生的双控制器写保护存储器增强神经网络在MIMIC-III数据集上展示了两项任务：程序预测和药物处方。结果表明，与传统袋装词和序列到序列方法相比，其性能有所提高。

##### URL
[https://arxiv.org/abs/1802.03689](https://arxiv.org/abs/1802.03689)

##### PDF
[https://arxiv.org/pdf/1802.03689](https://arxiv.org/pdf/1802.03689)

