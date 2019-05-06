---
layout: post
title: "Japanese Virtual Observatory as an advanced astronomical research enviroment"
date: 2006-04-28 01:18:26
categories: arXiv_CV
tags: arXiv_CV
author: Y.Shirasaki, M.Tanaka, S.Kawanomoto, S.Honda, M.Ohishi, Y.Mizumoto, N.Yasuda, Y.Masunaga, Y.Ishihara, J.Tsutsumi, H.Nakamoto, Y.Kobayashi, M.Sakamoto
mathjax: true
---

* content
{:toc}

##### Abstract
We present the design and implementation of the Japanese Virtual Observatory (JVO) system. JVO is a portal site to various kinds of astronomical resources distributed all over the world. We have developed five components for constructing the portal: (1) registry, (2) data service, (3) workflow system, (4) data analysis service (5) portal GUI. Registry services are used for publishing and searching data services in the VO, and they are constructed using an OAI-PMH metadata harvesting protocol and a SOAP web service protocol so that VO standard architecture is applied. Data services are developed based on the Astronomical Data Query Language (ADQL) which is an international VO standard and an extension of the standard SQL. The toolkit for building the ADQL-based service is released to the public on the JVO web site. The toolkit also provides the protocol translation from a Simple Image Access Protocol (SIAP) to ADQL protocol, so that both the VO standard service can be constructed using our toolkit. In order to federate the distributed databases and analysis services, we have designed a workflow language which is described in XML and developed execution system of the workflow. We have succeeded to connect to a hundred of data resources of the world as of April 2006. We have applied this system to the study of QSO environment by federating a QSO database, a Subaru Suprim-Cam database, and some analysis services such a SExtractor and HyperZ web services. These experiences are described is this paper.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/astro-ph/0604593](https://arxiv.org/abs/astro-ph/0604593)

##### PDF
[https://arxiv.org/pdf/astro-ph/0604593](https://arxiv.org/pdf/astro-ph/0604593)

