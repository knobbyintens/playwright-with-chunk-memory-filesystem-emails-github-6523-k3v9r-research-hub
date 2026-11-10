# Efficient Tokenizers for Low-Resource Languages

Reference implementation and experiment scripts for the paper
"Efficient Tokenizers for Low-Resource Languages" (LREC 2027).

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

Amara Diallo, Peter Lindqvist, Ji-Won Park. Efficient Tokenizers for Low-Resource Languages. LREC 2027.
