---
layout: post
title: Paper accepted at ICDE 2021
date: 2021-02-12 15:59:00-0400
inline: false
---

I am happy to announce that our research paper titled "Relational Header Discovery using Similarity Search in a Table Corpus" has been accepted for presentation at the 37th IEEE International Conference on Data Engineering (ICDE 2021).  The conference will take place virtually between 19-22 April, 2021.

Authors: Hazar Harmouch, Thorsten Papenbrock, Felix Naumann

***

### Abstract
Column headers are among the most relevant types of meta-data for relational tables, because they provide meaning and context in which the data is to be interpreted. Headers play an important role in many data integration, exploration, and cleaning scenarios, such as schema matching, knowledge base augmentation, and similarity search. Unfortunately, in many cases column headers are missing, because they were never defined properly, are meaningless, or have been lost during data extraction, transmission, or storage. For example, around one third of the tables on the Web have missing headers.

Missing headers leave abundant tabular data shrouded and inaccessible to many data-driven applications. We introduce a fully automated, multi-phase system that discovers table column headers for cases where headers are missing, meaningless, or unrepresentative for the column values. It leverages existing table headers from web tables to suggest human-understandable, representative, and consistent headers for any target table. We evaluate our system on tables extracted from Wikipedia. Overall, 60% of the automatically discovered table headers are exact and complete. Considering more header candidates, top-5 for example, increases this percentage to 72%.