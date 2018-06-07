---
layout: post
title: "Addressing Two Problems in Deep Knowledge Tracing via Prediction-Consistent Regularization"
date: 2018-06-06 13:41:48
categories: arXiv_AI
tags: arXiv_AI Regularization Knowledge Prediction
author: Chun-Kit Yeung, Dit-Yan Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge tracing is one of the key research areas for empowering personalized education. It is a task to model students' mastery level of a knowledge component (KC) based on their historical learning trajectories. In recent years, a recurrent neural network model called deep knowledge tracing (DKT) has been proposed to handle the knowledge tracing task and literature has shown that DKT generally outperforms traditional methods. However, through our extensive experimentation, we have noticed two major problems in the DKT model. The first problem is that the model fails to reconstruct the observed input. As a result, even when a student performs well on a KC, the prediction of that KC's mastery level decreases instead, and vice versa. Second, the predicted performance for KCs across time-steps is not consistent. This is undesirable and unreasonable because student's performance is expected to transit gradually over time. To address these problems, we introduce regularization terms that correspond to reconstruction and waviness to the loss function of the original DKT model to enhance the consistency in prediction. Experiments show that the regularized loss function effectively alleviates the two problems without degrading the original task of DKT.

##### Abstract (translated by Google)
知识追踪是增强个性化教育的关键研究领域之一。根据学生的历史学习轨迹，模拟学生对知识成分（KC）的掌握程度是一项任务。近年来，提出了一种称为深度知识追踪（DKT）的递归神经网络模型来处理知识追踪任务，并且文献表明DKT通常优于传统方法。但是，通过我们广泛的实验，我们注意到DKT模型中存在两个主要问题。第一个问题是该模型无法重建观察到的输入。因此，即使学生在KC上表现良好，对KC的掌握程度的预测反而会下降，反之亦然。其次，跨越时间步长的KCs的预测性能并不一致。这是不可取的，也是不合理的，因为学生的表现预计会随着时间逐渐过渡。为了解决这些问题，我们引入了与重建和波纹相对应的正则化术语，以适应原始DKT模型的损失函数，以提高预测的一致性。实验表明，正则化损失函数在不降低DKT原始任务的情况下有效缓解了这两个问题。

##### URL
[http://arxiv.org/abs/1806.02180](http://arxiv.org/abs/1806.02180)

##### PDF
[http://arxiv.org/pdf/1806.02180](http://arxiv.org/pdf/1806.02180)

