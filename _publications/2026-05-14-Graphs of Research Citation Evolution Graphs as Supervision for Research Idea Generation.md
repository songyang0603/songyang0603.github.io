---
title: "Graphs of Research: Citation Evolution Graphs as Supervision for Research Idea Generation (First Author, arXiv Preprint)"
collection: publications
permalink: /publication/2026-05-14-graphs-of-research
excerpt: 'We propose Graphs of Research (GoR), a supervised fine-tuning method that organizes a 2-hop citation neighborhood into a paper-evolution DAG and uses it as supervision for LLM-based research idea generation. GoR-SFT achieves SOTA against gpt-4o-driven baselines across head-to-head LLM-judge tournaments.'
date: 2026-05-14
venue: 'arXiv preprint (arXiv:2605.14790)'
paperurl: 'https://arxiv.org/abs/2605.14790'
citation: 'Songyang Gao*, Yinghui Xia*, Siyi Liu, Hui Xiong. "Graphs of Research: Citation Evolution Graphs as Supervision for Research Idea Generation." arXiv:2605.14790, 2026. (*Equal contribution)'
---

## Abstract
Research idea generation is the innovation-driving step of automated scientific research. Recently, large language models (LLMs) have shown potential for automating idea generation at scale. However, existing methods mainly condition LLMs on eliciting idea generation through static retrieval of relevant literature or complex prompt engineering, without discarding the structural relations among references. We propose **Graphs of Research (GoR)**, a supervised fine-tuning method that extracts a 2-hop reference neighborhood for each seed paper, derives the relations among those references from citation position, frequency, predecessor links, and publication time, and organizes them into a paper-evolution directed acyclic graph (DAG). We construct an automated extraction pipeline that draws data from five major ML/NLP venues, comprising 498/50/50 train/validation/test seed papers and approximately 7,600 cited references. Qwen2.5-7B-Instruct-1M is fine-tuned on a structured-text prompt that includes the citation graph, edge signals, reference information, and task definition to predict the idea for the seed paper. Across head-to-head LLM-judge tournaments against gpt-4o-driven baselines, **GoR-SFT achieves SOTA**, demonstrating the effectiveness of citation-evolution graphs as a supervision signal for LLM-based idea generation. We hope that this reduces the barrier for citation evolution graphs as a supervision, accelerating automated scientific innovation.

## Keywords
research idea generation, citation evolution graph, supervised fine-tuning, LLM agents, automated scientific research
