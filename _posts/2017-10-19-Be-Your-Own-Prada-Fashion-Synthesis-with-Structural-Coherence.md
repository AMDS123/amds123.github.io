---
layout: post
title: "Be Your Own Prada: Fashion Synthesis with Structural Coherence"
date: 2017-10-19 20:46:26
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Semantic_Segmentation Quantitative
author: Shizhan Zhu, Sanja Fidler, Raquel Urtasun, Dahua Lin, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel and effective approach for generating new clothing on a wearer through generative adversarial learning. Given an input image of a person and a sentence describing a different outfit, our model "redresses" the person as desired, while at the same time keeping the wearer and her/his pose unchanged. Generating new outfits with precise regions conforming to a language description while retaining wearer's body structure is a new challenging task. Existing generative adversarial networks are not ideal in ensuring global coherence of structure given both the input photograph and language description as conditions. We address this challenge by decomposing the complex generative process into two conditional stages. In the first stage, we generate a plausible semantic segmentation map that obeys the wearer's pose as a latent spatial arrangement. An effective spatial constraint is formulated to guide the generation of this semantic segmentation map. In the second stage, a generative model with a newly proposed compositional mapping layer is used to render the final image with precise regions and textures conditioned on this map. We extended the DeepFashion dataset [8] by collecting sentence descriptions for 79K images. We demonstrate the effectiveness of our approach through both quantitative and qualitative evaluations. A user study is also conducted. The codes and the data are available at this http URL edu.hk/projects/FashionGAN/.

##### Abstract (translated by Google)
我们提出了一种新颖有效的方法，通过生成对抗性学习，在穿着者身上产生新的服装。给定一个人的输入图像和一个描述不同装备的句子，我们的模型根据需要“修正”人，同时保持佩戴者和他/她的姿势不变。在保留佩戴者身体结构的同时，生成具有符合语言描述的精确区域的新服装是新的具有挑战性的任务。现有的生成对抗网络在确保输入照片和语言描述为条件的全球结构一致性方面并不理想。我们通过将复杂的生成过程分解为两个有条件的阶段来解决这个挑战。在第一阶段，我们生成一个合理的语义分割图，服从佩戴者的姿势作为潜在的空间安排。制定有效的空间约束来指导语义分割图的生成。在第二阶段中，使用新提出的组合映射层的生成模型来渲染最终图像，其中精确的区域和纹理在该图上被调节。我们通过收集79K图像的句子描述来扩展DeepFashion数据集[8]。我们通过定量和定性评估来证明我们的方法的有效性。用户研究也进行。代码和数据可在这个http URL edu.hk/projects/FashionGAN/上找到。

##### URL
[https://arxiv.org/abs/1710.07346](https://arxiv.org/abs/1710.07346)

##### PDF
[https://arxiv.org/pdf/1710.07346](https://arxiv.org/pdf/1710.07346)

