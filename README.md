# Database Systems

## Introduction

Any Data Scientist or Machine Learning Engineer, in fact any developer, will have to interact with databases mostly on a daily basis. It is helpful to understand how they are organized and queries get executed to write performant queries. Additionally, it opens the door for other topics such as distrubted and big data systems. Finally, it improves systems skills that are transferrable to other domains.

This course is about the design and implementation of database management systems (DBMS).  Topics discussed include: 
- Data models (relational, document, key/value)
- Storage models (n-ary, decomposition)
- Query languages (SQL, stored procedures)
- Storage architectures (heaps, log-structured)
- Indexing (order preserving trees, hash tables)
- Transaction processing (ACID, concurrency control)
- Recovery (logging, checkpoints)
- Query processing (joins, sorting, aggregation, optimization)
- Parallel architectures (multi-core, distributed)

We won't discuss how to use DBMSs or how to administer them.

## Learning Objectives

The main learning goals are:
- Flex systems thinking and programming skills
- Understand how data is organized and managed by DBMS
- What is a transaction? And how does a DBMS guarantee atomicity and all other guarantees (ACID)?
- How DBMSs use concurrency to parallelize their workloads?
- How to recover from craches?
- How does the query optimizer evaluate different plans for a given query?
- How to speed up queries using indexes and other techniques?
- How joins are really done under the hood?

