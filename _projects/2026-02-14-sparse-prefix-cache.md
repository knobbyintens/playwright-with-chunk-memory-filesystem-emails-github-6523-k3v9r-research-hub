---
title: "Sparse Prefix Caching for Streaming Inference"
authors: "Dmitri Kovalenko, Hana Osei, Tobias Berg"
venue: "Under review"
codepath: "code/sparse-prefix-cache"
summary: "A cache-eviction policy that keeps streaming inference latency flat while preserving answer quality."
tags: "inference, caching, streaming"
---

Streaming assistants re-use long prompt prefixes across turns. This project develops a sparse eviction policy for page-attention caches that bounds memory without dropping the spans that later turns actually need.
