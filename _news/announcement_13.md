---
layout: post
title: Article published in the IEEE Data Engineering Bulletin journal
date: 2016-06-22 15:59:00-0400
inline: false
---

The quarterly published IEEE Data Engineering Bulletin journal was just released. Its current issue contains articles that specifically investigate the topic of data quality of a certain dataset. Our group contributed the article "Data Anamnesis: Admitting Raw Data into an Organization", which employs data profiling methods to both reconstruct the schema of the MusicBrainz dataset and assess its schema quality in a novel bottom-up manner. Please find the abstract below.

Authors: Sebastian Kruse, Thorsten Papenbrock, Hazar Harmouch and Felix Naumann

***

### Abstract
Today’s internet offers a plethora of openly available datasets, bearing great potential for novel applications and research. Likewise, rich datasets slumber within organizations. However, all too often those datasets are available only as raw dumps and lack proper documentation or even a schema. Data anamnesis is the first step of any effort to work with such datasets: It determines fundamental properties regarding the datasets’ content, structure, and quality to assess their utility and to put them to use appropriately. Detecting such properties is a key concern of the research area of data profiling, which has developed several viable instruments, such as data type recognition and foreign key discovery.

In this article, we perform an anamnesis of the MusicBrainz dataset, an openly available and complex discographic database. In particular, we employ data profiling methods to create data summaries and then further analyze those summaries to reverse-engineer the database schema, to understand the data semantics, and to point out tangible schema quality issues. We propose two bottom-up schema quality dimensions, namely conciseness and normality, that measure the fit of the schema with its data, in contrast to a top-down approach that compares a schema with its application requirements.