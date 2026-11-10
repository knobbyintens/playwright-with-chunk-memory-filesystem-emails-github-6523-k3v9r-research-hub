# Sparse Prefix Caching for Streaming Inference

Reference implementation and experiment scripts for the paper
"Sparse Prefix Caching for Streaming Inference" (JARL 2027).

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

Dmitri Kovalenko, Hana Osei, Tobias Berg. Sparse Prefix Caching for Streaming Inference. JARL 2027.
