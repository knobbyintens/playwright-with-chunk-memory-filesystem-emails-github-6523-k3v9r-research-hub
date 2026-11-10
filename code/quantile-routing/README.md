# Quantile-Routed Mixture Transformers for Long-Context Retrieval

Reference implementation and experiment scripts for the paper
"Quantile-Routed Mixture Transformers for Long-Context Retrieval" (ICAS 2027).

## Layout

- `src/` — model and training code
- `experiments/` — configuration files for the reported runs
- `notebooks/` — analysis notebooks
- `results/` — aggregated metrics
- `tests/` — smoke tests

## Getting started

```bash
pip install -r requirements.txt
python -m src.train --config experiments/base.yaml
```

## Citation

Priya Raghunathan, Tobias Berg, Anneke Vos, Jae-Min Park. Quantile-Routed Mixture Transformers for Long-Context Retrieval. ICAS 2027.
