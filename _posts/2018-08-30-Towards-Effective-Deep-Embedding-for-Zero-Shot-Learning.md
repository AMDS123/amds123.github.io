---
layout: post
title: "Towards Effective Deep Embedding for Zero-Shot Learning"
date: 2018-08-30 00:51:13
categories: arXiv_CV
tags: arXiv_CV Embedding Recognition
author: Lei Zhang, Peng Wang, Lingqiao Liu, Chunhua Shen, Wei Wei, Yannning Zhang, Anton Van Den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning (ZSL) attempts to recognize visual samples of unseen classes by virtue of the semantic descriptions of those classes. We posit that the key to ZSL is to exploit an effective embedding space where 1) visual samples can be tightly centred around the semantic descriptions of classes that they belong to; 2) visual samples of different classes are separated from each other with a large enough margin. Towards this goal, we present a simple but surprisingly effective deep embedding model. In our model, we separately embed visual samples and semantic descriptions into a latent intermediate space such that visual samples not only coincide with associated semantic descriptions, but also can be correctly discriminated by a trainable linear classifier. By doing this, visual samples can be tightly centred around associated semantic descriptions and more importantly, they can be separated from other semantic descriptions with a large margin, thus leading to a new state-of-the-art for ZSL. Furthermore, due to lacking training samples, the generalization capacity of the learned embedding space to unseen classes can be further improved. To this end, we propose to upgrade our model with a refining strategy which progressively calibrates the embedding space based upon some test samples chosen from unseen classes with high-confidence pseudo labels, and ultimately improves the generalization capacity greatly. Experimental results on five benchmarks demonstrate the great advantage of our model over current state-of-the-art competitors. For example, on AwA1 dataset, our model improves the recognition accuracy on unseen classes by 16.9% in conventional ZSL setting and even by 38.6% in the generalized ZSL setting.

##### Abstract (translated by Google)
零射击学习（ZSL）试图通过这些类的语义描述来识别看不见的类的视觉样本。我们认为ZSL的关键是利用有效的嵌入空间，其中1）可视化样本可以紧紧围绕它们所属的类的语义描述; 2）不同类别的视觉样本以足够大的余量彼此分开。为实现这一目标，我们提出了一种简单但令人惊讶的有效深度嵌入模型。在我们的模型中，我们将视觉样本和语义描述分别嵌入到潜在的中间空间中，使得视觉样本不仅与相关的语义描述一致，而且还可以通过可训练的线性分类器正确地区分。通过这样做，可视化样本可以紧紧围绕相关的语义描述，更重要的是，它们可以与其他语义描述分开很大，从而为ZSL带来新的最新技术。此外，由于缺少训练样本，可以进一步提高学习嵌入空间对看不见的类的泛化能力。为此，我们建议使用精炼策略升级我们的模型，该策略基于从具有高置信度伪标签的看不见的类中选择的一些测试样本逐步校准嵌入空间，并最终大大提高泛化能力。五个基准测试的实验结果证明了我们的模型相对于当前最先进的竞争对手的巨大优势。例如，在AwA1数据集上，我们的模型在常规ZSL设置中将看不见的类别的识别准确度提高了16.9％，在广义ZSL设置中甚至提高了38.6％。

##### URL
[http://arxiv.org/abs/1808.10075](http://arxiv.org/abs/1808.10075)

##### PDF
[http://arxiv.org/pdf/1808.10075](http://arxiv.org/pdf/1808.10075)

