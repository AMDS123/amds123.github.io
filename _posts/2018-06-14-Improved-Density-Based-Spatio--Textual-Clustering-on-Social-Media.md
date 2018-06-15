---
layout: post
title: "Improved Density-Based Spatio--Textual Clustering on Social Media"
date: 2018-06-14 13:11:52
categories: arXiv_AI
tags: arXiv_AI
author: Minh D. Nguyen, Won-Yong Shin
mathjax: true
---

* content
{:toc}

##### Abstract
DBSCAN may not be sufficient when the input data type is heterogeneous in terms of textual description. When we aim to discover clusters of geo-tagged records relevant to a particular point-of-interest (POI) on social media, examining only one type of input data (e.g., the tweets relevant to a POI) may draw an incomplete picture of clusters due to noisy regions. To overcome this problem, we introduce DBSTexC, a newly defined density-based clustering algorithm using spatio--textual information. We first characterize POI-relevant and POI-irrelevant tweets as the texts that include and do not include a POI name or its semantically coherent variations, respectively. By leveraging the proportion of POI-relevant and POI-irrelevant tweets, the proposed algorithm demonstrates much higher clustering performance than the DBSCAN case in terms of $\mathcal{F}_1$ score and its variants. While DBSTexC performs exactly as DBSCAN with the textually homogeneous inputs, it far outperforms DBSCAN with the textually heterogeneous inputs. Furthermore, to further improve the clustering quality by fully capturing the geographic distribution of tweets, we present fuzzy DBSTexC (F-DBSTexC), an extension of DBSTexC, which incorporates the notion of fuzzy clustering into the DBSTexC. We then demonstrate the robustness of F-DBSTexC via intensive experiments. The computational complexity of our algorithms is also analytically and numerically shown.

##### Abstract (translated by Google)
当输入数据类型在文本描述方面是异构的时，DBSCAN可能是不够的。当我们的目标是在社交媒体上发现与特定兴趣点（POI）相关的地理标记记录群时，仅检查一种类型的输入数据（例如，与POI相关的推文）可能会绘制一幅不完整的由于嘈杂的地区群集。为了克服这个问题，我们引入DBSTexC，一种新定义的基于密度的聚类算法，使用空间文本信息。我们首先将POI相关和POI无关推文分别描述为包含和不包含POI名称或其语义连贯变体的文本。通过利用POI相关和POI无关tweets的比例，所提出的算法在$ \ mathcal {F} _1 $分数及其变体方面表现出比DBSCAN情况更高的聚类性能。虽然DBSTexC完全像DBSCAN一样具有文本上的同质输入，但它远远优于DBSCAN和文本异构输入。此外，为了进一步通过完全捕获推文的地理分布来提高聚类质量，我们提出了模糊DBSTexC（F-DBSTexC），它是DBSTexC的扩展，它将模糊聚类的概念结合到DBSTexC中。然后我们通过大量的实验来证明F-DBSTexC的鲁棒性。我们的算法的计算复杂度也被分析和数字显示。

##### URL
[https://arxiv.org/abs/1806.05522](https://arxiv.org/abs/1806.05522)

##### PDF
[https://arxiv.org/pdf/1806.05522](https://arxiv.org/pdf/1806.05522)

