---
date: 2026-03-30 15:59:00-0400
inline: false
layout: post
title: Paper accepted at KG-LLM @LREC26
---

I am happy to announce that our research paper titled “End-to-End Graph Retrieval Pipeline for Specialized Domains” has been accepted for publication at KG-LLM @LREC26.

Authors: Haraldur Bjarni Davíðsson , and Hazar Harmouch

***

### Abstract
We present an end-to-end pipeline for constructing a domain-specific knowledge graph from instructional text using Large Language Model assisted extraction. Applied to the Icelandic Riding Levels, a 602 pages training corpus for riders of the Icelandic Horse, the pipeline produces a hyper-relational knowledge graph of 9,382 nodes and 16,423 edges, where schema-constrained qualifiers preserve the conditional and procedural context that standard triples discard. To evaluate the resulting graph, we introduce, to our knowledge, the first expert validated question answering benchmark for this domain: 252 questions across four reasoning categories.
Comparing Graph-, Text-, and Hybrid-retrieval augmented generation methods, we find that Text-based achieves the highest overall mean judge score, but that Graph-based provides the only correct answer for a small subset of queries, particularly where the corpus contains competing values for the same fact. A failure analysis traces the majority of Graph-based retrieval errors to context dilution at high-degree hub nodes. We discuss implications for adaptive retrieval strategies that route queries to the appropriate modality as results points to Graph-RAG potentially serving rather as a complementary and query specific rather than a broader replacement to general Text-RAG.