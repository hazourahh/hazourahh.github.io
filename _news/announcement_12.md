---
layout: post
title: Experimental survey accepted at VLDB 2018
date: 2017-11-15 15:59:00-0400
inline: false
---

Our paper "Cardinality Estimation: An Experimental Survey" has been accepted for presentation at the 44th International Conference on Very Large Data Bases (VLDB 2018). VLDB 2018 will take place in Rio de Janeiro, Brazil, from August 27th to August 31st, 2018.

Authors: Hazar Harmouch and Felix Naumann

***

### Abstract
Data preparation and data profiling comprise many both basic and complex tasks to analyze a dataset at hand and extract metadata, such as data distributions, key candidates, and functional dependencies. Among the most important types of metadata is the number of distinct values in a column, also known as the zeroth-frequency moment. Cardinality estimation itself has been an active research topic in the past decades due to its many applications. The aim of this paper is to review the literature of cardinality estimation and to present a detailed experimental study of twelve algorithms, scaling far beyond the original experiments.

First, we outline and classify approaches to solve the problem of cardinality estimation-we describe their main idea, error-guarantees, advantages, and disadvantages. Our experimental survey then compares the performance all twelve cardinality estimation algorithms. We evaluate the algorithms' accuracy, runtime, and memory consumption using synthetic and real-world datasets. Our results show that different algorithms excel in different in categories, and we highlight their trade-offs