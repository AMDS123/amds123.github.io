---
layout: post
title: "Synthetically Trained Icon Proposals for Parsing and Summarizing Infographics"
date: 2018-07-27 05:33:09
categories: arXiv_CV
tags: arXiv_CV Summarization Classification
author: Spandan Madan (1), Zoya Bylinskii (1), Matthew Tancik (1), Adri&#xe0; Recasens (1), Kimberli Zhong (1), Sami Alsheikh (1), Hanspeter Pfister (2), Aude Oliva (1), Fredo Durand (1) ((1) Massachusetts Institute of Technology, (2) Harvard University)
mathjax: true
---

* content
{:toc}

##### Abstract
Widely used in news, business, and educational media, infographics are handcrafted to effectively communicate messages about complex and often abstract topics including `ways to conserve the environment' and `understanding the financial crisis'. Composed of stylistically and semantically diverse visual and textual elements, infographics pose new challenges for computer vision. While automatic text extraction works well on infographics, computer vision approaches trained on natural images fail to identify the stand-alone visual elements in infographics, or `icons'. To bridge this representation gap, we propose a synthetic data generation strategy: we augment background patches in infographics from our Visually29K dataset with Internet-scraped icons which we use as training data for an icon proposal mechanism. On a test set of 1K annotated infographics, icons are located with 38% precision and 34% recall (the best model trained with natural images achieves 14% precision and 7% recall). Combining our icon proposals with icon classification and text extraction, we present a multi-modal summarization application. Our application takes an infographic as input and automatically produces text tags and visual hashtags that are textually and visually representative of the infographic's topics respectively.

##### Abstract (translated by Google)
信息图表广泛用于新闻，商业和教育媒体，手工制作，有效地传达有关复杂和抽象主题的信息，包括“保护环境的方法”和“理解金融危机”。信息图表由风格和语义多样的视觉和文本元素组成，为计算机视觉带来了新的挑战。虽然自动文本提取在信息图表上运行良好，但在自然图像上训练的计算机视觉方法无法识别图表或“图标”中的独立视觉元素。为了弥合这种代表性差距，我们提出了一种综合数据生成策略：我们使用带有互联网抓取图标的Visually29K数据集在图表中增加背景补丁，我们将其用作图标提议机制的训练数据。在1K带注释的信息图表的测试集上，图标的精确度为38％，召回率为34％（使用自然图像训练的最佳模型达到14％的精度和7％的召回率）。结合我们的图标提议与图标分类和文本提取，我们提出了一个多模式摘要应用程序。我们的应用程序将信息图作为输入，并自动生成文本标签和可视标签，这些标签分别在文本和视觉上代表信息图的主题。

##### URL
[http://arxiv.org/abs/1807.10441](http://arxiv.org/abs/1807.10441)

##### PDF
[http://arxiv.org/pdf/1807.10441](http://arxiv.org/pdf/1807.10441)

