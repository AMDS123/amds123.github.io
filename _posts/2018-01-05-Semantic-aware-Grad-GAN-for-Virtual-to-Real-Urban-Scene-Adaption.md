---
layout: post
title: "Semantic-aware Grad-GAN for Virtual-to-Real Urban Scene Adaption"
date: 2018-01-05 11:54:27
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation GAN Semantic_Segmentation Quantitative Recognition
author: Peilun Li, Xiaodan Liang, Daoyuan Jia, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in vision tasks (e.g., segmentation) highly depend on the availability of large-scale real-world image annotations obtained by cumbersome human labors. Moreover, the perception performance often drops significantly for new scenarios, due to the poor generalization capability of models trained on limited and biased annotations. In this work, we resort to transfer knowledge from automatically rendered scene annotations in virtual-world to facilitate real-world visual tasks. Although virtual-world annotations can be ideally diverse and unlimited, the discrepant data distributions between virtual and real-world make it challenging for knowledge transferring. We thus propose a novel Semantic-aware Grad-GAN (SG-GAN) to perform virtual-to-real domain adaption with the ability of retaining vital semantic information. Beyond the simple holistic color/texture transformation achieved by prior works, SG-GAN successfully personalizes the appearance adaption for each semantic region in order to preserve their key characteristic for better recognition. It presents two main contributions to traditional GANs: 1) a soft gradient-sensitive objective for keeping semantic boundaries; 2) a semantic-aware discriminator for validating the fidelity of personalized adaptions with respect to each semantic region. Qualitative and quantitative experiments demonstrate the superiority of our SG-GAN in scene adaption over state-of-the-art GANs. Further evaluations on semantic segmentation on Cityscapes show using adapted virtual images by SG-GAN dramatically improves segmentation performance than original virtual data. We release our code at https://github.com/Peilun-Li/SG-GAN.

##### Abstract (translated by Google)
视觉任务（例如分割）的最新进展高度依赖于由繁琐的人工获得的大规模真实世界图像注释的可用性。此外，由于在有限和有偏见的注释上训练的模型的泛化能力差，对于新的场景，感知性能经常显着下降。在这项工作中，我们诉诸于从虚拟世界中的自动渲染的场景注释中传递知识，以促进真实世界的视觉任务。虽然虚拟世界注释可以是理想的多样性和无限的，虚拟和现实世界之间的差异数据分布使得知识转移具有挑战性。因此，我们提出了一种新的语义感知Grad-GAN（SG-GAN），以保留重要的语义信息来执行虚拟到实际的域自适应。除了以前的作品实现的简单的整体颜色/纹理转换之外，SG-GAN成功地将每个语义区域的外观自适应个性化，以保持其关键特征以获得更好的识别。它对传统的GAN提出了两个主要贡献：1）保持语义边界的软梯度敏感目标; 2）用于验证关于每个语义区域的个性化适应的保真度的语义感知鉴别器。定性和定量实验证明了我们的SG-GAN在场景适应上优于最先进的GAN。对Cityscapes进行语义分割的进一步评估表明，使用由SG-GAN改编的虚拟图像比原始虚拟数据显着改善了分割性能。我们在https://github.com/Peilun-Li/SG-GAN发布我们的代码。

##### URL
[http://arxiv.org/abs/1801.01726](http://arxiv.org/abs/1801.01726)

##### PDF
[http://arxiv.org/pdf/1801.01726](http://arxiv.org/pdf/1801.01726)

