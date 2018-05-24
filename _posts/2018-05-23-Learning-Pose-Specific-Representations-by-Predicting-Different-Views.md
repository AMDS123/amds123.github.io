---
layout: post
title: "Learning Pose Specific Representations by Predicting Different Views"
date: 2018-05-23 15:02:46
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Quantitative
author: Georg Poier, David Schinagl, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
The labeled data required to learn pose estimation for articulated objects is difficult to provide in the desired quantity, realism, density, and accuracy. To address this issue, we develop a method to learn representations, which are very specific for articulated poses, without the need for labeled training data. We exploit the observation that the object pose of a known object is predictive for the appearance in any known view. That is, given only the pose and shape parameters of a hand, the hand's appearance from any viewpoint can be approximated. To exploit this observation, we train a model that -- given input from one view -- estimates a latent representation, which is trained to be predictive for the appearance of the object when captured from another viewpoint. Thus, the only necessary supervision is the second view. The training process of this model reveals an implicit pose representation in the latent space. Importantly, at test time the pose representation can be inferred using only a single view. In qualitative and quantitative experiments we show that the learned representations capture detailed pose information. Moreover, when training the proposed method jointly with labeled and unlabeled data, it consistently surpasses the performance of its fully supervised counterpart, while reducing the amount of needed labeled samples by at least one order of magnitude.

##### Abstract (translated by Google)
学习铰接物体姿态估计所需的标记数据难以提供所需数量，真实性，密度和准确性。为了解决这个问题，我们开发了一种学习表示的方法，这些方法对于表达的姿势非常具体，而不需要标记的训练数据。我们利用这样的观察，即已知对象的对象姿态可以预测任何已知视图中的外观。也就是说，只给出一只手的姿态和形状参数，可以近似估计来自任何视点的手的外观。为了利用这个观察，我们训练了一个模型 - 根据一个视图的输入 - 估计一个潜在的表示，它被训练成可以预测从另一个视点捕获的对象的外观。因此，唯一必要的监督是第二种观点。该模型的训练过程揭示了潜在空间中的隐式姿态表示。重要的是，在测试时间，姿态表示可以仅使用单个视图来推断。在定性和定量实验中，我们展示了学习表示捕捉详细的姿势信息。而且，当与标记数据和未标记数据联合训练所提出的方法时，它总是超过其完全监督对象的表现，同时将所需标记样本的数量减少至少一个数量级。

##### URL
[http://arxiv.org/abs/1804.03390](http://arxiv.org/abs/1804.03390)

##### PDF
[http://arxiv.org/pdf/1804.03390](http://arxiv.org/pdf/1804.03390)

