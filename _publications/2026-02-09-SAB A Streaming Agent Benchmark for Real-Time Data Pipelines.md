---
title: "SAB: A Streaming Agent Benchmark for Real-Time Data Pipelines (Co-first Author, Under Review at ICDE 2027)"
collection: publications
permalink: /publication/2026-02-09-sab-streaming-agent-benchmark
excerpt: 'SAB is the first systematic benchmark for evaluating LLM-based controllers in production stream processing environments, transforming static text-to-SQL tasks from Spider 2.0 into 25 streaming-native control problems across six domains. Systematic test-time optimization yields a 200% relative improvement over single-shot generation, showing architectural design outweighs model scale.'
date: 2026-02-09
venue: 'Under review at ICDE 2027'
citation: 'Yinghui Xia*, Songyang Gao*, Hui Xiong. "SAB: A Streaming Agent Benchmark for Real-Time Data Pipelines." Under review, 2026. (*Equal contribution)'
---

## Abstract
We present **SAB**, the first systematic benchmark for evaluating LLM-based controllers in production stream processing environments. By transforming static text-to-SQL tasks from Spider 2.0 into streaming-native control problems spanning 25 tasks across six domains, SAB bridges the gap between offline semantic parsing and operational streaming requirements, incorporating event-time processing, stateful operators, and nested JSON aggregations absent in conventional benchmarks. Central to our framework is the decoupling of search strategy from validation mechanism, enabling fair comparison of optimization approaches. The Agent-Flow architecture demonstrates the efficacy of lightweight test-time optimization through its three-layer validation framework and structured feedback generation, achieving substantial gains against raw LLM baselines via iterative refinement without requiring execution feedback during the validation loop. Our experiments reveal that architectural design outweighs model scale in streaming SQL generation: systematic test-time optimization yields a **200% relative improvement** over single-shot generation, exceeding the performance variation across different base models. While these strategies significantly enhance capability, SAB exposes fundamental LLM limitations in handling streaming-specific challenges including deeply nested JSON parsing and complex multi-level aggregations, where current models achieve zero success. These findings establish that reliable streaming intelligence requires not merely larger models, but purpose-built architectures embedding validation and feedback directly into the agent loop. SAB provides the foundation for deploying autonomous agents capable of robust, efficient control in operational data pipelines.

## Keywords
streaming systems, text-to-SQL, LLM agents, benchmark, test-time optimization, real-time analytics
