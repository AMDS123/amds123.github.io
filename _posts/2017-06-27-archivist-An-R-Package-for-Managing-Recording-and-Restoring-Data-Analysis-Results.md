---
layout: post
title: "archivist: An R Package for Managing, Recording and Restoring Data Analysis Results"
date: 2017-06-27 12:44:39
categories: arXiv_CV
tags: arXiv_CV Tracking Caption Relation
author: Przemyslaw Biecek, Marcin Kosinski
mathjax: true
---

* content
{:toc}

##### Abstract
Everything that exists in R is an object [Chambers2016]. This article examines what would be possible if we kept copies of all R objects that have ever been created. Not only objects but also their properties, meta-data, relations with other objects and information about context in which they were created. We introduce archivist, an R package designed to improve the management of results of data analysis. Key functionalities of this package include: (i) management of local and remote repositories which contain R objects and their meta-data (objects' properties and relations between them); (ii) archiving R objects to repositories; (iii) sharing and retrieving objects (and it's pedigree) by their unique hooks; (iv) searching for objects with specific properties or relations to other objects; (v) verification of object's identity and context of it's creation. The presented archivist package extends, in a combination with packages such as knitr and Sweave, the reproducible research paradigm by creating new ways to retrieve and validate previously calculated objects. These new features give a variety of opportunities such as: sharing R objects within reports or articles; adding hooks to R objects in table or figure captions; interactive exploration of object repositories; caching function calls with their results; retrieving object's pedigree (information about how the object was created); automated tracking of the performance of considered models, restoring R libraries to the state in which object was archived.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.08822](https://arxiv.org/abs/1706.08822)

##### PDF
[https://arxiv.org/pdf/1706.08822](https://arxiv.org/pdf/1706.08822)

