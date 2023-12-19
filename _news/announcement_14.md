---
layout: post
title: Papers accepted at VLDB 2018
date: 2018-03-16 15:59:00-0400
inline: false
---

Our paper "Discovery of Genuine Functional Dependencies from Relational Data with Missing Values",  has been accepted for presentation at the 44th International Conference on Very Large Data Bases (VLDB 2018). VLDB 2018 will take place in Rio de Janeiro, Brazil, from August 27th to August 31st, 2018.

Authors: Laure Berti-Equille, Hazar Harmouch, Felix Naumann, Noel Novelli, and Saravanan Thirumuruganathan 

***

### Abstract
Functional dependencies (FDs) play an important role in maintaining data quality. They can be used to enforce data consistency and to guide repairs over a database. In this work, we investigate the problem of missing values and its impact on FD discovery. When using existing FD discovery algorithms, some genuine FDs could not be detected precisely due to missing values or some non-genuine FDs can be discovered even though they are caused by missing values with a certain NULL semantics. We define a notion of genuineness and propose algorithms to compute the genuineness score of a discovered FD. This can be used to identify the genuine FDs among the set of all valid dependencies that hold on the data. We evaluate the quality of our method over various real-world and semi-synthetic datasets with extensive experiments. The results show that our method performs well for relatively large FD sets and is able to accurately capture genuine FDs.