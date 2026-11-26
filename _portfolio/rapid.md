---
title: "RAPID and Scalable Semantic Web Data Processing in the Cloud"
excerpt: "Query algebras, data models, and optimization techniques for processing large RDF graphs and knowledge graphs on MapReduce, Hadoop, and Spark. NSF IIS-1218277 (2012–2017)."
collection: portfolio
group: earlier
order: 13
---

As Semantic Web and knowledge graph datasets grew to billions of triples, processing them on cloud data-processing platforms such as MapReduce became attractive, but naive translations of SPARQL queries into MapReduce jobs are very expensive: many join cycles, large intermediate results, and repeated scans.

In the **RAPID / RAPID+** line of work we developed the **Nested TripleGroup Data Model and Algebra (NTGA)**, which processes groups of triples sharing a subject together, greatly reducing the number of MapReduce cycles and the size of intermediate results. Building on this, we developed:

* Algebraic optimization of RDF graph pattern queries and complex analytical (aggregation) SPARQL queries on MapReduce
* Scan-sharing and multi-query optimization for concurrent workloads
* Information passing (HIP) and adaptive early state pruning for join-intensive dataflows
* Strategies for nesting intermediate results, and support for unbound-property queries
* Semantics-aware storage models and type-based semantic optimization for knowledge graphs on Hadoop and Spark
* SYRql, a dataflow language for large-scale processing of RDF data

**Funding:** NSF III: Small award [IIS-1218277](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1218277) (PI), IBM Faculty Awards, and an NC State Faculty Research and Professional Development award (2011).

**Selected papers**
* From SPARQL to MapReduce: The Journey Using a Nested TripleGroup Algebra. *PVLDB 2011*.
* An Intermediate Algebra for Optimizing RDF Graph Pattern Matching on MapReduce. *ESWC 2011*.
* RAPID: Enabling Scalable Ad-Hoc Analytics on the Semantic Web. *ISWC 2009*.
* Algebraic Optimization for Processing Graph Pattern Queries in the Cloud. *IEEE Internet Computing 2013*.
* SYRql: A Dataflow Language for Large Scale Processing of RDF Data. *ISWC 2014*.
* Scaling Unbound-Property Queries on Big RDF Data Warehouses using MapReduce. *EDBT 2015*.
* Optimization of Complex SPARQL Analytical Queries. *EDBT 2016*.
* A Semantics-Aware Storage Framework for Scalable Processing of Knowledge Graphs on Hadoop. *IEEE BigData 2017* (Best Paper Award).
* Type-based Semantic Optimization for Scalable RDF Graph Pattern Matching. *WWW 2017*.
