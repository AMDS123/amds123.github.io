---
layout: post
title: "COBRAS: Fast, Iterative, Active Clustering with Pairwise Constraints"
date: 2018-03-29 13:52:59
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Toon Van Craenendonck, Sebastijan Duman&#x10d;i&#x107;, Elia Van Wolputte, Hendrik Blockeel
mathjax: true
---

* content
{:toc}

##### Abstract
Constraint-based clustering algorithms exploit background knowledge to construct clusterings that are aligned with the interests of a particular user. This background knowledge is often obtained by allowing the clustering system to pose pairwise queries to the user: should these two elements be in the same cluster or not? Active clustering methods aim to minimize the number of queries needed to obtain a good clustering by querying the most informative pairs first. Ideally, a user should be able to answer a couple of these queries, inspect the resulting clustering, and repeat these two steps until a satisfactory result is obtained. We present COBRAS, an approach to active clustering with pairwise constraints that is suited for such an interactive clustering process. A core concept in COBRAS is that of a super-instance: a local region in the data in which all instances are assumed to belong to the same cluster. COBRAS constructs such super-instances in a top-down manner to produce high-quality results early on in the clustering process, and keeps refining these super-instances as more pairwise queries are given to get more detailed clusterings later on. We experimentally demonstrate that COBRAS produces good clusterings at fast run times, making it an excellent candidate for the iterative clustering scenario outlined above.

##### Abstract (translated by Google)
基于约束的聚类算法利用背景知识来构建符合特定用户兴趣的聚类。这种背景知识通常通过允许聚类系统向用户提出成对查询来获得：这两个元素是否应该在同一个聚类中？主动聚类方法旨在通过首先查询最丰富的对来最小化获得良好聚类所需的查询数量。理想情况下，用户应该能够回答几个这样的查询，检查所得到的聚类，并重复这两个步骤直到获得令人满意的结果。我们提出COBRAS，一种适用于这种交互式聚类过程的成对约束的主动聚类方法。 COBRAS中的核心概念是超级实例：数据中的所有实例都属于同一个群集的本地区域。 COBRAS以自顶向下的方式构造这样的超级实例，以在聚类过程的早期产生高质量的结果，并且随着更多的成对查询被提供来获得更详细的聚类，这些超级实例不断完善。我们通过实验证明COBRAS在快速运行时产生良好的聚类，使其成为上述迭代聚类场景的优秀候选者。

##### URL
[http://arxiv.org/abs/1803.11060](http://arxiv.org/abs/1803.11060)

##### PDF
[http://arxiv.org/pdf/1803.11060](http://arxiv.org/pdf/1803.11060)

