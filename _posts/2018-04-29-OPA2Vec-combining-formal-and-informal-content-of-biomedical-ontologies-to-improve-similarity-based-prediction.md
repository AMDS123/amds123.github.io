---
layout: post
title: "OPA2Vec: combining formal and informal content of biomedical ontologies to improve similarity-based prediction"
date: 2018-04-29 12:49:29
categories: arXiv_AI
tags: arXiv_AI Ontology Language_Model Prediction
author: Fatima Zohra Smaili, Xin Gao, Robert Hoehndorf
mathjax: true
---

* content
{:toc}

##### Abstract
Motivation: Ontologies are widely used in biology for data annotation, integration, and analysis. In addition to formally structured axioms, ontologies contain meta-data in the form of annotation axioms which provide valuable pieces of information that characterize ontology classes. Annotations commonly used in ontologies include class labels, descriptions, or synonyms. Despite being a rich source of semantic information, the ontology meta-data are generally unexploited by ontology-based analysis methods such as semantic similarity measures. Results: We propose a novel method, OPA2Vec, to generate vector representations of biological entities in ontologies by combining formal ontology axioms and annotation axioms from the ontology meta-data. We apply a Word2Vec model that has been pre-trained on PubMed abstracts to produce feature vectors from our collected data. We validate our method in two different ways: first, we use the obtained vector representations of proteins as a similarity measure to predict protein-protein interaction (PPI) on two different datasets. Second, we evaluate our method on predicting gene-disease associations based on phenotype similarity by generating vector representations of genes and diseases using a phenotype ontology, and applying the obtained vectors to predict gene-disease associations. These two experiments are just an illustration of the possible applications of our method. OPA2Vec can be used to produce vector representations of any biomedical entity given any type of biomedical ontology. Availability: this https URL Contact: robert.hoehndorf@kaust.edu.sa and xin.gao@kaust.edu.sa.

##### Abstract (translated by Google)
动机：本体在生物学中广泛用于数据注释，整合和分析。除了正式结构化的公理外，本体还包含注释公理形式的元数据，这些元数据提供了表征本体类的有价值的信息。本体中常用的注释包括类标签，描述或同义词。尽管作为丰富的语义信息来源，本体元数据通常未被基于本体的分析方法如语义相似性度量所利用。结果：我们提出了一种新的方法OPA2Vec，通过结合本体元数据中的形式本体公理和注释公理，生成本体中生物实体的向量表示。我们应用了一个Word2Vec模型，该模型已经在PubMed摘要上进行了预先训练，从我们收集的数据中产生特征向量。我们用两种不同的方法验证我们的方法：首先，我们使用获得的蛋白质矢量表示法作为相似性度量来预测两个不同数据集上的蛋白质 - 蛋白质相互作用（PPI）。其次，我们通过使用表型本体生成基因和疾病的载体表示并应用所获得的载体来预测基因 - 疾病关联来评估基于表型相似性预测基因 - 疾病关联的方法。这两个实验只是我们方法可能应用的一个例子。在任何类型的生物医学本体论中，OPA2Vec可用于生成任何生物医学实体的向量表示。可用性：此https URL联系人：robert.hoehndorf@kaust.edu.sa和xin.gao@kaust.edu.sa。

##### URL
[https://arxiv.org/abs/1804.10922](https://arxiv.org/abs/1804.10922)

##### PDF
[https://arxiv.org/pdf/1804.10922](https://arxiv.org/pdf/1804.10922)

