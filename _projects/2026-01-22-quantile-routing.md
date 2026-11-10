---
title: "Quantile-Routed Mixture Transformers for Long-Context Retrieval"
authors: "Priya Raghunathan, Tobias Berg, Anneke Vos, Jae-Min Park"
venue: "Under review"
codepath: "code/quantile-routing"
summary: "A quantile-based routing scheme that keeps mixture-of-experts inference cheap at long context."
tags: "retrieval, mixture-of-experts, long-context"
---

Decoder-only backbones lose retrieval fidelity once the context window grows past a few tens of thousands of tokens. This project studies a quantile-routed mixture layer that assigns token spans to expert groups by calibrated uncertainty instead of top-k gating.
