---
layout: post
title: "Invertible Autoencoder for domain adaptation"
date: 2018-02-10 01:00:32
categories: arXiv_CV
tags: arXiv_CV GAN Relation
author: Yunfei Teng, Anna Choromanska, Mariusz Bojarski
mathjax: true
---

* content
{:toc}

##### Abstract
The unsupervised image-to-image translation aims at finding a mapping between the source ($A$) and target ($B$) image domains, where in many applications aligned image pairs are not available at training. This is an ill-posed learning problem since it requires inferring the joint probability distribution from marginals. Joint learning of coupled mappings $F_{AB}: A \rightarrow B$ and $F_{BA}: B \rightarrow A$ is commonly used by the state-of-the-art methods, like CycleGAN [Zhu et al., 2017], to learn this translation by introducing cycle consistency requirement to the learning problem, i.e. $F_{AB}(F_{BA}(B)) \approx B$ and $F_{BA}(F_{AB}(A)) \approx A$. Cycle consistency enforces the preservation of the mutual information between input and translated images. However, it does not explicitly enforce $F_{BA}$ to be an inverse operation to $F_{AB}$. We propose a new deep architecture that we call invertible autoencoder (InvAuto) to explicitly enforce this relation. This is done by forcing an encoder to be an inverted version of the decoder, where corresponding layers perform opposite mappings and share parameters. The mappings are constrained to be orthonormal. The resulting architecture leads to the reduction of the number of trainable parameters (up to $2$ times). We present image translation results on benchmark data sets and demonstrate state-of-the art performance of our approach. Finally, we test the proposed domain adaptation method on the task of road video conversion. We demonstrate that the videos converted with InvAuto have high quality and show that the NVIDIA neural-network-based end-to-end learning system for autonomous driving, known as PilotNet, trained on real road videos performs well when tested on the converted ones.

##### Abstract (translated by Google)
无监督的图像到图像转换旨在找到源（$ A $）和目标（$ B $）图像域之间的映射，其中在许多应用中，对齐的图像对在训练时不可用。这是一个不适定的学习问题，因为它需要从边际推断联合概率分布。联合映射的联合学习$ F_ {AB}：A \ rightarrow B $和$ F_ {BA}：B \ rightarrow A $通常由最先进的方法使用，如CycleGAN [Zhu et al。， （AB）（F_ {BA}（B））\ approx B $和$ F_ {BA}（F_ {AB}（A））来学习这种翻译，通过引入对学习问题的循环一致性要求， ）\约A $。循环一致性强制保存输入图像和翻译图像之间的相互信息。但是，它并未明确强制$ F_ {BA} $作为$ F_ {AB} $的逆操作。我们提出了一种新的深层架构，我们称之为可逆自动编码器（InvAuto）来明确强制执行这种关系。这是通过强制编码器成为解码器的反转版本来完成的，其中相应的层执行相反的映射并共享参数。映射被限制为正交。由此产生的架构导致可训练参数的数量减少（最多2美元）。我们在基准数据集上呈现图像翻译结果，并展示我们方法的最新性能。最后，我们在道路视频转换任务上测试了所提出的领域适应方法。我们证明，使用InvAuto转换的视频具有高质量，并且表明用于自主驾驶的基于NVIDIA神经网络的端到端学习系统（称为PilotNet）在实际道路视频方面进行了培训，在对转换后的视频进行测试时表现良好。

##### URL
[http://arxiv.org/abs/1802.06869](http://arxiv.org/abs/1802.06869)

##### PDF
[http://arxiv.org/pdf/1802.06869](http://arxiv.org/pdf/1802.06869)

